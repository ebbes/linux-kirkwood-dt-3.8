linux-kirkwood-dt-3.8

-----------------

Simple PKGBUILD for building a device-tree enabled kernel 3.8 for Marvell Kirkwood devices.
This is based on Arch Linux ARM's PKGBUILD, but adjusted to kernel 3.8.
I have included some patches that I use for my GoFlex Net:
	* Adjust GoFlex Net NAND chip-delay
	* Add netdev LED-trigger to display network activity
	* Add sata-disk LED-trigger to display SATA activity
	* Set sata-disk trigger as default for GoFlex Net orange LED

Maybe someone has any use for it.
