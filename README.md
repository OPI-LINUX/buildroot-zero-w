
<div align = center>

# Buildroot orangepi zero-w
*Buildroot Package Mainly for Orangepi Devices. Support Allwinner  F133 / D1s*

<br>

<br>

<br>
</div>

## Quick Start-up

```
git clone https://github.com/OPI-LINUX/buildroot-zero-w   # Clone the code of buildroot-zero-w
cd buildroot-zero-w                                       # Change to the directory
source envsetup.sh                                        # Set the build environment
lunch                                                     # lunch the buildroot environment
make orangepi_zero_w_defconfig                            # Select target board
make                                                      # Build and pack
```
For more details, please check [Documentation]

## About Buildroot

```
Buildroot is a simple, efficient and easy-to-use tool to generate embedded
Linux systems through cross-compilation.

The documentation can be found in docs/manual. You can generate a text
document with 'make manual-text' and read output/docs/manual/manual.text.
Online documentation can be found at http://buildroot.org/docs.html

To build and use the buildroot stuff, do the following:

1) run 'make menuconfig'
2) select the target architecture and the packages you wish to compile
3) run 'make'
4) wait while it compiles
5) find the kernel, bootloader, root filesystem, etc. in output/images

You do not need to be root to build or run buildroot.  Have fun!

Buildroot comes with a basic configuration for a number of boards. Run
'make list-defconfigs' to view the list of provided configurations.

Please feed suggestions, bug reports, insults, and bribes back to the
buildroot mailing list: buildroot@buildroot.org
You can also find us on #buildroot on Freenode IRC.

If you would like to contribute patches, please read
https://buildroot.org/manual.html#submitting-patches
```


<!----------------------------------------------------------------------------->

