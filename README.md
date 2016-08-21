#battman-firmware
Firmware for the "battman" battery management system.
##Setup
 Clone repostiory. 
```
git clone https://github.com/raphaelchang/battman-firmware.git
```
 Fetch the ChibiOS submodule.
```
git submodule init
git submodule update
```
##Compiling
You'll need to install the following gcc arm cross compiler.
```
sudo apt-get install gcc-arm-none-eabi
```
To build the files. Navigate to the root of the repository and run the following:
```
make
```
