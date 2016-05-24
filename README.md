# imx6-linux

Copy 'imx_v6_v7_uspd_defconfig' to <linux_kernel>/arch/arm/config


Go to <linux_kernel>

> export LOADADDR=0x12000000

> export CROSS_COMPILE=arm-none-eabi-

> export ARCH=arm

> make imx_v6_v7_uspd_defconfig

> make uImage

> make imx6sx-sabreauto.dtb

