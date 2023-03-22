include $(TOPDIR)/rules.mk

PKG_NAME:=test-bar
PKG_VERSION:=1.0.0
PKG_RELEASE:=1

PKG_LICENSE:=Public-Domain

include $(INCLUDE_DIR)/package.mk

define Package/test-bar
  SUBMENU:=Compression
  SECTION:=utils
  CATEGORY:=Utilities
  URL:=https://example.com
  TITLE:=test-bar
endef

Build/Compile:=:

define Package/test-bar/install
	touch $(1)/test-bar
endef

$(eval $(call BuildPackage,test-bar))
