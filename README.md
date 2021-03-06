# MAGNETAR
<p align="center">
  <img src="https://github.com/Kyliekyler/MAGNETAR/blob/master/.github/logo.png"> 
</p>
 
<p align="center">
  <a href="https://t.me/MAGNETAR1999"><img src="https://img.shields.io/badge/Telegram-Channel-blue.svg"></a><br/><a href="https://t.me/MAGNETARCHAT"><img src="https://img.shields.io/badge/Telegram-Group-blue.svg"></a>
</p>
<br/>

Eliminate Lags and Throttling — Run Your Game Smoothly and Comfortably with No Substantial Performance Drops

# Notes
- Flash at your own risk, I'm not responsible for lost data or bricked devices

# Compatibility
- [![Android 5](https://img.shields.io/badge/Android-5-red.svg)]() [![Android 6](https://img.shields.io/badge/Android-6-pink.svg)]() [![Android 7](https://img.shields.io/badge/Android-7-violet.svg)]() [![Android 8](https://img.shields.io/badge/Android-8-yellow.svg)]() [![Android 9](https://img.shields.io/badge/Android-9-lightgreen.svg)]() [![Android 10](https://img.shields.io/badge/Android-10-brightgreen.svg)]() [![Android 11](https://img.shields.io/badge/Android-11-orange.svg)]()
- [![CPU ABI](https://img.shields.io/badge/ABI-32-pink.svg)]() [![Chipset](https://img.shields.io/badge/ABI-64-pink.svg)]()
- [![Magisk](https://img.shields.io/badge/Magisk-19%2B-00B39B.svg)]()
   
# Instructions
- Download and install the module
- Reboot after you finished installing

### Modes
- Changing modes can be done without having to reboot
just edit the mode.txt file to the mode you want

```
MODE
  0 = Adaptive Mode (Default)
      Dynamically changing through usage (Recommended)
  1 = Endurance Mode
      Lowering power draw by 20% to give more SOT
  2 = Balance Mode / Balance+ Mode
      Balancing power draw and performance stability
  3 = Extreme Mode
      Boosting device and better performance stability which is suitable for gaming
```

- There are also modes that cannot be changed and automatically
runs when certain conditions met like:

```
Sleep Mode = Pauses MAGNETAR processes when phone are turned off
           and continue processes when it was turned on             
Cooldown Mode = Monitors temp and automatically set low performance
           when temp reached above 45°C
Endurance+ Mode = Lowering power draw to avoid draining below
           10% batt capacity          
Charge Mode = Like adaptive mode but prioritizes temp over performance
           to avoid excess heating while phone is on charge
```

### Log Modes
- Changes logging style according to user preferences

```
LOG_MODE
  0 = Disable
      Disable module during boot
      (Need to reboot to reactivate)
  1 = Normal (Default)
      Refresh log every 60 seconds
  2 = Aggressive
      Refresh log every second
  3 = Sush
      Silence module logging but module continuously runs at background 
      (Need reboot to unsilence)
```

- There's also a log trimmer that is available to change

```
TRIM
  Default 'N' value is 100
    — Delete last 'N' log thread to avoid log spam
      'N' can be any number
```

# Changelog
### JULIET (2010052351)
- Added Android 11 Support
- Compiled w/ Clang 10.0.1
  - O3 Optimization Enabled
- Improved CPU Load Calculations
- Improved Config Backup & Restore
- Improved Game Detection
- Increased Temperature Threshold by 3°C
- Miscellaneous Changes
- New Modes
  - 0 = Adaptive
  - 1 = Endurance
  - 2 = Balance / Balance+
  - 3 = Extreme
- Optimized Overall Performance
- Various Bug Fixes & Stability Improvements

### INDIA (2006121454)
- Added Config Backup
  - Restores Default Config On Uninstall
- Added Error Logger
  - Can Be Found As "error.txt" On MAGNETAR Folder
- Improved Adaptive Mode
  - Better Game Detection
  - Much Accurate Mode Switcher
- Improved Performance
  - Better & Updated Tweaks
- Improved Charge Mode Algorithm
- Various Bug Fixes

### HOTEL (2005050000)
- Compiled w/ GCC 9
  - LTO & O3 Optimization Enabled
- All Tweaks Updated
- Bug Fixes
  - Fixed Folder Issue
  - Fixed Random Reboot
  - More...
- Added Doze Optimization
- Added Logging Switch
  - 0 = Disable Logging
  - 1 = Normal Logging
  - 2 = Aggressive Logging
  - 3 = Sush Logging
- Added Log Trimmer
  - Trim Logs Per Thread Count
- Added Game Mode (MODE 4)
  - Bypass Temp Limit
  - Better Ram Management For Gaming
  - Optimized Performance
  - Shows Current CPU/GPU/RAM Stats
- Added Ultra Powersave
  - Activated When Batt is Lower Than 10%
- Added Charge Mode
  - Activated When Charging
- Renamed Idle Mode to Powersave Mode
- Renamed Moderate Mode to Balanced Mode
- Disabled Module Detection
  - Run when Conflicting Module was Disabled
- Improved CPU and GPU Tuning
- Improved Adaptive and Sleep Mode
- Improved Mode Switching
- Improved Powesave Mode
  - 20% Less Power Draw
  - Improved SOT
- Improved Balanced Mode
  - 10% Less Power Draw
- Updated Conflict Library
- Stability Improvements

### GOLF (2004020115)
- Hotfix
  - Fixed Stucked Module
- A Bit Faster Module Logging

### GOLF (2004012304)
- Introduction of Modes
  - Adaptive 
  - Idle
  - Moderate
  - Performance
  - Cooldown – Triggered when Temp Hits 45°C
  - Sleep – Triggered when Screen was Turned OFF
- Mode Switch Made Easy
  - Can Be Done WITHOUT REBOOTING
  - See Instructions
- Support For All SOC
  - 32bit and 64bit
- Anti-Blocking Parameters Added
  - Unique ID For Each Installation
- Updated GPU Tweaks
- Fixed Missing Folder on Android 10
- API Support From As Low As Android 5
- Removed Unnecessary Script
- Various Bug Fixes & Improvements

### FOXTROT (1910121000)
- Various Important Bug Fix

### FOXTROT (1910112244)
- Fixed After-Reboot-Execution

### FOXTROT (1910111955)
- Fixed .MAGNE.BIN Path Detection

### FOXTROT (1910111550)
- Anti-Kang Parameters
- Fully Rewritten For Efficiency
- Not Forcing Config To Avoid Conflicts
- Force High Quality Graphics
- Added RAM Gaming Configuration
- Adjusted Kernel Gaming Config
- Removed Governor Config For CPU & GPU
- Fixed Lag When Certain Temp Reached
- Much Better Temps
- Removed SoundFX
- Updated Props
- Compiled With Clang 
  - 32bit and 64bit SOC Support
- All New Logging System
  - Detailed Logging
- Improved SOC Detection
  - Fixed Recovery Installation
- Smoother UI
  - FPS Unlocking
  - Auto Freq
- Reduced Idle Drain
  - Adjusted LPM Parameters
  - Disabled Debuggers
- EAS / HMP Tuning
- Better Color Adjustment
- More...
  
### ECHO (1909230945)
- Various Adjustments
- Smoother Performance
- Added SD855 Support
- Added SoundFX Opt-in/out
- Added More GPU/CPU Tweaks
- Fixed Wifi Issues On Some Devices
- Fixed Static Call Sound
- Fixed Scroll Bug
- Fixed Module Logging Duplicate
- Updated Thermal
- Better Idling
  - Reduced Heating
  - Lower Batt Consumption
- Updated Props
  - Removed Various Props
  - Reverted Some Props from Build 1909101057
- Smart Fast Charge
  - Lowering Charge Input When Battery Temp Reached 45°C
- Improved Log Checking
- Increased Override Time To 3mins After Boot

### DELTA (1909191327)
- Support for All Devices Using QComm Snapdragon SOC
- Improved System Speed
- Improved App Launch Speed
- Improved IPV4 Traffic
- Improved Module Logging
- Better Temperature
- Lower Battery Consumption
- Adjusted KCAL Values
- Updated Props
- Cleanup and Optimizations

### CHARLIE (1909101057)
- Performance Improvements
- Proper Android 10 Support
- Updated Props
- Extended Min API to 25
- Added More Devices to Run Service Script
- Added Thermal Bin to Entry-Level SOC
- Adjusted Tweaking Values
- Improved Module Logging
- Sound Mod Will Only Be Installed on AOSP Based Android 9 Rom (Device Specific)

### BRAVO (1908312141)
- Performance Improvements
- Adjusted Some Tweaking Values
- Fixed Some Settings That Didn't Get Applied
- Added Thermals On Flagship SOC 
- Added Module Logging
- Added Better BT Libs
- More... (Forgotten)

### ALPHA (1908281710)
- Initial Release

# Special Thanks To
- [@TheWolfGirl02](https://t.me/TheWolfGirl02)
- [@MrCarb0n](https://t.me/MrCarb0n)
- [@ardasuzen](https://t.me/ardasuzen)
- [@Drizzy00](https://t.me/Drizzy00)
- All of the Testers
