## Save img on the MicroSD

1- dd if=FreeBSD-13.1-RELEASE-arm-armv7-GENERICSD.img of=/dev/{{device ID}} bs=1m conv=sync

2- dd if=u-boot-orangepi-zero/u-boot-sunxi-with-spl.bin of=/dev/{{device ID}} bs=1024 seek=8 conv=sync

