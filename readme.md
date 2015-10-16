PXE-Boot
=======

A repo containing scripts & commands to set up PXE booting on Ubuntu, Debian, and Synology NAS devices. 
This project can chain boot into [netboot.xyz](https://netboot.xyz)

Note - this project only works when booting in BIOS mode, it does not work when booting in UEFI mode

- **Synology** assumes a root of `/volume1/pxe/`  
    - A few manual steps to edit pxelinux.cfg/default & unzip files  
    - Use [this Synology KB article](https://kb.synology.com/en-global/DSM/tutorial/How_to_implement_PXE_with_Synology_NAS) to set up the PXE/TFTP service  
- **Debian** assumes a root of `/srv/tftp`  
    - One manual step to edit pxelinux.cfg/default  
    - Use [this Debian wiki article](https://wiki.debian.org/PXEBootInstall#Set_up_TFTP_server) to set up the PXE/TFTP service  
    - [This blog post](https://reintech.io/blog/setting-up-pxe-boot-server-debian-12) is also a good article  
- **Ubuntu** assumes a root of `/var/lib/tftpboot`  
    - One manual step to edit pxelinux.cfg/default  
    - Use [this Ubuntu article](https://ubuntu.com/server/docs/how-to-netboot-the-server-installer-on-amd64) to set up the PXE/TFTP service  
    - [This blog post](https://reintech.io/blog/setting-up-pxe-boot-server-ubuntu-22) is a good article for Ubuntu  
    - [This blog post](https://reintech.io/blog/configure-pxe-boot-server-ubuntu-2004) is also a good article Ubuntu  

See [Bootscreens repo](https://github.com/chris18890/boot-screens) for menu and display structure.
