include $(TOPDIR)/rules.mk

PKG_NAME:=test-foo
PKG_VERSION:=1.0.0
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/test-foo
  SUBMENU:=Compression
  SECTION:=utils
  CATEGORY:=Utilities
  URL:=https://example.com
  TITLE:=test-foo
  DEPENDS:=+test-bar
endef

Build/Compile:=:

define Package/test-foo/install
	touch $(1)/test-foo
endef

$(eval $(call BuildPackage,test-foo))
