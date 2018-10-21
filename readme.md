PXE-Boot
=======

repo containing scripts to set up PXE booting on Ubuntu Server, Raspain and 
Synology NAS devices.

- **Synology** assumes a root of `/volume1/pxe/`
-- a few manual steps to edit pxelinux.cfg/default & unzip files
- **Raspian** assumes a root of `/srv/tftp`
-- one step to edit pxelinux.cfg/default
- **Ubuntu** assumes a root of `/var/lib/tftpboot`
-- one step to edit pxelinux.cfg/default

See [Bootscreens repo](https://github.com/chris18890/boot-screens) for menu 
and display structure.
