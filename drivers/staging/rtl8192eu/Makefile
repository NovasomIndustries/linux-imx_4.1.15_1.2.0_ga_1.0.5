HCI_NAME = usb
RTL871X = rtl8192e
MODULE_NAME = 8192eu

r8192eu-y :=	\
		core/rtw_cmd.o \
		core/rtw_security.o \
		core/rtw_debug.o \
		core/rtw_io.o \
		core/rtw_ioctl_set.o \
		core/rtw_ieee80211.o \
		core/rtw_mlme.o \
		core/rtw_mlme_ext.o \
		core/rtw_mi.o \
		core/rtw_wlan_util.o \
		core/rtw_vht.o \
		core/rtw_pwrctrl.o \
		core/rtw_rf.o \
		core/rtw_chplan.o \
		core/rtw_recv.o \
		core/rtw_sta_mgt.o \
		core/rtw_ap.o \
		core/mesh/rtw_mesh.o \
		core/mesh/rtw_mesh_pathtbl.o \
		core/mesh/rtw_mesh_hwmp.o \
		core/rtw_xmit.o	\
		core/rtw_p2p.o \
		core/rtw_rson.o \
		core/rtw_tdls.o \
		core/rtw_br_ext.o \
		core/rtw_iol.o \
		core/rtw_sreset.o \
		core/rtw_btcoex_wifionly.o \
		core/rtw_btcoex.o \
		core/rtw_beamforming.o \
		core/rtw_odm.o \
		core/rtw_rm.o \
		core/rtw_rm_fsm.o \
		core/rtw_mp.o \
		core/efuse/rtw_efuse.o \
		os_dep/osdep_service.o \
		os_dep/linux/os_intfs.o \
		os_dep/linux/$(HCI_NAME)_intf.o \
		os_dep/linux/$(HCI_NAME)_ops_linux.o \
		os_dep/linux/ioctl_linux.o \
		os_dep/linux/xmit_linux.o \
		os_dep/linux/mlme_linux.o \
		os_dep/linux/recv_linux.o \
		os_dep/linux/ioctl_cfg80211.o \
		os_dep/linux/rtw_cfgvendor.o \
		os_dep/linux/wifi_regd.o \
		os_dep/linux/rtw_android.o \
		os_dep/linux/rtw_proc.o \
		os_dep/linux/rtw_rhashtable.o \
		os_dep/linux/ioctl_mp.o \
		hal/hal_intf.o \
		hal/hal_com.o \
		hal/hal_com_phycfg.o \
		hal/hal_phy.o \
		hal/hal_dm.o \
		hal/hal_dm_acs.o \
		hal/hal_btcoex_wifionly.o \
		hal/hal_btcoex.o \
		hal/hal_mp.o \
		hal/hal_mcc.o \
		hal/hal_hci/hal_$(HCI_NAME).o \
		hal/led/hal_led.o \
		hal/led/hal_$(HCI_NAME)_led.o \
		hal/HalPwrSeqCmd.o \
		hal/$(RTL871X)/Hal8192EPwrSeq.o \
		hal/$(RTL871X)/$(RTL871X)_xmit.o \
		hal/$(RTL871X)/$(RTL871X)_sreset.o \
		hal/$(RTL871X)/$(RTL871X)_hal_init.o \
		hal/$(RTL871X)/$(RTL871X)_phycfg.o \
		hal/$(RTL871X)/$(RTL871X)_rf6052.o \
		hal/$(RTL871X)/$(RTL871X)_dm.o \
		hal/$(RTL871X)/$(RTL871X)_rxdesc.o \
		hal/$(RTL871X)/$(RTL871X)_cmd.o \
		hal/$(RTL871X)/hal8192e_fw.o \
		hal/$(RTL871X)/$(HCI_NAME)/$(HCI_NAME)_halinit.o \
		hal/$(RTL871X)/$(HCI_NAME)/rtl$(MODULE_NAME)_led.o \
		hal/$(RTL871X)/$(HCI_NAME)/rtl$(MODULE_NAME)_xmit.o \
		hal/$(RTL871X)/$(HCI_NAME)/rtl$(MODULE_NAME)_recv.o \
		hal/efuse/$(RTL871X)/HalEfuseMask8192E_USB.o \
		platform/platform_ops.o \
		hal/phydm/phydm_debug.o	\
		hal/phydm/phydm_antdiv.o\
		hal/phydm/phydm_soml.o\
		hal/phydm/phydm_smt_ant.o\
		hal/phydm/phydm_antdect.o\
		hal/phydm/phydm_interface.o\
		hal/phydm/phydm_phystatus.o\
		hal/phydm/phydm_hwconfig.o\
		hal/phydm/phydm.o\
		hal/phydm/phydm_dig.o\
		hal/phydm/phydm_pathdiv.o\
		hal/phydm/phydm_rainfo.o\
		hal/phydm/phydm_dynamictxpower.o\
		hal/phydm/phydm_adaptivity.o\
		hal/phydm/phydm_cfotracking.o\
		hal/phydm/phydm_noisemonitor.o\
		hal/phydm/phydm_beamforming.o\
		hal/phydm/phydm_dfs.o\
		hal/phydm/txbf/halcomtxbf.o\
		hal/phydm/txbf/haltxbfinterface.o\
		hal/phydm/txbf/phydm_hal_txbf_api.o\
		hal/phydm/phydm_adc_sampling.o\
		hal/phydm/phydm_ccx.o\
		hal/phydm/phydm_psd.o\
		hal/phydm/phydm_primary_cca.o\
		hal/phydm/phydm_cck_pd.o\
		hal/phydm/phydm_rssi_monitor.o\
		hal/phydm/phydm_auto_dbg.o\
		hal/phydm/phydm_math_lib.o\
		hal/phydm/phydm_api.o\
		hal/phydm/phydm_pow_train.o\
		hal/phydm/phydm_lna_sat.o\
		hal/phydm/phydm_pmac_tx_setting.o\
		hal/phydm/phydm_mp.o\
		hal/phydm/halrf/halrf.o\
		hal/phydm/halrf/halrf_debug.o\
		hal/phydm/halrf/halphyrf_ce.o\
		hal/phydm/halrf/halrf_powertracking_ce.o\
		hal/phydm/halrf/halrf_powertracking.o\
		hal/phydm/halrf/halrf_kfree.o\
		hal/phydm/$(RTL871X)/halhwimg8192e_mac.o\
		hal/phydm/$(RTL871X)/halhwimg8192e_bb.o\
		hal/phydm/$(RTL871X)/halhwimg8192e_rf.o\
		hal/phydm/halrf/$(RTL871X)/halrf_8192e_ce.o\
		hal/phydm/$(RTL871X)/phydm_regconfig8192e.o\
		hal/phydm/$(RTL871X)/phydm_rtl8192e.o \
		hal/btc/halbtc8192e1ant.o \
		hal/btc/halbtc8192e2ant.o \
		hal/$(RTL871X)/$(HCI_NAME)/$(HCI_NAME)_ops_linux.o

