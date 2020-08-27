# Copyright (C) 2017 Ian Li <OpenSource@ianli.xyz>
#
# This is free software, licensed under the GNU General Public License v3.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-adguardhome
LUCI_TITLE:=LuCI support for adguardhome
PKG_DEPENDS:=+!wget&&!curl:wget
LUCI_PKGARCH:=all
PKG_VERSION:=1.8
PKG_RELEASE:=20200827
PKG_MAINTAINER:=<https://github.com/rufengsuixing/luci-app-adguardhome, https://github.com/Twinzo1/AdGuardHome>

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
