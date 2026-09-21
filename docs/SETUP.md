Mounting the drive:

I first ran ```sudo mkdir -p /mnt/cloud-storage```, identified my HDD by using ```lsblk``` and mounted it using ```sudo mount /dev/yourstoragedrive /mnt/cloud-storage```. I also configured ```/etc/fstab``` to mount my drive automatically upon boot.

PC syncing:

After confirming that the service works by visiting the Nextcloud dashboard, I installed the Nextcloud Desktop Client on my personal computer so I could sync it with my server and automatically save files of my choosing in my cloud. The desktop client application is very intuitive with its UI so I will not be going over it.

Nextcloud Dashboard:

I did minimal configurations to the dashboard, it has a very intuitive set up making it very easy to understand even if it's your first time seeing it.
