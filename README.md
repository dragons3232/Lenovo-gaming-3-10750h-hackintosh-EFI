# Lenovo-gaming-3-10750h-hackintosh-EFI
I had a hard time to find a working hackintosh EFI for my lenovo gaming 3. I guess some one out there is looking for this. So here we go :))

# Working features
1. Intel UHD Graphics 630 1536 MB
2. Brightness control (Replace config.plist with config_after_installation.plist under /EFI/EFI/CLOVER)
3. Audio (Install VoodooHDA 2.9.2 Clover to ESP) and connect to bluetooth speaker

# Notice
You will find 2 versions of config.plist file under /EFI/EFI/CLOVER. Because of an issue with low brightness at boot, you need to use default config.plist when you want to install Catlina so that you can see what is displayed on your screen.
After installation of your Catalina, you can replace config.plist with another version of config_after_installation.plist which can be found in same directory (rename it to config.plist).
At next boot, your screen will be under very low brightness. But that will be fixed after few minutes. All you need to do is to wait. Trust me

ENJOY !!!
