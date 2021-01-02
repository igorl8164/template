Шаблон для проектов

Workspace
	Project 
		Docs`
		Firmware
		Hardware
		Mechanical
		
		
###   Splash screen
splash screen is a PNG file at /usr/share/plymouth/themes/pix/splash.png
 
---
### Set screen black on boot

sudo nano /boot/cmdline.txt

consoleblank=1 logo.nologo quiet loglevel=0 plymouth.enable=0 vt.global_cursor_default=0 plymouth.ignore-serial-consoles splash fastboot noatime nodiratime noram

sudo nano /boot/config.txt

disable_splash=1

sudo reboot
