# mt7902 driver development
Developing driver for mt7902 taking code base from `linux-6.12.5` from folder `drivers/net/wireless/mediatek` and modifing the code of mt7921.

## Working with Kernel Modules in Linux
you can check currently loaded modules by `lsmod`. 
you can load a .ko kernel module by `insmod`. 
you can check if a module is already present in your kernel by `modinfo`. 
you can load already present module in kernel by `modprobe`. 
Insert the module in your kernel by 

    sudo modprobe mt76-connac-lib
    sudo modprobe mt76
    sudo modprobe mt76-sdio
    sudo modprobe mt76-usb
    sudo modprobe mt76x02-lib
    sudo modprobe mt76x02-usb
    sudo modprobe mt792x-lib
    sudo modprobe mt792x-usb


