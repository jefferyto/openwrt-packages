#
# Copyright (C) 2018 Jeffery To
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=test-package
PKG_VERSION:=0.0.1
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/test-package
  SECTION:=net
  CATEGORY:=Network
  TITLE:=A Tor pluggable transport proxy, implementing obfs4
  URL:=https://gitlab.com/yawning/obfs4
  DEPENDS:=+obfs4proxy
endef

Build/Compile:=:

define Package/test-package/install
	touch $(1)/test-package
endef

$(eval $(call BuildPackage,test-package))
