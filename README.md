This is the cross compiler used to build [u-boot-sunxi](https://github.com/moddevices/u-boot-sunxi).

`arm-none-linux-gnueabi` is initially provided by [codesourcery](http://www.codesourcery.com/).
The toolchain is based on GCC and optimized for ARM devices.

Codesourcery has a product called [Sourcery G++ Lite Edition](http://www.codesourcery.com/sgpp/lite/arm/), the command-line version is free, the IDE is not.

To build u-boot-sunxi add the $(pwd)/bin to your PATH (must be first place) and run:
`make sun7i CROSS_COMPILE=arm-none-linux-gnueabi-`
