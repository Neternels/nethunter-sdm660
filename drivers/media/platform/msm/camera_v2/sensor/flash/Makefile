# SPDX-License-Identifier: GPL-2.0-only
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/cci
ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/io
obj-$(CONFIG_MSMB_CAMERA) += msm_flash.o
ifeq ($(CONFIG_MACH_ASUS_SDM660),y)
obj-$(CONFIG_MSMB_CAMERA) += msm_subflash.o
endif
