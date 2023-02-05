# GD32Vduino

Arduino core for GD32V MCUs.

Initially the purpose of this project is to add Linux host support for [Longduino](https://github.com/sipeed/Longduino) 
for Arduino IDE.


## Board Manager URL
```
https://raw.githubusercontent.com/onelife/gd32vduino/main/package_gd32v_index.json
```


## Packages
- You may change the following line in `hardware/gd32v/0.1.1/boards.txt` for more Flash memory space.

```
# For example change the number 65536 to 126976
eval.upload.maximum_size=65536
```


## Tools (GCC Compiler, OpenOCD, and etc.)
- The Windows tools are copied from [Sipeed Longduino](https://dl.sipeed.com/shareURL/LONGAN/Longduino/tools).
- The Linux tools are copied from [Sipeed platformio](https://dl.sipeed.com/shareURL/LONGAN/platformio/dl-packages) and 
repacked.
- GCC compiler is hosting in Dropbox as oversized.


## GD32V
- [GD32VF103](https://www.gd32mcu.com/cn/download?kw=GD32VF1)


## Sipeed Longan Nano Board
- [Sipeed Longan](https://longan.sipeed.com/)
