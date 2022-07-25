#
# Copyright (C) 2014 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=linux-firmware
<<<<<<< HEAD
PKG_VERSION:=20221012
=======
PKG_VERSION:=20220209
>>>>>>> 30f160bc8... Merged changes from internal repo.
PKG_RELEASE:=1

PKG_SOURCE_URL:=@KERNEL/linux/kernel/firmware
PKG_SOURCE:=$(PKG_NAME)-$(PKG_VERSION).tar.xz
<<<<<<< HEAD
PKG_HASH:=e9d174af729511c8cccb60ec4e0b223b3c44b67d813b42d1ab9813acfa667fa5
=======
PKG_HASH:=e2e46fa618414952bbf2f6920cd3abcddbef45bfb7d1352994b4bfc35394d177
>>>>>>> 30f160bc8... Merged changes from internal repo.

PKG_MAINTAINER:=Felix Fietkau <nbd@nbd.name>

SCAN_DEPS = *.mk

include $(INCLUDE_DIR)/package.mk

define Package/firmware-default
  SECTION:=firmware
  CATEGORY:=Firmware
  URL:=http://git.kernel.org/cgit/linux/kernel/git/firmware/linux-firmware.git
  TITLE:=$(1)
  DEPENDS:=$(2)
endef

define Build/Compile

endef

include $(wildcard ./*.mk)
#$(eval $(call BuildPackage,linux-firmware))
