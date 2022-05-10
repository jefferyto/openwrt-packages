
include $(TOPDIR)/rules.mk

PKG_NAME:=gh-action-sdk-test
PKG_VERSION:=1
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/gh-action-sdk-test
  SECTION:=utils
  CATEGORY:=Utilities
  TITLE:=Testing gh-action-sdk
  DEPENDS:=
endef

define Package/gh-action-sdk-test/description
Testing gh-action-sdk
endef

define Build/Prepare
endef

define Build/Configure
endef

define Build/Compile
	echo `id -un`
	exit 1
endef

define Package/gh-action-sdk-test/install
	touch $(1)/foo
endef

$(eval $(call BuildPackage,gh-action-sdk-test))
