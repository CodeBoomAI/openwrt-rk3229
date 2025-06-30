#
# Copyright (C) 2024 CodeBoomAI
#

include $(TOPDIR)/rules.mk
include $(INCLUDE_DIR)/image.mk

define Device/rk322x_box
  DEVICE_VENDOR := Generic
  DEVICE_MODEL := RK322x Box
  DEVICE_DTS := rk3229-box
  IMAGE_SIZE := 128m
  SUPPORTED_DEVICES := rk322x-box
endef
TARGET_DEVICES += rk322x_box

$(eval $(call BuildImage))