obj-$(CONFIG_R8192EU)	:= r8192eu.o

ccflags-y += \
	-DCONFIG_MP_INCLUDED \
	-DCONFIG_POWER_SAVING \
	-DCONFIG_BT_COEXIST \
	-DCONFIG_EFUSE_CONFIG_FILE \
	-DEFUSE_MAP_PATH=\"/system/etc/wifi/wifi_efuse_$(MODULE_NAME).map\" \
	-DWIFIMAC_PATH=\"/data/wifimac.txt\" \
	-DCONFIG_LOAD_PHY_PARA_FROM_FILE \
	-DREALTEK_CONFIG_PATH=\"/lib/firmware/\" \
	-DCONFIG_TXPWR_BY_RATE=1 \
	-DCONFIG_TXPWR_BY_RATE_EN=0 \
	-DCONFIG_TXPWR_LIMIT=1 \
	-DCONFIG_TXPWR_LIMIT_EN=0 \
	-DCONFIG_RTW_CHPLAN=0xFF \
	-DCONFIG_RTW_ADAPTIVITY_EN=0 \
	-DCONFIG_RTW_ADAPTIVITY_MODE=0 \
	-DCONFIG_IEEE80211W \
	-DHIGH_ACTIVE_HST2DEV=0 \
	-DCONFIG_BR_EXT \
	-DCONFIG_BR_EXT_BRNAME=\"br0\" \
	-DCONFIG_WIFI_MONITOR \
	-DCONFIG_RTW_NAPI \
	-DCONFIG_RTW_NETIF_SG \
	-DCONFIG_RTW_DEBUG \
	-DRTW_LOG_LEVEL=2 \
	-DCONFIG_RTL8192E \
	-DCONFIG_LITTLE_ENDIAN \
	-DCONFIG_IOCTL_CFG80211 \
	-DRTW_USE_CFG80211_STA_EVENT \
	-DDM_ODM_SUPPORT_TYPE=0x04 \
	-I$(src)/include \
	-I$(src)/platform \
	-I$(src)/hal/btc \
	-I$(src)/hal/phydm
