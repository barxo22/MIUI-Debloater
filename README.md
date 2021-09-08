# MIUI debloater script
A universal and easy way to bring fresh air your Xiaomi phone running MIUI!

# PREREQUISITES
1. ADB drivers installed on your PC
2. Device running MIUI (MIUI 12.5-10 tested)
3. USB debugging enabled on device

# CHOOSING THE RIGHT SCRIPT FOR YOUR NEEDS
First of, there are 2 different scripts:
- Light version
- Extreme version

The light version uninstall only the useless bloatware, the extreme version also uninstalls some system apps which are not gonna break the system integrity, obviously.
If you're using Windows, download the latest .bat script.
If you're using any Linux distribution, download the latest .sh script.

# HOW TO INSTALL ADB DRIVERS ON WINDOWS
Download [the 15 seconds adb installer](https://forum.xda-developers.com/t/official-tool-windows-adb-fastboot-and-drivers-15-seconds-adb-installer-v1-4-3.2588979/) and follow the instructions and it should work (otherwise follow [this](https://www.xiaomidriversdownload.com/xiaomi-adb-drivers-official/) guide for installing drivers manually.

# HOW TO INSTALL ADB DRIVERS ON LINUX DISTRIBUTIONS
-Debian & based distributions: sudo apt-get install android-tools-adb

Other distributions: google it lol

# USAGE
Windows: double-click .bat file 
Linux: open terminal in the directory where you saved the file and use the following command: ./filename.sh (replace filename with the file name)

# TROUBLESHOOTING
no devices/emulators found: this is an error which is related to device connection, check if usb debug is enabled on phone and if you get any confirmation popup, agree (could also be some driver which is not installed correctly on the computer)

FAILURE not installed for 0: just don't worry, it just means that the app is already uninstalled

