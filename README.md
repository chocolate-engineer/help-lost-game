# help-lost-game

## 1. Install Whisky

[Download Whisky App to Emulate Windows](https://data.getwhisky.app/Releases/v2.3.5/Whisky.zip)

Click through the installations and add to Applications folder

## 2. Download SteamSetup.exe

Download the Windows installer for Steam

[SteamSetup.exe](https://cdn.akamai.steamstatic.com/client/installer/SteamSetup.exe)

## 3. Add Whisky to Trusted Apps

You need to enable whisky to your trusted device in the apple menu

System Preferences --> Privacy & Security --> App Management. Add Whisky here.


## 4. Create a Bottle in Whisky

Pick Windows 10 

Drag and drop SteamSetup.exe into there

Run and click through the installation as normal

## 5. Add steam.exe as a Program

Open your C: Drive, and look for steam.exe in Program Files (x86 or not)

## 6. Add args and re-run with new args
Before first launch

```
-forcesteamupdate -forcepackagedownload -overridepackageurl http://web.archive.org/web/20250306194830if_/media.steampowered.com/client -exitsteam
```

Run and let it update

Before second launch

```
-noverifyfiles -nobootstrapupdate -skipinitialbootstrap -norepairfiles -overridepackageurl
```

Launch as normal

## 6. Install Lockdown Protocol

## 7. Run Lockdown Protocol with certain arguments

Go to the little Gear icon on steam > properties > General > Launch options
```
-dx9 -novid -console
```

Start your game

Say no to drivers
