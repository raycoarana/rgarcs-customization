Several configuration files customized for Anbernic RG ARC S to make it work properly with themes.
## Info about OS paths
Firmware themes
/usr/share/emulationstation/themes/

Firmware EmulationStation systems
/usr/share/emulationstation/es_systems.cfg

Firmware EmulationStation features
/usr/share/emulationstation/es_features.cfg

Firmware PSX/PSP Bios
/usr/share/psxbios/

Firmware Splash
/usr/share/anbernic/splash/

Firmaware Defaults
/usr/share/anbernic/datainit/

## Installation

### Systems
scp es_systems.cfg root@192.168.1.124:/usr/share/emulationstation/es_systems.cfg

### Features
scp es_features.cfg root@192.168.1.124:/usr/share/emulationstation/es_features.cfg

### Settings
scp es_settings.cfg root@192.168.1.124:/userdata/system/configs/emulationstation/es_settings.cfg

## Commands

Restart EmulationStation without restart the device
/etc/init.d/S31emulationstation restart

Store changes in the overlay (prevent loosing it on device restart)
anbernic-save-overlay

## PortMaster fixes

GTA 3 => libmpg123
GTA Vice City => libmpg123
Sonic Mania => several 64bit libs


TODO:
===
 - Kodi
 - Fix playing videos (possible?)
 - Script to record video?
 - Update PortMaster to latest version installing missing dependencies
 - Add customized PortMaster mapping files to repo (Carmageddon,...)
 - Fix Solarus key mapping
 - Scummvm mapping in Retroarch or update standalone to fix whites in BladeRunner
