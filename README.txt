
                   Operating System - ASSIGNMENT


❖ Download the latest stable Linux kernel from
kernel.org, compile it, and dual boot it with your
current Linux version. Your current version as well
as the new version should be present in the
grub-menu.

1.Download the source code:   wget http://cdn.kernel.org/pub/linux/kernel/v5.x/linux-5.14.tar.xz

2.Install the required packages: 
                                                        i.sudo apt-get update
							    ii.sudo apt-get install git fakeroot build-essential ncurses-dev xz-utils libssl-dev bc							

3.Extract/untar the archive :   tar xf linux-5.14.tar.xz

4.Change directory to extracted folder: cd linux-5.14
                                  
5.Configure the kernel features:   cp /boot/config-$(uname -r) .config
                                
6.Install tools:  sudo apt-get install libncurses-dev flex bison openssl libssl-dev dkms libelf-dev libudev-dev libpci-dev libiberty-dev autoconf

7.Configure the kernel: make menuconfig

8.Compilation of kernel: 
                                           i.sudo make
					 ii.sudo make modules_install		
                                   iii.sudo make install
						
9.Verification:   uname -r
                              
			           

# os
