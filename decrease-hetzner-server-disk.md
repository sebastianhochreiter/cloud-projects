Create new volumen and new server

Mount new volume in old server

df -h
lsblk

rsync -avx / /mnt/external-disk/

Dismount volume and mount in new server

sudo rsync -avx /mnt/external-disk/ /mnt/external-disk/




