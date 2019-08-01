# OsxAptioFixDrv-free2000

This is an alternative driver for ColverEFI to walk-around the memory layout problem (mainly happens on x99 platform).

For details, please refer to the [original discussion thread](https://sourceforge.net/p/cloverefiboot/tickets/125/).

## Compile

The code is pretty old. I used to compile it with Clover r3354 and tested with r3354 and r3469. It may not work with newer Clover build.

1. Download the source code of [Clover](https://sourceforge.net/projects/cloverefiboot/)
2. Replace the files in `Clover/OsxAptioFixDrv` by this repo
3. Compile as usual and the final binary is `OsxAptioFix2Drv`; feel free to rename it
