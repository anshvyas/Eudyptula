obj-m +=Hello.o
 

all:

	make -C $(shell echo $(KERN_PATH)) M=$(shell pwd) modules

clean:

	make -C $(shell echo $(KERN_PATH)) M=$(shell pwd) clean
