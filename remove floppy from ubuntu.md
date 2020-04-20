# Remove floppy from Ubuntu

Io error fd0

`rmmod floppy`
`echo "blacklist floppy" | tee /etc/modprobe.d/blacklist-floppy.conf`
`dpkg-reconfigure initramfs-tools`