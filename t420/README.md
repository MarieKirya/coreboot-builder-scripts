Lenovo T420
===========

### Prep work
A flashrom binary dump of the stock T420 BIOS is needed to compile Coreboot.

* Place a copy of this dump under the T420 `stock_bios` directory and name it `stock_bios.bin` (to put it another way `./t420/stock_bios/stock_bios.bin`)

### Compiling
Build the latest merged into the master git branch:  
`./build.sh --bleeding-edge t420`

Latest stable release:  
 `./build.sh x420`

### Output

`coreboot_lenovo-t420-complete.rom` - The complete Coreboot ROM is the 8MB version used for internal or external flashing.   
`coreboot_lenovo-t420-complete.rom.sha256` - sha256 checksum of 8MB Coreboot Rom
