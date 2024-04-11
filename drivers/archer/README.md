## How to install to odroid

1. `make clean`
2. `make`
After compiling, you can see a name of the `chip.ko` file is stored in the directory of the driver. Run the following command to load the driver
3. `sudo cp 88x2bu.ko /lib/modules/[kernel version]/kernel/drivers/net/wireless/ ` #[kernel version] is the directory name of the system kernel version
4. `sudo depmod –a`
5. `sudo modprobe 88x2bu.ko`
Or directly use insmod to load the driver.
6. `sudo insmod 88x2bu.ko`
After loading the driver, run the following command to check if the driver is successfully loaded
7. `lsmod`