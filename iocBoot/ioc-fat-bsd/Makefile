IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.6.1
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME := lcls-plc-fat-bsd
PROJECT_PATH := ../../lcls-plc-fat-bsd/lcls-plc-fat-bsd.tsproj
PLC := fat_bsd

PYTMC_OPTS := 
PREFIX := PLC:BSD:FAT

include $(IOC_TOP)/iocBoot/templates/Makefile.base
