# android_samsung_sm-g355h_kernel
  Linux kernel release 3.x <http://kernel.org/>

1. How to Build
	- (Toolchains and initramfs.cpio already built)

	$ make kanas3g_hw04_defconfig                
	$ make
	
2. Output files
	- Kernel : Kernel/arch/arm/boot/zImage amd Image
	- module : Kernel/drivers/*/*.ko
	
3. How to Clean	
    $ make clean  

                         
########################           
email:microzans@gmail.com         
Thanks Y300-0100
