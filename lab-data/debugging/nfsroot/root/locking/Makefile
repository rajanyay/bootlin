ifneq ($(KERNELRELEASE),)
obj-m := locking_test.o
else
KDIR ?= $(HOME)/debugging-labs/src/linux
all:
	$(MAKE) -C $(KDIR) M=$$PWD

clean:
	$(MAKE) -C $(KDIR) M=$$PWD clean
endif
