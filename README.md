## Installation

* Download the sources from master branch 
MediaTek_mt7610u_STA_driver_Linux 64bit.zip

* Unzip and cd MediaTek_mt7610u_STA_driver_Linux 64bit
* run the following commands

```bash
make clean
sudo make 
sudo make install 
```

## Supported Hardware

* Elecom WDC-433SU2M

For other chipsets some files need modification including the following

* Makefile
* os/linux/config.mk 
* common/rtusb_dev_id.c