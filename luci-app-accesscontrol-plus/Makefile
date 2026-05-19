
# Copyright (C) 2016 Openwrt.org
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI Access Control Configuration
LUCI_DEPENDS:=+snmpd +iptables +iptables-nft +iptables-mod-ipopt +iptables-mod-nat-extra +IPV6:ip6tables +IPV6:ip6tables-nft +IPV6:ip6tables-mod-nat
LUCI_PKGARCH:=all

PKG_NAME:=luci-app-accesscontrol-plus
PKG_VERSION:=1
PKG_RELEASE:=12

include $(TOPDIR)/feeds/luci/luci.mk
# call BuildPackage - OpenWrt buildroot signature
