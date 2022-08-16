# MAPS-Boot
MAPS boot partition's files (zynq-7000)

## Introduction
a linux system consist of two partitions one is /boot and the second is fs(filesystem):

* <p>/boot partition files for our borad (xilinx zynq700) are generated from tool called petalinux which takes a hardware design file (.xsa) and a fsbl file and output BOOT.BIN, image.ub and system.dtb. </br>
these files are to put in the * /boot partition on a linux system.</p>

* <p>/fs partition is the filesystem partiotion 
filesystem can be download according to the distro(ubuntu, debian etc') and versions (7, 10.11, 18.4 etc) needed.</p>

## What's in the repo
resources:
* .XSA file - Xlinx Shell Archive for HW design.

Boot files:
* internal_emmc - BOOT.BIN, image.ub, system.dtb suited to run from internal emmc.
* external_emmc - BOOT.BIN, image.ub, system.dtb suited to run from external emmc (i.e SDCard).

## Resources:
* debian10.11 - <a href="\\storage\UsersPublic\IsraelY\MAPS_resources\debian-1011-minimal-armhf-2021-11-02.tar"> debian-1011-minimal-armhf-2021-11-02.tar
</a>

## How to use
documentation about how to preapare SDCard and boot from it can be found <a href=""> here </a>.
</br>documentation about how to preapare boot partition to run from internal memory can be found <a href=""> here </a>.</br>



### Authors
Israel Yesha'ayahu (israely@insightec.com)

### copyright
Copyright © 2002 by InSightec