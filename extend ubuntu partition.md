# Extend Ubuntu Partition

`lvextend -l +100%FREE /dev/ubuntu-vg/ubuntu-lv`
`resize2fs /dev/ubuntu-vg/ubuntu-lv`

If it shouts about not having enough space:

`rm -rf /var/cache/apt/*`