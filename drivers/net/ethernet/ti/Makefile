# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the TI network device drivers.
#

obj-$(CONFIG_TI_CPSW) += cpsw-common.o
obj-$(CONFIG_TI_DAVINCI_EMAC) += cpsw-common.o
obj-$(CONFIG_TI_CPSW_SWITCHDEV) += cpsw-common.o

obj-$(CONFIG_TI_CPSW_PROXY_CLIENT) += ti-cpsw-proxy-client.o
ti-cpsw-proxy-client-y := cpsw-proxy-client.o k3-cppi-desc-pool.o

obj-$(CONFIG_TLAN) += tlan.o
obj-$(CONFIG_CPMAC) += cpmac.o
obj-$(CONFIG_TI_DAVINCI_EMAC) += ti_davinci_emac.o
ti_davinci_emac-y := davinci_emac.o davinci_cpdma.o
obj-$(CONFIG_TI_DAVINCI_MDIO) += davinci_mdio.o
obj-$(CONFIG_TI_CPSW_PHY_SEL) += cpsw-phy-sel.o
obj-$(CONFIG_TI_CPTS) += cpts.o
obj-$(CONFIG_TI_CPSW) += ti_cpsw.o
ti_cpsw-y := cpsw.o davinci_cpdma.o cpsw_ale.o cpsw_priv.o cpsw_sl.o cpsw_ethtool.o
obj-$(CONFIG_TI_CPSW_SWITCHDEV) += ti_cpsw_new.o
ti_cpsw_new-y := cpsw_switchdev.o cpsw_new.o davinci_cpdma.o cpsw_ale.o cpsw_sl.o cpsw_priv.o cpsw_ethtool.o

obj-$(CONFIG_TI_KEYSTONE_NETCP) += keystone_netcp.o
keystone_netcp-y := netcp_core.o cpsw_ale.o
obj-$(CONFIG_TI_KEYSTONE_NETCP_ETHSS) += keystone_netcp_ethss.o
keystone_netcp_ethss-y := netcp_ethss.o netcp_sgmii.o netcp_xgbepcsr.o cpsw_ale.o

obj-$(CONFIG_TI_K3_AM65_CPSW_NUSS) += ti-am65-cpsw-nuss.o
ti-am65-cpsw-nuss-y := am65-cpsw-nuss.o cpsw_sl.o am65-cpsw-ethtool.o cpsw_ale.o k3-cppi-desc-pool.o am65-cpsw-qos.o am65-debugfs.o
ti-am65-cpsw-nuss-$(CONFIG_TI_K3_AM65_CPSW_SWITCHDEV) += am65-cpsw-switchdev.o
obj-$(CONFIG_TI_K3_AM65_CPTS) += am65-cpts.o

obj-$(CONFIG_TI_RDEV_ETH_SWITCH_VIRT_EMAC) += ti-j721e-cpsw-virt-mac.o
ti-j721e-cpsw-virt-mac-y := j721e-cpsw-virt-mac.o k3-cppi-desc-pool.o

obj-$(CONFIG_TI_ICSSG_PRUETH) += icssg-prueth.o
icssg-prueth-y := icssg_prueth.o icssg_classifier.o icssg_ethtool.o icssg_queues.o icssg_config.o k3-cppi-desc-pool.o icssg_mii_cfg.o icssg_switchdev.o icssg_qos.o
obj-$(CONFIG_TI_ICSS_IEP) += icss_iep.o
