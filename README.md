# Lenovo-gaming-3-10750h-hackintosh-EFI
I had a hard time to find a working hackintosh EFI for my lenovo gaming 3. I guess some one out there is looking for this. So here we go :))

# Upgrading to Sonoma from Ventura
1. Download **[https://github.com/dragons3232/Lenovo-gaming-3-10750h-hackintosh-EFI/blob/main/EFI Ventura to Sonoma.zip](https://github.com/dragons3232/Lenovo-gaming-3-10750h-hackintosh-EFI/blob/main/EFI%20Ventura%20to%20Sonoma.zip)** and extract it to Volumes/EFI/EFI (This EFI is required to access WIFI to download Sonoma)
2. Download Sonoma from https://apps.apple.com/us/app/macos-sonoma/id6450717509
3. Install Sonoma by following instructions on the screen
4. After successfully updating to Sonoma, download [https://github.com/dragons3232/Lenovo-gaming-3-10750h-hackintosh-EFI/blob/main/EFI Sonoma.zip](https://github.com/dragons3232/Lenovo-gaming-3-10750h-hackintosh-EFI/blob/main/EFI%20Sonoma.zip) and extract it to Volumes/EFI/EFI to overwrite.

# Upgrading to Sequoia from Sonoma
1. Go to System Settings => Apple Account => disable `Find My Mac` in iCloud (reveal it in See All apps)
2. Run this command in Terminal: `sudo softwareupdate -i -a -R`
3. Wait for it to download and upgrade your Mac
4. After successful upgrade, no more WIFI. In order to fix, use EFI Sequoia and download HeliPort to access WIFI
5. Disable Wifi icon in System Settings => Control Center
6. Set HeliPort to launch at system start in Settings => General => Login Items & Extensions.

# Working features
1. Intel UHD Graphics 630 1536 MB
2. Brightness control
3. Audio & Microphone
4. All USB ports
5. Webcam
6. Wifi

# Not working
1. HDMI port (use USB 3.0 to HDMI from Unitek instead)
2. Trackpad

ENJOY !!!
