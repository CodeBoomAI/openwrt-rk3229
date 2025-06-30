#
# Copyright (C) 2024 CodeBoomAI
#

include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=rockchip
SUBTARGET:=armv7
BOARDNAME:=Rockchip ARMv7 (e.g. RK322x)
FEATURES:=ext4 usb display gpio fpu
CPU_TYPE:=cortex-a7

KERNEL_PATCHVER:=5.10

include $(INCLUDE_DIR)/target.mk

DEFAULT_PACKAGES += kmod-usb-core kmod-usb-ohci kmod-usb2

$(eval $(call BuildTarget))
