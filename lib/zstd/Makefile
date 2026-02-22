# ZSTD Library for Kernel 4.14 - Final Stable Build
obj-$(CONFIG_ZSTD_COMPRESS) += zstd_common.o entropy_common.o fse_compress.o fse_decompress.o huf_compress.o huf_decompress.o compress.o decompress.o

ccflags-y += -I$(srctree)/lib/zstd -O3
