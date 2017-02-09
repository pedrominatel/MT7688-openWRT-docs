*Before start, use gcc 4.7*

**Links**

https://github.com/widora/openwrt_widora
https://github.com/widora/u-boot-mt7688


*Uboot build*

	
$ git clone https://github.com/widora/u-boot-mt7688.git
	
$ sudo tar xvfj buildroot-gcc342.tar.bz2 -C /opt/
	
$ sudo apt-get install openjdk-7-jdk
	
$ cd u-boot-mt7688
	
$ make clean

$ make

$ls uboot.bin
