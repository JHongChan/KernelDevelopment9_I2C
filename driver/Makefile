obj-m += i2c_driver.o
all:
	make -C /home/sice/kj_gjx_embedd_base/lab_8/linux-3.5 M=`pwd` modules
	cp i2c_driver.ko /opt/rootfs/lib/modules/3.5.0cyh/lab9_I2C_device_driver/i2c_driver.ko
clean:
	make -C /home/sice/kj_gjx_embedd_base/lab_8/linux-3.5 M=`pwd` modules clean
