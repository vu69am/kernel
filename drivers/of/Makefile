# SPDX-License-Identifier: GPL-2.0
obj-y = base.o device.o platform.o property.o
obj-$(CONFIG_OF_KOBJ) += kobj.o
obj-$(CONFIG_OF_DYNAMIC) += dynamic.o
obj-$(CONFIG_OF_FLATTREE) += fdt.o
obj-$(CONFIG_OF_EARLY_FLATTREE) += fdt_address.o
obj-$(CONFIG_OF_PROMTREE) += pdt.o
obj-$(CONFIG_OF_ADDRESS)  += address.o
obj-$(CONFIG_OF_IRQ)    += irq.o
obj-$(CONFIG_OF_UNITTEST) += unittest.o
obj-$(CONFIG_OF_RESERVED_MEM) += of_reserved_mem.o
obj-$(CONFIG_OF_RESOLVE)  += resolver.o
obj-$(CONFIG_OF_OVERLAY) += overlay.o
obj-$(CONFIG_OF_NUMA) += of_numa.o
obj-$(CONFIG_OF_DTBO) += dtbocfg.o

ifdef CONFIG_KEXEC_FILE
ifdef CONFIG_OF_FLATTREE
obj-y	+= kexec.o
endif
endif

obj-$(CONFIG_OF_UNITTEST) += unittest-data/
