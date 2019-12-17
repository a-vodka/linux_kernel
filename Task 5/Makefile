obj-m += chrdev.o

PATHTOMOD=/lib/modules/4.15.0-72-generic/build

all:
	make -C ${PATHTOMOD} M=$(PWD) modules

clean:
	make -C ${PATHTOMOD}/build M=$(PWD) clean
