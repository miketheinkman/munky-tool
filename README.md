# munky-tool
Munky-tool is an on-board android utility that runs in Terminal Emulator

Munky-tool v1.0 supports dumping system, efs, and boot partitions for backup or use in kitchen. It also supports contacts backup and restore, logcat, and it goes out for a rip.

Munky-tool will identify and copy most partitions, however some devices have weird partition names. I will add support for more devices, and possibly more features as time goes on. 

# INSTALLATION and use

-Place munky-tool in the system partition. I use /, but /system, or any directory where you can set permissions should be fine. 

-Chmod 775 or better the munky-tool script (not the munky-tool directory).

-Open Terminal Emulator app.

-Request root (type 'su' without quotes and hit ENTER).

-Change directory to munky-tool (cd /pathtotool/munky-tool)

-Execute munky-tool script (type './munky-tool' without quotes and hit ENTER).

-Enjoy munky-tool
