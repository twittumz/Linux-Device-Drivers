obj-m:=helloworld.o
KERNDIR= /lib/modules/$(shell uname -r)/build/
PWD:=$(shell pwd)

default:
	$(MAKE) -C $(KERNDIR) M=$(PWD) 

