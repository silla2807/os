
Operating System - ASSIGNMENT
❖ Download the latest stable Linux kernel from
kernel.org, compile it, and dual boot it with your
current Linux version. Your current version as well
as the new version should be present in the
grub-menu.
1. wget http://cdn.kernel.org/pub/linux/kernel/v5.x/linux-5.14.tar .xz
2. sudo apt-get update
3.sudo apt-get install git fakeroot build-essential ncurses-dev
xz-utils libssl-dev bc
4. tar xf linux-5.14.tar.xz
5.cd linux-5.14 4.
6.cp /boot/config-$(uname -r) .config
7. sudo apt-get install libncurses-dev flex bison openssl
libssl-dev dkms libelf-dev libudev-dev libpci-dev
libiberty-dev autoconf
8.make menuconfig
9.sudo make
10.sudo make modules_install
11.sudo make install
12.uname -r

# os
