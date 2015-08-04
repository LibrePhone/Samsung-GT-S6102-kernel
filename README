HOW TO BUILD KERNEL 2.6.35 FOR GT-S6102

1. How to Build
	- Get a toolchain for ARM
	You may for example use the cross-compilers available from standard Debian repositories or emdebian.org. 
	Or visit http://www.codesourcery.com/, download and install Sourcery G++ Lite 2009q3-68 toolchain for ARM EABI.

	- Build:
	$ make bcm21553_torino_02_defconfig zImage -j16

    ARCH=arm and CROSS_COMPILE=arm-linux-gnueabihf- are pre-set in the Makefile.

2. Output files
	- Kernel : kernel/common/arch/arm/boot/zImage
	
3. How to make .tar binary for downloading into target
	$ cd kernel/common/arch/arm/boot
	$ tar -cvf GT-S6102_Kernel_Gingerbread.tar zImage
