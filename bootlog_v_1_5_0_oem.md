[   12.109684] random: ubusd: uninitialized urandom read (4 bytes read, 68 bits of entropy available)
[   12.118724] random: ubusd: uninitialized urandom read (4 bytes read, 68 bits of entropy available)
[   12.127648] random: ubusd: uninitialized urandom read (4 bytes read, 68 bits of entropy available)
[   12.136779] procd: - init -
[   12.311119] UBI: attaching mtd11 to ubi1
[   12.353260] UBI: scanning is finished
[   12.362208] UBI: attached mtd11 (name "factory_data", size 9 MiB) to ubi1
[   12.368017] UBI: PEB size: 131072 bytes (128 KiB), LEB size: 126976 bytes
[   12.374753] UBI: min./max. I/O unit sizes: 2048/2048, sub-page size 2048
[   12.381418] UBI: VID header offset: 2048 (aligned 2048), data offset: 4096
[   12.388291] UBI: good PEBs: 72, bad PEBs: 0, corrupted PEBs: 0
[   12.394106] UBI: user volume: 1, internal volumes: 1, max. volumes count: 128
[   12.401215] UBI: max/mean erase counter: 3/1, WL threshold: 4096, image sequence number: 774569133
[   12.410166] UBI: available PEBs: 0, total reserved PEBs: 72, PEBs reserved for bad PEB handling: 20
[   12.419216] UBI: background thread "ubi_bgt1d" started, PID 163
[   12.452846] UBIFS: background thread "ubifs_bgt1_0" started, PID 169
[   12.473862] UBIFS: recovery needed
[   12.553103] UBIFS: recovery completed
[   12.555855] UBIFS: mounted UBI device 1, volume 0, name "ubi_factory_data"
[   12.562599] UBIFS: LEB size: 126976 bytes (124 KiB), min./max. I/O unit sizes: 2048 bytes/2048 bytes
[   12.571737] UBIFS: FS size: 4825088 bytes (4 MiB, 38 LEBs), journal size 1015809 bytes (0 MiB, 6 LEBs)
[   12.581014] UBIFS: reserved for root: 227900 bytes (222 KiB)
[   12.586660] UBIFS: media format: w4/r0 (latest is w4/r0), UUID 500EFE10-6703-4CE1-AEE2-2FFBA508295F, small LPT model
[   12.612343] UBI: attaching mtd12 to ubi2
[   12.689228] UBI: scanning is finished
[   12.698873] UBI: attached mtd12 (name "runtime_data", size 17 MiB) to ubi2
[   12.704746] UBI: PEB size: 131072 bytes (128 KiB), LEB size: 126976 bytes
[   12.711487] UBI: min./max. I/O unit sizes: 2048/2048, sub-page size 2048
[   12.718193] UBI: VID header offset: 2048 (aligned 2048), data offset: 4096
[   12.725043] UBI: good PEBs: 136, bad PEBs: 0, corrupted PEBs: 0
[   12.730934] UBI: user volume: 1, internal volumes: 1, max. volumes count: 128
[   12.738068] UBI: max/mean erase counter: 11/5, WL threshold: 4096, image sequence number: 1676817941
[   12.747179] UBI: available PEBs: 0, total reserved PEBs: 136, PEBs reserved for bad PEB handling: 20
[   12.756324] UBI: background thread "ubi_bgt2d" started, PID 175
[   12.782850] UBIFS: background thread "ubifs_bgt2_0" started, PID 181
[   12.807616] UBIFS: recovery needed
[   12.900804] UBIFS: recovery completed
[   12.903562] UBIFS: mounted UBI device 2, volume 0, name "ubi_runtime_data"
[   12.910298] UBIFS: LEB size: 126976 bytes (124 KiB), min./max. I/O unit sizes: 2048 bytes/2048 bytes
[   12.919435] UBIFS: FS size: 12951552 bytes (12 MiB, 102 LEBs), journal size 1015809 bytes (0 MiB, 6 LEBs)
[   12.928974] UBIFS: reserved for root: 611733 bytes (597 KiB)
[   12.934620] UBIFS: media format: w4/r0 (latest is w4/r0), UUID FCACC49C-6716-4F94-940E-69F1EAE7CF10, small LPT model
[   14.089990] QCE50: __qce_init_clk: Unable to get CE core src clk, set to NULL
[   14.096255] qcrypto 8e20000.qcrypto: Qualcomm Crypto 5.3.1 device found @0x8e20000
[   14.103766] qcrypto 8e20000.qcrypto: CE device = 0x0
[   14.103766] , IO base, CE = 0xe1600000
[   14.103766] , Consumer (IN) PIPE 2,    Producer (OUT) PIPE 3
[   14.103766] IO base BAM = 0x  (null)
[   14.103766] BAM IRQ 239
[   14.103766] Engines Availability = 0x2010453
[   14.128261] sps:BAM 0x08e04000 is registered.
[   14.133365] sps:BAM 0x08e04000 (va:0xe1640000) enabled: ver:0x27, number of pipes:4
[   14.141158] QCE50: qce_sps_init:  Qualcomm MSM CE-BAM at 0x0000000008e04000 irq 239
[   14.148163] bus_scale_table is NULL
[   14.151469] qcrypto 8e20000.qcrypto: qcrypto-ecb-aes
[   14.156394] qcrypto 8e20000.qcrypto: qcrypto-cbc-aes
[   14.161307] qcrypto 8e20000.qcrypto: qcrypto-ctr-aes
[   14.166275] qcrypto 8e20000.qcrypto: qcrypto-ecb-des
[   14.171200] qcrypto 8e20000.qcrypto: qcrypto-cbc-des
[   14.176169] qcrypto 8e20000.qcrypto: qcrypto-ecb-3des
[   14.181189] qcrypto 8e20000.qcrypto: qcrypto-cbc-3des
[   14.186243] qcrypto 8e20000.qcrypto: qcrypto-xts-aes
[   14.191172] qcrypto 8e20000.qcrypto: qcrypto-sha1
[   14.195888] qcrypto 8e20000.qcrypto: qcrypto-sha256
[   14.200724] qcrypto 8e20000.qcrypto: qcrypto-aead-hmac-sha1-cbc-aes
[   14.207011] qcrypto 8e20000.qcrypto: qcrypto-aead-hmac-sha1-cbc-des
[   14.213239] qcrypto 8e20000.qcrypto: qcrypto-aead-hmac-sha1-cbc-3des
[   14.219555] qcrypto 8e20000.qcrypto: qcrypto-aead-hmac-sha256-cbc-aes
[   14.226002] qcrypto 8e20000.qcrypto: qcrypto-aead-hmac-sha256-cbc-des
[   14.232408] qcrypto 8e20000.qcrypto: qcrypto-aead-hmac-sha256-cbc-3des
[   14.238928] qcrypto 8e20000.qcrypto: qcrypto-hmac-sha1
[   14.244056] qcrypto 8e20000.qcrypto: qcrypto-hmac-sha256
[   14.249332] qcrypto 8e20000.qcrypto: qcrypto-aes-ccm
[   14.254295] qcrypto 8e20000.qcrypto: qcrypto-rfc4309-aes-ccm
[   14.259810] qcrypto: FIPS140-2 Known Answer Tests: Skipped
[   14.273680] nf_conntrack version 0.5.0 (7765 buckets, 31060 max)
[   14.283619] PPP generic driver version 2.4.2
[   14.441137] ess-switch DT exist!
[   14.443392] switchreg_base_addr: 0xc000000
[   14.447415] switchreg_size: 0x80000
[   14.450888] switch_access_mode: local bus
[   14.454902] wan bmp:0x20
[   14.457415] ess-psgmii DT exist!
[   14.460614] mac mode=0
[   14.462968] current mac mode = 0
[   14.466168] current dts led_source_num is 0
[   14.470346] mdio DT exist!
[   14.473044] ssdk_plat_init start
[   14.476386] enable ess clk
[   14.479254] test point ssdk_probe
[   14.592982] reset ok in probe!
[   14.595581] PHY ID is 0x4dd0b2
[   14.658264] qca probe malibu phy driver succeeded!
[   16.443083] Dakota Chip version 0x1401
[   16.447159] qca-ssdk module init succeeded!
[   16.457432] l2tp_core: L2TP core driver, V2.0
[   16.461649] l2tp_netlink: L2TP netlink interface
[   16.466790] sit: IPv6 over IPv4 tunneling driver
[   16.473818] tipc: Activated (version 2.0.0)
[   16.477407] NET: Registered protocol family 30
[   16.482018] tipc: Started in single node mode
[   16.487626] gre: GRE over IPv4 demultiplexor driver
[   16.492662] ip_gre: GRE over IPv4 tunneling driver
[   16.502363] bonding: Ethernet Channel Bonding Driver: v3.7.1 (April 27, 2011)
[   16.516626] QCA Hy-Fi multicast installation successfully
[   16.524126] ip6_tables: (C) 2000-2006 Netfilter Core Team
[   16.534486] EDMA using MAC@ - using
[   16.536786] a6:da:6a:d1:48:fa
[   16.541302] EDMA using MAC@ - using
[   16.543663] 6a:4e:e4:ea:ea:a1
[   16.640330] u32 classifier
[   16.642014]     Performance counters on
[   16.645939]     input device check on
[   16.649475]     Actions configured
[   16.654426] Mirror/redirect action on
[   16.693217] Ebtables v2.0 registered
[   16.697746] ip_tables: (C) 2000-2006 Netfilter Core Team
[   16.880116] Netfilter messages via NETLINK v0.30.
[   16.887536] NET: Registered protocol family 24
[   16.894440] PPTP driver version 0.8.5
[   16.949947] xt_time: kernel timezone is -0000
[   16.955535] usbcore: registered new interface driver cdc_ether
[   16.972836] l2tp_ppp: PPPoL2TP kernel driver, V2.0
[   16.986710] ctnetlink v0.93: registering with nfnetlink.
[   16.994779] nf_conntrack_rtsp v0.6.21 loading
[   17.002494] nf_nat_rtsp v0.6.21 loading
[   17.009204] usbcore: registered new interface driver rndis_host
[   18.873661] random: nonblocking pool is initialized
[   21.178794] IPv6: ADDRCONF(NETDEV_UP): eth0: link is not ready
[   21.257211] IPv6: ADDRCONF(NETDEV_UP): eth0: link is not ready
[   24.840742] Load statistics in Router Mode
[   24.844139] module inited
[   25.813812] IPv6: ADDRCONF(NETDEV_UP): br-wan: link is not ready
[   25.832062] device eth0 entered promiscuous mode
[   25.836812] IPv6: ADDRCONF(NETDEV_UP): br-lan: link is not ready
[   25.847801] device eth1 entered promiscuous mode
[   28.391733] mode:0
[   30.679711] mem_manager: module license 'unspecified' taints kernel.
[   30.685318] Disabling lock debugging due to kernel taint
[   30.691518] __mm_init_module 
[   30.736326] ath_dfs: Version 2.0.0
[   30.736326] Copyright (c) 2005-2006 Atheros Communications, Inc. All Rights Reserved
[   30.758561] ath_spectral: Version 2.0.0
[   30.758561] Copyright (c) 2005-2009 Atheros Communications, Inc. All Rights Reserved
[   31.306196] ath_hal: 0.9.17.1 (AR5416, AR9380, WRITE_EEPROM, 11D)
[   31.324928] ath_rate_atheros: Copyright (c) 2001-2005 Atheros Communications, Inc, All Rights Reserved
[   31.344338] ath_tx99: Version 2.0
[   31.344338] Copyright (c) 2010 Atheros Communications, Inc, All Rights Reserved
[   31.377700] ath_dev: Copyright (c) 2001-2007 Atheros Communications, Inc, All Rights Reserved
[   31.403398] ath_da_pci:  (Atheros/multi-bss)
[   31.593940]  *********** IPQ4019  *************Wifi0 CPU frequency 250000000
[   31.610066] hif_target_sync_ahb: Got FW signal, retries = 1hif_ahb_enable_bus: X - hif_type = 0xd, target_type = 0xbhif_config_ce: ce_init donehif_config_ce: X, ret = 0hif_set_hia: Ehif_pci_bus_configure: hif_set_hia donehif_configure_irq: Ehif_enable: X OKhif_napi_create: NAPI structures initializedhif_napi_create: NAPI id 6 created for pipe 5qca_napi_create: napi instance 32 created on pipe 4
[   31.647359] hif_napi_event: received evnt: CONF cmd; v = 1 (state=0x1)hif_napi_event: setting configuration to ON
[   31.647359] __ol_ath_attach() Allocated scn db5c04c0
[   31.661224] __ol_ath_attach: dev name wifi0
[   31.665392] ol_ath_attach interface_id 0
[   31.669473] ol_target_init() BMI inited.
[   31.673335] ol_target_init() BMI Get Target Info.
[   31.677865] Chip id: 0xb, chip version: 0x1000000
[   31.682539] 
[   31.682539]  CE WAR Disabled
[   31.687239] NUM_DEV=1 FWMODE=0x2 FWSUBMODE=0x0 FWBR_BUF 0
[   31.692597] ol_target_init() configure Target .
[   31.697016] 
[   31.697016]  Target Version is 1000000
[   31.701989] 
[   31.701989]  Flash Download Address  c0000 
[   31.707691] ol_transfer_bin_file: flash data file defined
[   31.713065] ol_transfer_bin_file[3686] Get Caldata for wifi0.
[   31.718791] qdf_fs_read[59], Open File /tmp/wifi0.caldata SUCCESS!!file system magic:16914836super blocksize:4096inode 4453file size:12064qc98xx_verify_checksum: flash checksum passed: 0xeadd
[   31.735818] ol_transfer_bin_file 3747: Download Flash data len 12064
[   31.742551] Board extended Data download address: 0x0
[   31.766855] 
[   31.766855]  Board data initialized
[   31.770978] ol_ath_download_firmware: Download OTP, flash download ADDRESS 0xc0000
[   31.778431] 
[   31.778431]  Selecting  OTP binary for CHIP Version -541105212
[   31.808078] ath10k_ahb a000000.wifi: Firmware loaded from user helper succesfully
[   31.814638] ol_transfer_bin_file 3567: downloading file 0, Download data len 4680
[   31.838714] 
[   31.838714]  First OTP send param 8000
[   31.847824] ol_ath_download_firmware :First OTP download and Execute is good address:0x5000 return param 4660
[   31.856947] ol_ath_download_firmware:##Board Id 20 , CHIP Id 0
[   31.862749] ol_ath_download_firmware: BOARDDATA DOWNLOAD TO address 0xc0000
[   31.869822] qdf_fs_read[59], Open File /tmp/country SUCCESS!!file system magic:16914836super blocksize:4096inode 5590file size:3qdf_fs_read[79]: caldata data size mismatch, fsize=3, cal_size=2!!!!!!!!!!!!!board_type:11, country code is US, boardid: 20 !!!!!!!!!!!!!!!
[   31.893330] 
[   31.893330]  wifi0: Selecting board data file name boardData_1_0_IPQ4019_DK04_2G_US.bin
[   31.902694] ol_transfer_bin_file: Board Data File download to address=0xc0000 file name=IPQ4019/hw.1/boardData_1_0_IPQ4019_DK04_2G_US.bin
[   31.920564] ath10k_ahb a000000.wifi: Firmware loaded from user helper succesfully
[   31.927272] ol_transfer_bin_file 3567: downloading file 3, Download data len 12064
[   31.935291] Board extended Data download address: 0x0
[   31.965253] ol_ath_download_firmware: Using 0x1234 for the remainder of init
[   31.971282] 
[   31.971282]  Selecting  OTP binary for CHIP Version -541105212
[   31.978993] ath10k_ahb a000000.wifi: Firmware loaded from user helper succesfully
[   31.986256] ol_transfer_bin_file 3567: downloading file 0, Download data len 4680
[   32.010276] 
[   32.010276]  [Flash] : Ignore Module param
[   32.015626] 
[   32.015626]  Second otp download Param 10000 
[   32.031034] ol_ath_download_firmware : Second OTP download and Execute is good, param=0x0 
[   32.040173] 
[   32.040173]  Mission mode: Firmware CHIP Version -541105212
[   32.124212] ath10k_ahb a000000.wifi: Firmware loaded from user helper succesfully
[   32.132000] ol_swap_seg_alloc: Successfully allocated memory for SWAP size=262144 
[   32.139543] ath10k_ahb a000000.wifi: Firmware loaded from user helper succesfully
[   32.147712] Swap: bytes_left to copy: fw:16; dma_page:101001
[   32.152426] Swap: wrong length read:0
[   32.156315] ol_swap_wlan_memory_expansion: Swap total_bytes copied: 161143 Target address 4179a0 
[   32.165424] scn=db5c04c0  target_write_addr=4179a0 seg_info=deba7410 
[   32.171340] ol_transfer_swap_struct:Code swap structure successfully downloaded for bin type =2 
[   32.180494] bin_filename=IPQ4019/hw.1/athwlan.bin swap_filename=/lib/firmware/IPQ4019/hw.1/athwlan.codeswap.bin 
[   32.190498] ol_transfer_bin_file: Downloading firmware file: IPQ4019/hw.1/athwlan.bin
[   32.526022] ath10k_ahb a000000.wifi: Firmware loaded from user helper succesfully
[   32.532508] ol_transfer_bin_file 3567: downloading file 1, Download data len 368572
[   33.778281] ol_target_init() Download FW done. 
[   33.781996] ol_ath_attach() WMI attached. wmi_handle df5ea000 
[   33.792068] wmi_unified_register_event_handler: Event id 62 is unavailable
[   33.798076] +htc_create ..  HIF :dc1e0000-htc_create: (0xdc08a800)
[   33.804015] htc_wmi_init() HT Create . dc08a800
[   33.808902] htc_wmi_init 7585 host_enable 0 nss_nwifi_offload 0
[   33.814814] ol_ath_set_default_tgt_config : AC Minfree buffer allocation through module param (umac.ko)
[   33.824118]  OL_ACBKMinfree : 0
[   33.827111]  OL_ACBEMinfree : 0
[   33.830238]  OL_ACVIMinfree : 0
[   33.833586]  OL_ACVOMinfree : 0
[   33.836488] hif_enable_fastpath, Enabling fastpath mode
[   33.841516] +HWT
[   33.843732] hif_completion_thread_startup: pipe_num:0 pipe_info:0xdc1e4578hif_completion_thread_startup: pipe_num:3 pipe_info:0xdc1e4650hif_completion_thread_startup: pipe_num:4 pipe_info:0xdc1e4698
[   33.866229] -HWT
[   33.867269] Startup Mode-0 set
[   33.870250] 
[   33.870250] <=== cfg max peer id 1056 ====>
[   33.876986] htt_peer_map_timer_init Enter pdev db310000 hrtimer db314888
[   33.882679] 
[   33.882679]  htt_alloc_peer_map_mem : Alloc Success : host q vaddr db65a000 paddr 9b65a000
[   33.892537] 
[   33.892537]  htt_alloc_peer_map_mem : Flush Interval Configured to 256 pkts
[   33.904130] ol_txrx_pdev_attach: 2500 tx desc's allocated ; range starts from daf80000
[   33.913398] Firmware_Build_Number:74 
[   33.916075] FW wireless modes: 0x680c
[   33.919695] num_rf_chain:0x00000002  ht_cap_info:0x0000085b  vht_cap_info:0x339959b2  vht_supp_mcs:0x0000fffa
[   33.936130] btcoex_support 1, wlan_prio_gpio 52, coex_gpio_pin 0 0 0
[   33.942410] wmi_service_coex_gpio 1, wmi_service_4_wire_coex_support 1, coex_version 2
[   33.950412] 
[   33.950412] Sending Ext resource cfg: HOST PLATFORM as 0
[   33.950412] fw_feature_bitmap as 52 to TGT
[   33.961408] ol_ath_service_ready_event: tt_support: 1
[   33.966245] ol_ath_service_ready_event: periodic_chan_stats: 1
[   33.971998] ol_ath_service_ready_event: sw_cal_support_check_flag: 1
[   33.978424] Peer Caching Enabled ; num_peers = 530, num_active_peers = 52 num_tids = 104, num_vdevs = 17
[   33.988028] idx 1 req 2  num_units 1 num_unit_info 12 unit size 256 actual units 53 
[   33.995580] ol_ath_alloc_host_mem_chunk req_id 2 idx 0 num_units 53 unit_len 256,
[   34.003001] idx 2 req 3  num_units 1 num_unit_info 12 unit size 1024 actual units 53 
[   34.010916] ol_ath_alloc_host_mem_chunk req_id 3 idx 1 num_units 53 unit_len 1024,
[   34.018414] idx 3 req 4  num_units 1 num_unit_info 12 unit size 4096 actual units 53 
[   34.026433] ol_ath_alloc_host_mem_chunk req_id 4 idx 2 num_units 53 unit_len 4096,
[   34.033781] idx 0 req 1  num_units 0 num_unit_info 2 unit size 744 actual units 531 
[   34.041831] ol_ath_alloc_host_mem_chunk req_id 1 idx 3 num_units 531 unit_len 744,
[   34.049046] idx 4 req 6  num_units 35 num_unit_info 0 unit size 3072 actual units 35 
[   34.056946] ol_ath_alloc_host_mem_chunk req_id 6 idx 4 num_units 35 unit_len 3072,
[   34.064439] idx 5 req 7  num_units 1 num_unit_info 0 unit size 6144 actual units 1 
[   34.072030] ol_ath_alloc_host_mem_chunk req_id 7 idx 5 num_units 1 unit_len 6144,
[   34.079488] idx 6 req 5  num_units 0 num_unit_info 2 unit size 2052 actual units 531 
[   34.088239] ol_ath_alloc_host_mem_chunk req_id 5 idx 6 num_units 531 unit_len 2052,
[   34.094965] Support not added yet for Service 91
[   34.099563] Support not added yet for Service 92
[   34.104154] No EXT_MSG send INIT now
[   34.107725] chunk 0 len 13568 requested , ptr  0x9b43c000
[   34.113078] chunk 1 len 54272 requested , ptr  0x9af70000
[   34.118482] chunk 2 len 217088 requested , ptr  0x9a800000
[   34.123942] chunk 3 len 395064 requested , ptr  0x9a880000
[   34.129420] chunk 4 len 107520 requested , ptr  0x9afe0000
[   34.134882] chunk 5 len 6144 requested , ptr  0x9b402000
[   34.140178] chunk 6 len 1089612 requested , ptr  0x9aa00000
[   34.145937] ol_ath_service_ready_event[4310] WAPI MBSSID 2 
[   34.187849] Version = 16777216 3  status = 0
[   34.191304] ol_ath_connect_htc() WMI is ready
[   34.195671] target uses HTT version 2.2; host uses 2.2
[   34.200603] htt_h2t_frag_desc_bank_cfg_msg - HTT_H2T_MSG_TYPE_FRAG_DESC_BANK_CFG sent to FW for radio ID = 0
[   34.215746] ol_ath_attach() connect HTC. 
[   34.221639] bypasswmi : 0
[   34.226074] ol_regdmn_start: reg-domain param: regdmn=0, countryName=, wModeSelect=FFFFFFFF, netBand=FFFFFFFF, extendedChanMode=0.
[   34.237045] ol_regdmn_init_channels: !avail mode 0x680c (0x2) flags 0x2150
[   34.244469] ol_regdmn_init_channels: !avail mode 0x680c (0x1) flags 0x140
[   34.250461] ol_regdmn_init_channels: !avail mode 0x680c (0x20) flags 0xd0
[   34.257414] ol_regdmn_init_channels: !avail mode 0x680c (0x40) flags 0x150
[   34.264325] ol_regdmn_init_channels: !avail mode 0x680c (0x1000) flags 0x10100
[   34.271262] ol_regdmn_init_channels: !avail mode 0x680c (0x8000) flags 0x20100
[   34.278685] ol_regdmn_init_channels: !avail mode 0x680c (0x10000) flags 0x40100
[   34.285942] ol_regdmn_init_channels: !avail mode 0x680c (0x20000) flags 0x100100
[   34.293277] ol_regdmn_init_channels: !avail mode 0x680c (0x40000) flags 0x200100
[   34.300517] ol_regdmn_init_channels: !avail mode 0x680c (0x80000) flags 0x400100
[   34.308123] ol_regdmn_init_channels: !avail mode 0x680c (0x100000) flags 0x800100
[   34.315556] ol_regdmn_init_channels: !avail mode 0x680c (0x200000) flags 0x4000100
[   34.323074] ol_regdmn_init_channels: !avail mode 0x680c (0x400000) flags 0x8000100
[   34.331261] ol_ath_phyerr_attach: called
[   34.331509] OL Resmgr Init-ed
[   34.333852] ieee80211_bsteering_attach: Band steering initialized
[   34.339562] acfg_attach: 2884: Netlink socket created:dd3b9c00
[   34.345440] ol_if_spectral_setup
[   34.345506] SPECTRAL : get_capability not registered
[   34.350295] HAL_CAP_PHYDIAG : Capable
[   34.354026] SPECTRAL : Need to fix the capablity check for RADAR (spectral_attach : 237)
[   34.362015] SPECTRAL : get_capability not registered
[   34.367091] HAL_CAP_RADAR   : Capable
[   34.370674] SPECTRAL : Need to fix the capablity check for SPECTRAL
[   34.370674]  (spectral_attach : 242)
[   34.380571] SPECTRAL : get_capability not registered
[   34.385461] HAL_CAP_SPECTRAL_SCAN : Capable
[   34.389539] SPECTRAL : get_tsf64 not registered
[   34.394218] spectral_init_netlink 78 NULL SKB
[   34.398511] Green-AP : Green-AP : Attached
[   34.398511] 
[   34.404009] Green-AP : Attached
[   34.407064] rate power table override is only supported for AR98XX
[   34.413847] ol_ath_smart_ant_attach: Hardware doest not support Smart Antenna.
[   34.420700] ol_if_dfs_setup: called 
[   34.420766] ol_if_dfs_attach: called; ptr=dab9198c, radar_info=dc1afc40
[   34.427679] dfs_attach: event log enabled by default
[   34.432966] ol_ath_rtt_meas_report_attach: called
[   34.432995] ol_ath_lowi_wmi_event_attach: called
[   34.433018] >>>> CB Set   (null)
[   34.435646] of_get_named_gpiod_flags: can't parse gpios property of node '/soc/wifi@a000000[0]'
[   34.435670] ipq4019_wifi_led_init: Wifi LED init failed.. Couldn't get led gpio/led source
[   34.443611] ol_ath_attach() UMAC attach . 
[   34.447634] 
[   34.447634]  BURSTING enabled by default
[   34.453248] ol_ath_attach: Set global_ic[1] ..ptr:bf6cad28
[   34.458519] ath_lowi_if_netlink_init LOWI Netlink successfully created
[   34.465130] osif_wrap_attach:441 osif wrap attached
[   34.469901] osif_wrap_devt_init:402 osif wrap dev table init done
[   34.476001]  Wrap Attached: Wrap_com =dea58c00 ic->ic_wrap_com=dea58c00 &wrap_com->wc_devt=dea58c00 
[   34.485112] __ol_ath_attach: needed_headroom reservation 60
[   34.492509] ol_ath_thermal_mitigation_attach: --
[   34.496198] ol_ath_ahb_probe num_radios=0, wifi_radios[0].sc = db5c04c0 wifi_radio_type = 2
[   34.504538] ath_sysfs_diag_init: diag_fsattr 
[   34.509003]  *********** IPQ4019  *************Wifi1 CPU frequency 250000000
[   34.526561] hif_target_sync_ahb: Got FW signal, retries = 1hif_ahb_enable_bus: X - hif_type = 0xd, target_type = 0xbhif_config_ce: ce_init donehif_config_ce: X, ret = 0hif_set_hia: Ehif_pci_bus_configure: hif_set_hia donehif_configure_irq: Ehif_enable: X OKhif_napi_create: NAPI structures initializedhif_napi_create: NAPI id 6 created for pipe 5qca_napi_create: napi instance 32 created on pipe 4
[   34.577370] hif_napi_event: received evnt: CONF cmd; v = 1 (state=0x1)hif_napi_event: setting configuration to ON
[   34.577370] __ol_ath_attach() Allocated scn da8404c0
[   34.591209] __ol_ath_attach: dev name wifi1
[   34.595430] ol_ath_attach interface_id 1
[   34.599768] ol_target_init() BMI inited.
[   34.604740] ol_target_init() BMI Get Target Info.
[   34.608430] Chip id: 0xb, chip version: 0x1000000
[   34.613157] 
[   34.613157]  CE WAR Disabled
[   34.617871] NUM_DEV=1 FWMODE=0x2 FWSUBMODE=0x0 FWBR_BUF 0
[   34.633185] ol_target_init() configure Target .
[   34.636885] 
[   34.636885]  Target Version is 1000000
[   34.641923] 
[   34.641923]  Flash Download Address  c0000 
[   34.647672] ol_transfer_bin_file: flash data file defined
[   34.652977] ol_transfer_bin_file[3686] Get Caldata for wifi1.
[   34.658718] qdf_fs_read[59], Open File /tmp/wifi1.caldata SUCCESS!!file system magic:16914836super blocksize:4096inode 1052file size:12064qc98xx_verify_checksum: flash checksum passed: 0x1e38
[   34.675741] ol_transfer_bin_file 3747: Download Flash data len 12064
[   34.682472] Board extended Data download address: 0x0
[   34.706666] 
[   34.706666]  Board data initialized
[   34.710822] ol_ath_download_firmware: Download OTP, flash download ADDRESS 0xc0000
[   34.718302] 
[   34.718302]  Selecting  OTP binary for CHIP Version -541104644
[   34.725656] ath10k_ahb a800000.wifi: Firmware loaded from user helper succesfully
[   34.733002] ol_transfer_bin_file 3567: downloading file 0, Download data len 4680
[   34.757202] 
[   34.757202]  First OTP send param 8000
[   34.766139] ol_ath_download_firmware :First OTP download and Execute is good address:0x5400 return param 4660
[   34.775272] ol_ath_download_firmware:##Board Id 21 , CHIP Id 0
[   34.781065] ol_ath_download_firmware: BOARDDATA DOWNLOAD TO address 0xc0000
[   34.788050] qdf_fs_read[59], Open File /tmp/country SUCCESS!!file system magic:16914836super blocksize:4096inode 5590file size:3qdf_fs_read[79]: caldata data size mismatch, fsize=3, cal_size=2!!!!!!!!!!!!!board_type:11, country code is US, boardid: 21 !!!!!!!!!!!!!!!
[   34.811423] 
[   34.811423]  wifi1: Selecting board data file name boardData_1_0_IPQ4019_DK04_5G_US.bin
[   34.821313] [wifi0] FWLOG: [41611] WAL_DBGID_TX_AC_BUFFER_SET ( 
[   34.822936] ol_transfer_bin_file: Board Data File download to address=0xc0000 file name=IPQ4019/hw.1/boardData_1_0_IPQ4019_DK04_5G_US.bin
[   34.837645] ath10k_ahb a800000.wifi: Firmware loaded from user helper succesfully
[   34.837666] ol_transfer_bin_file 3567: downloading file 3, Download data len 12064
[   34.854358] Board extended Data download address: 0x0
[   34.858201] 0x3, 0xdeb002, 0x94c, 0x94c, 0x0 )
[   34.858227] [wifi0] FWLOG: [41611] WAL_DBGID_TX_AC_BUFFER_SET ( 0x12, 0x1e, 0x94c, 0x94c, 0x0 )
[   34.858246] [wifi0] FWLOG: [41611] WAL_DBGID_TX_AC_BUFFER_SET ( 0x45, 0x1e, 0x94c, 0x94c, 0x0 )
[   34.858264] [wifi0] FWLOG: [41611] WAL_DBGID_TX_AC_BUFFER_SET ( 0x67, 0x1e, 0x94c, 0x94c, 0x0 )
[   34.858284] [wifi0] FWLOG: [41761] UNKNOWN 22:55 ( 0x3a, 0xa10, 0x160, 0x0, 0x12 )
[   34.919939] ol_ath_download_firmware: Using 0x1234 for the remainder of init
[   34.926159] 
[   34.926159]  Selecting  OTP binary for CHIP Version -541104644
[   34.933647] ath10k_ahb a800000.wifi: Firmware loaded from user helper succesfully
[   34.940757] ol_transfer_bin_file 3567: downloading file 0, Download data len 4680
[   34.965100] 
[   34.965100]  [Flash] : Ignore Module param
[   34.969665] 
[   34.969665]  Second otp download Param 10000 
[   34.987095] ol_ath_download_firmware : Second OTP download and Execute is good, param=0x0 
[   34.994532] 
[   34.994532]  Mission mode: Firmware CHIP Version -541104644
[   35.001899] ath10k_ahb a800000.wifi: Firmware loaded from user helper succesfully
[   35.009361] ol_swap_seg_alloc: Successfully allocated memory for SWAP size=262144 
[   35.022517] ath10k_ahb a800000.wifi: Firmware loaded from user helper succesfully
[   35.030423] Swap: bytes_left to copy: fw:16; dma_page:101001
[   35.035148] Swap: wrong length read:0
[   35.038715] ol_swap_wlan_memory_expansion: Swap total_bytes copied: 161143 Target address 4179a0 
[   35.047938] scn=da8404c0  target_write_addr=4179a0 seg_info=dea84a10 
[   35.054062] ol_transfer_swap_struct:Code swap structure successfully downloaded for bin type =2 
[   35.062760] bin_filename=IPQ4019/hw.1/athwlan.bin swap_filename=/lib/firmware/IPQ4019/hw.1/athwlan.codeswap.bin 
[   35.078304] ol_transfer_bin_file: Downloading firmware file: IPQ4019/hw.1/athwlan.bin
[   35.086280] ath10k_ahb a800000.wifi: Firmware loaded from user helper succesfully
[   35.092842] ol_transfer_bin_file 3567: downloading file 1, Download data len 368572
[   36.332098] ol_target_init() Download FW done. 
[   36.336051] ol_ath_attach() WMI attached. wmi_handle db65e000 
[   36.341434] wmi_unified_register_event_handler: Event id 62 is unavailable
[   36.348579] +htc_create ..  HIF :dab40000-htc_create: (0xdc09b800)
[   36.354317] htc_wmi_init() HT Create . dc09b800
[   36.359227] htc_wmi_init 7585 host_enable 0 nss_nwifi_offload 0
[   36.365155] ol_ath_set_default_tgt_config : AC Minfree buffer allocation through module param (umac.ko)
[   36.374464]  OL_ACBKMinfree : 0
[   36.377473]  OL_ACBEMinfree : 0
[   36.380505]  OL_ACVIMinfree : 0
[   36.383863]  OL_ACVOMinfree : 0
[   36.386760] hif_enable_fastpath, Enabling fastpath mode
[   36.391787] +HWT
[   36.393967] hif_completion_thread_startup: pipe_num:0 pipe_info:0xdab44578hif_completion_thread_startup: pipe_num:3 pipe_info:0xdab44650hif_completion_thread_startup: pipe_num:4 pipe_info:0xdab44698
[   36.417680] -HWT
[   36.418730] Startup Mode-0 set
[   36.421714] 
[   36.421714] <=== cfg max peer id 1056 ====>
[   36.428455] htt_peer_map_timer_init Enter pdev da0a8000 hrtimer da0ac888
[   36.434391] 
[   36.434391]  htt_alloc_peer_map_mem : Alloc Success : host q vaddr da0f0000 paddr 9a0f0000
[   36.444054] 
[   36.444054]  htt_alloc_peer_map_mem : Flush Interval Configured to 256 pkts
[   36.455905] ol_txrx_pdev_attach: 2500 tx desc's allocated ; range starts from d9d20000
[   36.465252] Firmware_Build_Number:74 
[   36.467918] FW wireless modes: 0x1f9001
[   36.471896] num_rf_chain:0x00000002  ht_cap_info:0x0000085b  vht_cap_info:0x339959b2  vht_supp_mcs:0x0000fffa
[   36.494765] wmi_service_coex_gpio 0, wmi_service_4_wire_coex_support 0, coex_version 0
[   36.502504] 
[   36.502504] Sending Ext resource cfg: HOST PLATFORM as 0
[   36.502504] fw_feature_bitmap as 50 to TGT
[   36.513837] ol_ath_service_ready_event: tt_support: 1
[   36.518533] ol_ath_service_ready_event: periodic_chan_stats: 1
[   36.524451] ol_ath_service_ready_event: sw_cal_support_check_flag: 1
[   36.530549] Peer Caching Enabled ; num_peers = 530, num_active_peers = 52 num_tids = 104, num_vdevs = 17
[   36.540318] idx 1 req 2  num_units 1 num_unit_info 12 unit size 256 actual units 53 
[   36.547957] ol_ath_alloc_host_mem_chunk req_id 2 idx 0 num_units 53 unit_len 256,
[   36.555377] idx 2 req 3  num_units 1 num_unit_info 12 unit size 1024 actual units 53 
[   36.563131] ol_ath_alloc_host_mem_chunk req_id 3 idx 1 num_units 53 unit_len 1024,
[   36.570562] idx 3 req 4  num_units 1 num_unit_info 12 unit size 4096 actual units 53 
[   36.578629] ol_ath_alloc_host_mem_chunk req_id 4 idx 2 num_units 53 unit_len 4096,
[   36.585964] idx 0 req 1  num_units 0 num_unit_info 2 unit size 744 actual units 531 
[   36.594022] ol_ath_alloc_host_mem_chunk req_id 1 idx 3 num_units 531 unit_len 744,
[   36.601204] idx 4 req 6  num_units 35 num_unit_info 0 unit size 3072 actual units 35 
[   36.609191] ol_ath_alloc_host_mem_chunk req_id 6 idx 4 num_units 35 unit_len 3072,
[   36.616607] idx 5 req 7  num_units 1 num_unit_info 0 unit size 6144 actual units 1 
[   36.624269] ol_ath_alloc_host_mem_chunk req_id 7 idx 5 num_units 1 unit_len 6144,
[   36.631723] idx 6 req 5  num_units 0 num_unit_info 2 unit size 2052 actual units 531 
[   36.640579] ol_ath_alloc_host_mem_chunk req_id 5 idx 6 num_units 531 unit_len 2052,
[   36.647284] Support not added yet for Service 91
[   36.651837] Support not added yet for Service 92
[   36.656470] No EXT_MSG send INIT now
[   36.660003] chunk 0 len 13568 requested , ptr  0x9a994000
[   36.665386] chunk 1 len 54272 requested , ptr  0x99d80000
[   36.670760] chunk 2 len 217088 requested , ptr  0x99dc0000
[   36.676272] chunk 3 len 395064 requested , ptr  0x99e00000
[   36.681703] chunk 4 len 107520 requested , ptr  0x99da0000
[   36.687207] chunk 5 len 6144 requested , ptr  0x9c1d2000
[   36.692466] chunk 6 len 1089612 requested , ptr  0x99800000
[   36.698250] ol_ath_service_ready_event[4310] WAPI MBSSID 2 
[   36.741849] Version = 16777216 3  status = 0
[   36.745176] ol_ath_connect_htc() WMI is ready
[   36.749522] target uses HTT version 2.2; host uses 2.2
[   36.754602] htt_h2t_frag_desc_bank_cfg_msg - HTT_H2T_MSG_TYPE_FRAG_DESC_BANK_CFG sent to FW for radio ID = 1
[   36.769915] ol_ath_attach() connect HTC. 
[   36.772952] bypasswmi : 0
[   36.775540] ol_ath_attach: low_5ghz: 5150  high_5gh: 5250 
[   36.781012] ol_regdmn_start: reg-domain param: regdmn=0, countryName=, wModeSelect=FFFFFFFF, netBand=FFFFFFFF, extendedChanMode=0.
[   36.792803] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x2) flags 0x2150
[   36.799775] ol_regdmn_init_channels: c 5260 out of range [5150..5250]
[   36.799797] ol_regdmn_init_channels: c 5280 out of range [5150..5250]
[   36.799808] ol_regdmn_init_channels: c 5300 out of range [5150..5250]
[   36.799818] ol_regdmn_init_channels: c 5320 out of range [5150..5250]
[   36.799832] ol_regdmn_init_channels: c 5500 out of range [5150..5250]
[   36.799842] ol_regdmn_init_channels: c 5520 out of range [5150..5250]
[   36.799854] ol_regdmn_init_channels: c 5540 out of range [5150..5250]
[   36.799864] ol_regdmn_init_channels: c 5560 out of range [5150..5250]
[   36.799874] ol_regdmn_init_channels: c 5580 out of range [5150..5250]
[   36.799884] ol_regdmn_init_channels: c 5600 out of range [5150..5250]
[   36.799896] ol_regdmn_init_channels: c 5620 out of range [5150..5250]
[   36.799907] ol_regdmn_init_channels: c 5640 out of range [5150..5250]
[   36.799927] ol_regdmn_init_channels: c 5660 out of range [5150..5250]
[   36.799946] ol_regdmn_init_channels: c 5680 out of range [5150..5250]
[   36.799961] ol_regdmn_init_channels: c 5700 out of range [5150..5250]
[   36.799981] ol_regdmn_init_channels: c 5720 out of range [5150..5250]
[   36.799995] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   36.800006] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   36.800021] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   36.800036] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   36.800052] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   36.800072] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x4) flags 0xa0
[   36.806783] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x8) flags 0xc0
[   36.813506] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x20) flags 0xd0
[   36.820418] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x40) flags 0x150
[   36.827502] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x800) flags 0x10080
[   36.834791] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x2000) flags 0x20080
[   36.842119] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x4000) flags 0x40080
[   36.849569] ol_regdmn_init_channels: c 5260 out of range [5150..5250]
[   36.849589] ol_regdmn_init_channels: c 5280 out of range [5150..5250]
[   36.849600] ol_regdmn_init_channels: c 5300 out of range [5150..5250]
[   36.849610] ol_regdmn_init_channels: c 5320 out of range [5150..5250]
[   36.849622] ol_regdmn_init_channels: c 5500 out of range [5150..5250]
[   36.849633] ol_regdmn_init_channels: c 5520 out of range [5150..5250]
[   36.849643] ol_regdmn_init_channels: c 5540 out of range [5150..5250]
[   36.849653] ol_regdmn_init_channels: c 5560 out of range [5150..5250]
[   36.849663] ol_regdmn_init_channels: c 5580 out of range [5150..5250]
[   36.849673] ol_regdmn_init_channels: c 5600 out of range [5150..5250]
[   36.849683] ol_regdmn_init_channels: c 5620 out of range [5150..5250]
[   36.849718] ol_regdmn_init_channels: c 5640 out of range [5150..5250]
[   36.849775] ol_regdmn_init_channels: c 5660 out of range [5150..5250]
[   36.849815] ol_regdmn_init_channels: c 5680 out of range [5150..5250]
[   36.849837] ol_regdmn_init_channels: c 5700 out of range [5150..5250]
[   36.849853] ol_regdmn_init_channels: c 5720 out of range [5150..5250]
[   36.849872] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   36.849889] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   36.849905] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   36.849921] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   36.849940] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   36.849976] ol_regdmn_init_channels: c 5260 out of range [5150..5250]
[   36.849994] ol_regdmn_init_channels: c 5300 out of range [5150..5250]
[   36.850007] ol_regdmn_init_channels: c 5500 out of range [5150..5250]
[   36.850023] ol_regdmn_init_channels: c 5540 out of range [5150..5250]
[   36.850034] ol_regdmn_init_channels: c 5580 out of range [5150..5250]
[   36.850044] ol_regdmn_init_channels: c 5620 out of range [5150..5250]
[   36.850054] ol_regdmn_init_channels: c 5660 out of range [5150..5250]
[   36.850068] ol_regdmn_init_channels: c 5700 out of range [5150..5250]
[   36.850083] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   36.850093] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   36.850118] ol_regdmn_init_channels: c 5280 out of range [5150..5250]
[   36.850136] ol_regdmn_init_channels: c 5320 out of range [5150..5250]
[   36.850152] ol_regdmn_init_channels: c 5520 out of range [5150..5250]
[   36.850164] ol_regdmn_init_channels: c 5560 out of range [5150..5250]
[   36.850174] ol_regdmn_init_channels: c 5600 out of range [5150..5250]
[   36.850184] ol_regdmn_init_channels: c 5640 out of range [5150..5250]
[   36.850194] ol_regdmn_init_channels: c 5680 out of range [5150..5250]
[   36.850204] ol_regdmn_init_channels: c 5720 out of range [5150..5250]
[   36.850216] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   36.850226] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   36.850252] ol_regdmn_init_channels: c 5260 out of range [5150..5250]
[   36.850263] ol_regdmn_init_channels: c 5280 out of range [5150..5250]
[   36.850274] ol_regdmn_init_channels: c 5300 out of range [5150..5250]
[   36.850284] ol_regdmn_init_channels: c 5320 out of range [5150..5250]
[   36.850303] ol_regdmn_init_channels: c 5500 out of range [5150..5250]
[   36.850332] ol_regdmn_init_channels: c 5520 out of range [5150..5250]
[   36.850361] ol_regdmn_init_channels: c 5540 out of range [5150..5250]
[   36.850412] ol_regdmn_init_channels: c 5560 out of range [5150..5250]
[   36.850461] ol_regdmn_init_channels: c 5580 out of range [5150..5250]
[   36.850496] ol_regdmn_init_channels: c 5600 out of range [5150..5250]
[   36.850525] ol_regdmn_init_channels: c 5620 out of range [5150..5250]
[   36.850554] ol_regdmn_init_channels: c 5640 out of range [5150..5250]
[   36.850582] ol_regdmn_init_channels: c 5660 out of range [5150..5250]
[   36.850611] ol_regdmn_init_channels: c 5680 out of range [5150..5250]
[   36.850626] ol_regdmn_init_channels: c 5700 out of range [5150..5250]
[   36.850637] ol_regdmn_init_channels: c 5720 out of range [5150..5250]
[   36.850648] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   36.850659] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   36.850678] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   36.850689] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   36.850699] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   36.850718] ol_regdmn_init_channels: c 5260 out of range [5150..5250]
[   36.850729] ol_regdmn_init_channels: c 5300 out of range [5150..5250]
[   36.850740] ol_regdmn_init_channels: c 5500 out of range [5150..5250]
[   36.850751] ol_regdmn_init_channels: c 5540 out of range [5150..5250]
[   36.850761] ol_regdmn_init_channels: c 5580 out of range [5150..5250]
[   36.850771] ol_regdmn_init_channels: c 5620 out of range [5150..5250]
[   36.850783] ol_regdmn_init_channels: c 5660 out of range [5150..5250]
[   36.850793] ol_regdmn_init_channels: c 5700 out of range [5150..5250]
[   36.850804] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   36.850816] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   36.850833] ol_regdmn_init_channels: c 5280 out of range [5150..5250]
[   36.850844] ol_regdmn_init_channels: c 5320 out of range [5150..5250]
[   36.850855] ol_regdmn_init_channels: c 5520 out of range [5150..5250]
[   36.850865] ol_regdmn_init_channels: c 5560 out of range [5150..5250]
[   36.850875] ol_regdmn_init_channels: c 5600 out of range [5150..5250]
[   36.850885] ol_regdmn_init_channels: c 5640 out of range [5150..5250]
[   36.850896] ol_regdmn_init_channels: c 5680 out of range [5150..5250]
[   36.850906] ol_regdmn_init_channels: c 5720 out of range [5150..5250]
[   36.850917] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   36.850927] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   36.850939] Add VHT80 channel: 5210
[   36.853468] Add VHT80 channel: 5290
[   36.856898] Add VHT80 channel: 5530
[   36.860358] Add VHT80 channel: 5610
[   36.863877] Add VHT80 channel: 5690
[   36.867316] Add VHT80 channel: 5775
[   36.870809] ol_regdmn_init_channels: c 5260 out of range [5150..5250]
[   36.870828] ol_regdmn_init_channels: c 5280 out of range [5150..5250]
[   36.870848] ol_regdmn_init_channels: c 5300 out of range [5150..5250]
[   36.870860] ol_regdmn_init_channels: c 5320 out of range [5150..5250]
[   36.870880] ol_regdmn_init_channels: c 5500 out of range [5150..5250]
[   36.870892] ol_regdmn_init_channels: c 5520 out of range [5150..5250]
[   36.870909] ol_regdmn_init_channels: c 5540 out of range [5150..5250]
[   36.870926] ol_regdmn_init_channels: c 5560 out of range [5150..5250]
[   36.870946] ol_regdmn_init_channels: c 5580 out of range [5150..5250]
[   36.870966] ol_regdmn_init_channels: c 5600 out of range [5150..5250]
[   36.870986] ol_regdmn_init_channels: c 5620 out of range [5150..5250]
[   36.871005] ol_regdmn_init_channels: c 5640 out of range [5150..5250]
[   36.871023] ol_regdmn_init_channels: c 5660 out of range [5150..5250]
[   36.871035] ol_regdmn_init_channels: c 5680 out of range [5150..5250]
[   36.871045] ol_regdmn_init_channels: c 5700 out of range [5150..5250]
[   36.871056] ol_regdmn_init_channels: c 5720 out of range [5150..5250]
[   36.871072] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   36.871090] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   36.871107] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   36.871126] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   36.871146] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   36.871169] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x200000) flags 0x4000100
[   36.878655] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x400000) flags 0x8000100
[   36.886555] ol_ath_phyerr_attach: called
[   36.886725] OL Resmgr Init-ed
[   36.889305] ieee80211_bsteering_attach: Band steering initialized
[   36.895313] acfg_attach: Offload using existing sock dd3b9c00
[   36.901000] ol_if_spectral_setup
[   36.901043] SPECTRAL : get_capability not registered
[   36.906018] HAL_CAP_PHYDIAG : Capable
[   36.909593] SPECTRAL : Need to fix the capablity check for RADAR (spectral_attach : 237)
[   36.917694] SPECTRAL : get_capability not registered
[   36.922597] HAL_CAP_RADAR   : Capable
[   36.926289] SPECTRAL : Need to fix the capablity check for SPECTRAL
[   36.926289]  (spectral_attach : 242)
[   36.936103] SPECTRAL : get_capability not registered
[   36.941011] HAL_CAP_SPECTRAL_SCAN : Capable
[   36.945206] SPECTRAL : get_tsf64 not registered
[   36.949689] spectral_init_netlink 78 NULL SKB
[   36.954062] Green-AP : Green-AP : Attached
[   36.954062] 
[   36.959586] Green-AP : Attached
[   36.962708] rate power table override is only supported for AR98XX
[   36.969227] ol_ath_smart_ant_attach: Hardware doest not support Smart Antenna.
[   36.976108] ol_if_dfs_setup: called 
[   36.976166] ol_if_dfs_attach: called; ptr=d9e6998c, radar_info=dc1afc40
[   36.982675] dfs_attach: event log enabled by default
[   36.988523] ol_ath_rtt_meas_report_attach: called
[   36.988548] ol_ath_lowi_wmi_event_attach: called
[   36.988564] >>>> CB Set   (null)
[   36.991225] of_get_named_gpiod_flags: can't parse gpios property of node '/soc/wifi@a800000[0]'
[   36.991247] ipq4019_wifi_led_init: Wifi LED init failed.. Couldn't get led gpio/led source
[   36.999228] ol_ath_attach() UMAC attach . 
[   37.003311] 
[   37.003311]  BURSTING enabled by default
[   37.009029] ol_ath_attach: Set global_ic[2] ..ptr:bf6cad28
[   37.014146] ath_lowi_if_netlink_init Incremented LOWI netlink ref count: 2
[   37.020977] osif_wrap_attach:441 osif wrap attached
[   37.025901] osif_wrap_devt_init:402 osif wrap dev table init done
[   37.031900]  Wrap Attached: Wrap_com =dd14da00 ic->ic_wrap_com=dd14da00 &wrap_com->wc_devt=dd14da00 
[   37.041064] __ol_ath_attach: needed_headroom reservation 60
[   37.048560] ol_ath_thermal_mitigation_attach: --
[   37.052201] ol_ath_ahb_probe num_radios=1, wifi_radios[1].sc = da8404c0 wifi_radio_type = 2
[   37.060598] ath_sysfs_diag_init: diag_fsattr 
[   37.065165] ath_ol_pci:  (Atheros/multi-bss)
[   37.069264] hif_pci_enable_bus: con_mode = 0x0, device_id = 0x56PCI: enabling device 0000:00:00.0 (0144 -> 0147)
[   37.079298] PCI: enabling device 0000:01:00.0 (0140 -> 0142)
[   37.085049] hif_pci_enable_bus: hif_enable_pci done *********** QCA9888 *************hif_pci_enable_bus: hif_type = 0xe, target_type = 0xchif_pci_enable_bus: hif_pci_probe_tgt_wakeup donehif_target_sync: Loop checking FW signalhif_target_sync: Got FW signal, retries = 0hif_config_ce: ce_init donehif_config_ce: X, ret = 0hif_set_hia: Ehif_set_hia_extnd: E
[   37.122614] chip_id 0xc chip_revision 0x0
[   37.126827] 
[   37.126827]  CLOCK PLL skipped
[   37.131299] hif_set_hia_extnd: setting the target pll frac ffffffff intval ffffffff
[   37.138978] hif_set_hia_extnd: no frac provided, skipping pre-configuring PLL
[   37.149251] hif_pci_bus_configure: hif_set_hia donehif_configure_irq: Ehif_pci_configure_legacy_irq: Ehif_pci_configure_legacy_irq: X, ret = 0hif_enable: X OKhif_napi_create: NAPI structures initializedhif_napi_create: NAPI id 6 created for pipe 5qca_napi_create: napi instance 32 created on pipe 4
[   37.174594] hif_napi_event: received evnt: CONF cmd; v = 1 (state=0x1)hif_napi_event: setting configuration to ON
[   37.174594] __ol_ath_attach() Allocated scn d9e804c0
[   37.188487] __ol_ath_attach: dev name wifi2
[   37.192636] ol_ath_attach interface_id 2
[   37.196811] ol_target_init() BMI inited.
[   37.200590] ol_target_init() BMI Get Target Info.
[   37.209281] Chip id: 0xc, chip version: 0x1000000
[   37.213890] 
[   37.213890]  CE WAR Disabled
[   37.218434] NUM_DEV=1 FWMODE=0x2 FWSUBMODE=0x0 FWBR_BUF 0
[   37.223848] ol_target_init() configure Target .
[   37.228220] 
[   37.228220]  Target Version is 1000000
[   37.233339] 
[   37.233339]  Flash Download Address  c0000 
[   37.238960] ol_transfer_bin_file: flash data file defined
[   37.244362] ol_transfer_bin_file[3686] Get Caldata for wifi2.
[   37.250124] qdf_fs_read[59], Open File /tmp/wifi2.caldata SUCCESS!!file system magic:16914836super blocksize:4096inode 4456file size:12064qc98xx_verify_checksum: flash checksum passed: 0x1c32
[   37.267113] ol_transfer_bin_file 3747: Download Flash data len 12064
[   37.273834] Board extended Data download address: 0x0
[   37.305130] 
[   37.305130]  Board data initialized
[   37.309196] ol_ath_download_firmware: Download OTP, flash download ADDRESS 0xc0000
[   37.316868] 
[   37.316868]  Selecting  OTP binary for CHIP Version 0
[   37.381858] [wifi1] 
[   37.383065] ath_ol_pci 0000:01:00.0: Firmware loaded from user helper succesfully
[   37.390530] ol_transfer_bin_file 3567: downloading file 0, Download data len 9084
[   37.398217] FWLOG: [44227] WAL_DBGID_TX_AC_BUFFER_SET ( 0x3, 0xdeb002, 0x94c, 0x94c, 0x0 )
[   37.406195] [wifi1] FWLOG: [44227] WAL_DBGID_TX_AC_BUFFER_SET ( 0x12, 0x1e, 0x94c, 0x94c, 0x0 )
[   37.414913] [wifi1] FWLOG: [44227] WAL_DBGID_TX_AC_BUFFER_SET ( 0x45, 0x1e, 0x94c, 0x94c, 0x0 )
[   37.423595] [wifi1] FWLOG: [44227] WAL_DBGID_TX_AC_BUFFER_SET ( 0x67, 0x1e, 0x94c, 0x94c, 0x0 )
[   37.432270] [wifi1] FWLOG: [44379] UNKNOWN 22:55 ( 0x3a, 0xa10, 0x160, 0x10, 0x0 )
[   37.456048] 
[   37.456048]  First OTP send param 8000
[   37.701009] ol_ath_download_firmware :First OTP download and Execute is good address:0x5c00 return param 4660
[   37.709935] ol_ath_download_firmware:##Board Id 23 , CHIP Id 0
[   37.715955] ol_ath_download_firmware: BOARDDATA DOWNLOAD TO address 0xc0000
[   37.722748] qdf_fs_read[59], Open File /tmp/country SUCCESS!!file system magic:16914836super blocksize:4096inode 5590file size:3qdf_fs_read[79]: caldata data size mismatch, fsize=3, cal_size=2!!!!!!!!!!!!!board_type:12, country code is US, boardid: 23 !!!!!!!!!!!!!!!
[   37.746395] 
[   37.746395]  wifi2: Selecting board data file name boardData_2_0_QCA9888_5G_Y9690_SBS_HB_US.bin
[   37.756690] ol_transfer_bin_file: Board Data File download to address=0xc0000 file name=QCA9888/hw.2/boardData_2_0_QCA9888_5G_Y9690_SBS_HB_US.bin
[   37.825641] ath_ol_pci 0000:01:00.0: Firmware loaded from user helper succesfully
[   37.832119] ol_transfer_bin_file 3567: downloading file 3, Download data len 12064
[   37.840104] Board extended Data download address: 0x0
[   37.868786] ol_ath_download_firmware: Using 0x1234 for the remainder of init
[   37.874862] 
[   37.874862]  Selecting  OTP binary for CHIP Version 0
[   37.881559] ath_ol_pci 0000:01:00.0: Firmware loaded from user helper succesfully
[   37.888866] ol_transfer_bin_file 3567: downloading file 0, Download data len 9084
[   37.931193] 
[   37.931193]  [Flash] : Ignore Module param
[   37.935789] 
[   37.935789]  Second otp download Param 10000 
[   38.183101] g_back_dev_num:16
[   38.194705] ol_ath_download_firmware : Second OTP download and Execute is good, param=0x0 
[   38.205209] 
[   38.205209]  Mission mode: Firmware CHIP Version 0
[   38.373333] ath_ol_pci 0000:01:00.0: Firmware loaded from user helper succesfully
[   38.380097] ol_swap_seg_alloc: Successfully allocated memory for SWAP size=262144 
[   38.388208] ath_ol_pci 0000:01:00.0: Firmware loaded from user helper succesfully
[   38.395287] Swap: bytes_left to copy: fw:16; dma_page:28009
[   38.400379] Swap: wrong length read:0
[   38.404088] ol_swap_wlan_memory_expansion: Swap total_bytes copied: 234135 Target address 41a4e8 
[   38.413060] scn=d9e804c0  target_write_addr=41a4e8 seg_info=dd1d4310 
[   38.419303] ol_transfer_swap_struct:Code swap structure successfully downloaded for bin type =2 
[   38.428127] bin_filename=QCA9888/hw.2/athwlan.bin swap_filename=/lib/firmware/QCA9888/hw.2/athwlan.codeswap.bin 
[   38.440665] ol_transfer_bin_file: Downloading firmware file: QCA9888/hw.2/athwlan.bin
[   38.806957] ath_ol_pci 0000:01:00.0: Firmware loaded from user helper succesfully
[   38.813494] ol_transfer_bin_file 3567: downloading file 1, Download data len 372624
[   38.931698] mode:0
[   40.312578] ol_target_init() Download FW done. 
[   40.316450] ol_ath_attach() WMI attached. wmi_handle da0f4000 
[   40.321912] wmi_unified_register_event_handler: Event id 62 is unavailable
[   40.328913] +htc_create ..  HIF :da950000-htc_create: (0xdc09f800)
[   40.334767] htc_wmi_init() HT Create . dc09f800
[   40.339549] htc_wmi_init 7585 host_enable 0 nss_nwifi_offload 0
[   40.345401] ol_ath_set_default_tgt_config : AC Minfree buffer allocation through module param (umac.ko)
[   40.354776]  OL_ACBKMinfree : 0
[   40.357835]  OL_ACBEMinfree : 0
[   40.360958]  OL_ACVIMinfree : 0
[   40.364107]  OL_ACVOMinfree : 0
[   40.367213] hif_enable_fastpath, Enabling fastpath mode
[   40.372245] +HWT
[   40.374272] hif_completion_thread_startup: pipe_num:0 pipe_info:0xda954578hif_completion_thread_startup: pipe_num:3 pipe_info:0xda954650hif_completion_thread_startup: pipe_num:4 pipe_info:0xda954698
[   40.396383] -HWT
[   40.397430] Startup Mode-0 set
[   40.400510] 
[   40.400510] <=== cfg max peer id 1056 ====>
[   40.407113] htt_peer_map_timer_init Enter pdev d9288000 hrtimer d928c888
[   40.412832] 
[   40.412832]  htt_alloc_peer_map_mem : Alloc Success : host q vaddr ddcb4000 paddr 9dcb4000
[   40.422516] 
[   40.422516]  htt_alloc_peer_map_mem : Flush Interval Configured to 256 pkts
[   40.434370] ol_txrx_pdev_attach: 2500 tx desc's allocated ; range starts from d8f00000
[   40.443468] Firmware_Build_Number:74 
[   40.446114] FW wireless modes: 0x7f9001
[   40.449969] num_rf_chain:0x00000002  ht_cap_info:0x0000085b  vht_cap_info:0x339979fa  vht_supp_mcs:0x0000fffa
[   40.459825] wmi_service_coex_gpio 0, wmi_service_4_wire_coex_support 0, coex_version 0
[   40.467875] 
[   40.467875] Sending Ext resource cfg: HOST PLATFORM as 0
[   40.467875] fw_feature_bitmap as 50 to TGT
[   40.478651] ol_ath_service_ready_event: tt_support: 1
[   40.483673] ol_ath_service_ready_event: periodic_chan_stats: 1
[   40.489425] ol_ath_service_ready_event: sw_cal_support_check_flag: 1
[   40.495823] Peer Caching Enabled ; num_peers = 530, num_active_peers = 52 num_tids = 104, num_vdevs = 17
[   40.505968] idx 1 req 2  num_units 1 num_unit_info 12 unit size 256 actual units 53 
[   40.513249] ol_ath_alloc_host_mem_chunk req_id 2 idx 0 num_units 53 unit_len 256,
[   40.520422] idx 2 req 3  num_units 1 num_unit_info 12 unit size 1024 actual units 53 
[   40.528308] ol_ath_alloc_host_mem_chunk req_id 3 idx 1 num_units 53 unit_len 1024,
[   40.535817] idx 3 req 4  num_units 1 num_unit_info 12 unit size 4096 actual units 53 
[   40.543778] ol_ath_alloc_host_mem_chunk req_id 4 idx 2 num_units 53 unit_len 4096,
[   40.551147] idx 0 req 1  num_units 0 num_unit_info 2 unit size 896 actual units 531 
[   40.559228] ol_ath_alloc_host_mem_chunk req_id 1 idx 3 num_units 531 unit_len 896,
[   40.566452] idx 4 req 5  num_units 0 num_unit_info 2 unit size 1956 actual units 531 
[   40.574992] ol_ath_alloc_host_mem_chunk req_id 5 idx 4 num_units 531 unit_len 1956,
[   40.581872] Support not added yet for Service 91
[   40.586498] Support not added yet for Service 92
[   40.591070] No EXT_MSG send INIT now
[   40.594718] chunk 0 len 13568 requested , ptr  0x99f70000
[   40.600016] chunk 1 len 54272 requested , ptr  0x98f70000
[   40.605414] chunk 2 len 217088 requested , ptr  0x98f80000
[   40.610865] chunk 3 len 475776 requested , ptr  0x98800000
[   40.616352] chunk 4 len 1038636 requested , ptr  0x98900000
[   40.621917] ol_ath_service_ready_event[4310] WAPI MBSSID 2 
[   40.670428] Version = 16777216 3  status = 0
[   40.673723] ol_ath_connect_htc() WMI is ready
[   40.678054] htt_h2t_frag_desc_bank_cfg_msg - HTT_H2T_MSG_TYPE_FRAG_DESC_BANK_CFG sent to FW for radio ID = 2
[   40.678080] target uses HTT version 2.2; host uses 2.2
[   40.699113] ol_ath_attach() connect HTC. 
[   40.702093] bypasswmi : 0
[   40.704714] ol_ath_attach: low_5ghz: 5490  high_5gh: 5850 
[   40.710174] ol_regdmn_start: reg-domain param: regdmn=0, countryName=, wModeSelect=FFFFFFFF, netBand=FFFFFFFF, extendedChanMode=0.
[   40.721923] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x2) flags 0x2150
[   40.728942] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   40.728954] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   40.728965] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   40.728975] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   40.728986] ol_regdmn_init_channels: c 5260 out of range [5490..5850]
[   40.728996] ol_regdmn_init_channels: c 5280 out of range [5490..5850]
[   40.729006] ol_regdmn_init_channels: c 5300 out of range [5490..5850]
[   40.729016] ol_regdmn_init_channels: c 5320 out of range [5490..5850]
[   40.729054] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x4) flags 0xa0
[   40.735793] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x8) flags 0xc0
[   40.742634] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x20) flags 0xd0
[   40.749591] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x40) flags 0x150
[   40.756625] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x800) flags 0x10080
[   40.763917] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x2000) flags 0x20080
[   40.771280] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x4000) flags 0x40080
[   40.778675] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   40.778696] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   40.778716] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   40.778726] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   40.778737] ol_regdmn_init_channels: c 5260 out of range [5490..5850]
[   40.778748] ol_regdmn_init_channels: c 5280 out of range [5490..5850]
[   40.778758] ol_regdmn_init_channels: c 5300 out of range [5490..5850]
[   40.778768] ol_regdmn_init_channels: c 5320 out of range [5490..5850]
[   40.778804] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   40.778821] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   40.778856] ol_regdmn_init_channels: c 5260 out of range [5490..5850]
[   40.778881] ol_regdmn_init_channels: c 5300 out of range [5490..5850]
[   40.778905] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   40.778918] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   40.778929] ol_regdmn_init_channels: c 5280 out of range [5490..5850]
[   40.778939] ol_regdmn_init_channels: c 5320 out of range [5490..5850]
[   40.778962] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   40.778973] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   40.778983] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   40.778993] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   40.779004] ol_regdmn_init_channels: c 5260 out of range [5490..5850]
[   40.779014] ol_regdmn_init_channels: c 5280 out of range [5490..5850]
[   40.779024] ol_regdmn_init_channels: c 5300 out of range [5490..5850]
[   40.779034] ol_regdmn_init_channels: c 5320 out of range [5490..5850]
[   40.779064] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   40.779074] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   40.779085] ol_regdmn_init_channels: c 5260 out of range [5490..5850]
[   40.779095] ol_regdmn_init_channels: c 5300 out of range [5490..5850]
[   40.779118] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   40.779135] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   40.779164] ol_regdmn_init_channels: c 5280 out of range [5490..5850]
[   40.779193] ol_regdmn_init_channels: c 5320 out of range [5490..5850]
[   40.779230] Add VHT80 channel: 5210
[   40.782127] Add VHT80 channel: 5290
[   40.785613] Add VHT80 channel: 5530
[   40.789072] Add VHT80 channel: 5610
[   40.792540] Add VHT80 channel: 5690
[   40.796029] Add VHT80 channel: 5775
[   40.799494] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   40.799505] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   40.799515] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   40.799526] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   40.799536] ol_regdmn_init_channels: c 5260 out of range [5490..5850]
[   40.799546] ol_regdmn_init_channels: c 5280 out of range [5490..5850]
[   40.799556] ol_regdmn_init_channels: c 5300 out of range [5490..5850]
[   40.799566] ol_regdmn_init_channels: c 5320 out of range [5490..5850]
[   40.799596] Skipping VHT80 channel 5825
[   40.803329] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5290
[   40.803357] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5210
[   40.803385] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5610
[   40.803413] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5530
[   40.803436] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   40.803446] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   40.803456] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   40.803466] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   40.803477] ol_regdmn_init_channels: c 5260 out of range [5490..5850]
[   40.803487] ol_regdmn_init_channels: c 5280 out of range [5490..5850]
[   40.803499] ol_regdmn_init_channels: c 5300 out of range [5490..5850]
[   40.803509] ol_regdmn_init_channels: c 5320 out of range [5490..5850]
[   40.803570] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5530
[   40.803580] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5210
[   40.803589] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5610
[   40.803598] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5210
[   40.803608] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5690
[   40.803617] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5210
[   40.803626] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5775
[   40.803635] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5210
[   40.803644] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5530
[   40.803653] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5290
[   40.803663] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5610
[   40.803672] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5290
[   40.803681] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5690
[   40.803690] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5290
[   40.803701] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5775
[   40.803710] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5290
[   40.803719] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5690
[   40.803729] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5530
[   40.803738] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5775
[   40.803747] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5530
[   40.803757] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5775
[   40.803766] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5610
[   40.803776] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5775
[   40.803791] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5690
[   40.803820] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   40.803849] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   40.803878] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   40.803907] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   40.803936] ol_regdmn_init_channels: c 5260 out of range [5490..5850]
[   40.803965] ol_regdmn_init_channels: c 5280 out of range [5490..5850]
[   40.803993] ol_regdmn_init_channels: c 5300 out of range [5490..5850]
[   40.804022] ol_regdmn_init_channels: c 5320 out of range [5490..5850]
[   40.804124] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5690, cfreq2:5530 in case of VHT80+80
[   40.812089] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5690, cfreq2:5530 in case of VHT80+80
[   40.820876] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5530 in case of VHT80+80
[   40.829629] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5610 in case of VHT80+80
[   40.838396] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5690 in case of VHT80+80
[   40.847168] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5530 in case of VHT80+80
[   40.855928] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5610 in case of VHT80+80
[   40.864696] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5690 in case of VHT80+80
[   40.873467] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5530 in case of VHT80+80
[   40.882219] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5610 in case of VHT80+80
[   40.890998] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5690 in case of VHT80+80
[   40.899776] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5530 in case of VHT80+80
[   40.908606] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5610 in case of VHT80+80
[   40.917320] EMI WAR rejecting fc1 > fc2 Combination cfreq1:5775, cfreq2:5690 in case of VHT80+80
[   40.926770] ol_ath_phyerr_attach: called
[   40.926874] freq=106 
[   40.928299] freq=122 
[   40.930563] freq=138 
[   40.932873] OL Resmgr Init-ed
[   40.935907] ieee80211_bsteering_attach: Band steering initialized
[   40.941858] acfg_attach: Offload using existing sock dd3b9c00
[   40.947613] ol_if_spectral_setup
[   40.947655] SPECTRAL : get_capability not registered
[   40.952529] HAL_CAP_PHYDIAG : Capable
[   40.956197] SPECTRAL : Need to fix the capablity check for RADAR (spectral_attach : 237)
[   40.964263] SPECTRAL : get_capability not registered
[   40.969192] HAL_CAP_RADAR   : Capable
[   40.972852] SPECTRAL : Need to fix the capablity check for SPECTRAL
[   40.972852]  (spectral_attach : 242)
[   40.982649] SPECTRAL : get_capability not registered
[   40.987608] HAL_CAP_SPECTRAL_SCAN : Capable
[   40.991764] SPECTRAL : get_tsf64 not registered
[   40.996292] spectral_init_netlink 78 NULL SKB
[   41.000624] Green-AP : Green-AP : Attached
[   41.000624] 
[   41.006185] Green-AP : Attached
[   41.009299] rate power table override is only supported for AR98XX
[   41.015545] ol_ath_smart_ant_attach: Hardware doest not support Smart Antenna.
[   41.022670] ol_if_dfs_setup: called 
[   41.022721] ol_if_dfs_attach: called; ptr=d8f6998c, radar_info=dc1afc18
[   41.029282] dfs_attach: event log enabled by default
[   41.035007] ol_ath_rtt_meas_report_attach: called
[   41.035028] ol_ath_lowi_wmi_event_attach: called
[   41.035044] >>>> CB Set   (null)
[   41.038061] ol_ath_attach() UMAC attach . 
[   41.041506] 
[   41.041506]  BURSTING enabled by default
[   41.046982] ol_ath_attach: Set global_ic[3] ..ptr:bf6cad28
[   41.052366] ath_lowi_if_netlink_init Incremented LOWI netlink ref count: 3
[   41.059240] osif_wrap_attach:441 osif wrap attached
[   41.064124] osif_wrap_devt_init:402 osif wrap dev table init done
[   41.070155]  Wrap Attached: Wrap_com =da976400 ic->ic_wrap_com=da976400 &wrap_com->wc_devt=da976400 
[   41.079281] __ol_ath_attach: needed_headroom reservation 60
[   41.086264] ol_ath_thermal_mitigation_attach: --
[   41.089957] ol_ath_pci_probe num_radios=2, wifi_radios[2].sc = d9e804c0 wifi_radio_type = 2
[   41.098297] ath_sysfs_diag_init: diag_fsattr 
[   41.116340]  pktlog_init: Initializing Pktlog for AR900B, pktlog_hdr_size = 16
[   41.122550] +hif_update_pipe_callback pipeid 8
[   41.127064] -hif_update_pipe_callback
[   41.130671]  pktlog_init: Initializing Pktlog for AR900B, pktlog_hdr_size = 16
[   41.137873] +hif_update_pipe_callback pipeid 8
[   41.142236] -hif_update_pipe_callback
[   41.146095]  pktlog_init: Initializing Pktlog for AR900B, pktlog_hdr_size = 16
[   41.153194] +hif_update_pipe_callback pipeid 8
[   41.157525] -hif_update_pipe_callback
[   41.172993] __sa_init_module 
[   41.208198] Removing athdebug proc file
[   41.211038] ath_dev: driver unloaded
[   41.223902] ath_tx99: driver unloaded
[   41.235633] ath_rate_atheros: driver unloaded
[   41.248209] ath_hal: driver unloaded
[   41.289660] [ol_ath_iw_setcountry][1757] *p=55, *(p+1)=53
[   41.294336] isCountryCodeValid: EEPROM regdomain 0x0
[   41.299011] ol_regdmn_init_channels: !avail mode 0x680c (0x2) flags 0x2150
[   41.306036] ol_regdmn_init_channels: !avail mode 0x680c (0x1) flags 0x140
[   41.312653] ol_regdmn_init_channels: !avail mode 0x680c (0x20) flags 0xd0
[   41.319537] ol_regdmn_init_channels: !avail mode 0x680c (0x40) flags 0x150
[   41.326449] ol_regdmn_init_channels: !avail mode 0x680c (0x1000) flags 0x10100
[   41.333547] ol_regdmn_init_channels: !avail mode 0x680c (0x8000) flags 0x20100
[   41.340658] ol_regdmn_init_channels: !avail mode 0x680c (0x10000) flags 0x40100
[   41.344731] [wifi2] FWLOG: [41316] WAL_DBGID_TX_AC_BUFFER_SET ( 0x3, 0xdeb002, 0x94c, 0x94c, 0x0 )
[   41.344750] [wifi2] FWLOG: [41316] WAL_DBGID_TX_AC_BUFFER_SET ( 0x12, 0x1e, 0x94c, 0x94c, 0x0 )
[   41.344768] [wifi2] FWLOG: [41316] WAL_DBGID_TX_AC_BUFFER_SET ( 0x45, 0x1e, 0x94c, 0x94c, 0x0 )
[   41.344786] [wifi2] FWLOG: [41316] WAL_DBGID_TX_AC_BUFFER_SET ( 0x67, 0x1e, 0x94c, 0x94c, 0x0 )
[   41.344798] [wifi2] FWLOG: [41316] WAL_DBGID_TX_AC_BUFFER_SET ( 0x100, 0x11e1a300 )
[   41.344817] [wifi2] FWLOG: [41581] UNKNOWN 22:55 ( 0x3a, 0xa10, 0x160, 0x10, 0x0 )
[   41.398162] ol_regdmn_init_channels: !avail mode 0x680c (0x20000) flags 0x100100
[   41.405518] ol_regdmn_init_channels: !avail mode 0x680c (0x40000) flags 0x200100
[   41.412966] ol_regdmn_init_channels: !avail mode 0x680c (0x80000) flags 0x400100
[   41.420257] ol_regdmn_init_channels: !avail mode 0x680c (0x100000) flags 0x800100
[   41.427737] ol_regdmn_init_channels: !avail mode 0x680c (0x200000) flags 0x4000100
[   41.435288] ol_regdmn_init_channels: !avail mode 0x680c (0x400000) flags 0x8000100
[   41.455094] isCountryCodeValid: EEPROM regdomain 0x0
[   41.459062] ol_regdmn_init_channels: !avail mode 0x680c (0x2) flags 0x2150
[   41.465922] ol_regdmn_init_channels: !avail mode 0x680c (0x1) flags 0x140
[   41.472702] ol_regdmn_init_channels: !avail mode 0x680c (0x20) flags 0xd0
[   41.479466] ol_regdmn_init_channels: !avail mode 0x680c (0x40) flags 0x150
[   41.486348] ol_regdmn_init_channels: !avail mode 0x680c (0x1000) flags 0x10100
[   41.493574] ol_regdmn_init_channels: !avail mode 0x680c (0x8000) flags 0x20100
[   41.500707] ol_regdmn_init_channels: !avail mode 0x680c (0x10000) flags 0x40100
[   41.508013] ol_regdmn_init_channels: !avail mode 0x680c (0x20000) flags 0x100100
[   41.515394] ol_regdmn_init_channels: !avail mode 0x680c (0x40000) flags 0x200100
[   41.522754] ol_regdmn_init_channels: !avail mode 0x680c (0x80000) flags 0x400100
[   41.530146] ol_regdmn_init_channels: !avail mode 0x680c (0x100000) flags 0x800100
[   41.537624] ol_regdmn_init_channels: !avail mode 0x680c (0x200000) flags 0x4000100
[   41.545165] ol_regdmn_init_channels: !avail mode 0x680c (0x400000) flags 0x8000100
[   41.625040] set TXBF_SND_PERIOD: value 100 wmi_status 0
[   41.688959]  Disconnect_timeout value entered:10 
[   41.705417]  reconfiguration_timeout value entered:60 
[   41.810763] [wifi0] FWLOG: [49048] UNKNOWN 22:55 ( 0x3a, 0xa10, 0x160, 0x0, 0x12 )
[   41.817300] [wifi0] FWLOG: [49161] UNKNOWN 22:55 ( 0x16, 0xa10, 0x810, 0x0, 0x12 )
[   42.014417] wlan_vap_create : enter. devhandle=0xdb5c04c0, opmode=IEEE80211_M_HOSTAP, flags=0x1
[   42.022167] send_vdev_create_cmd_non_tlv: ID = 0 Type = 1, Subtype = 0 VAP Addr = cc:32:e5:3a:29:bc:
[   42.031384] ieee80211_mbo_vattach:MBO Initialized 
[   42.036011] ieee80211_oce_vattach: OCE Initialized 
[   42.041083] wlan_vap_create : exit. devhandle=0xdb5c04c0, vap=0xdc240000, opmode=IEEE80211_M_HOSTAP, flags=0x1.
[   42.050965] __ieee80211_smart_ant_init: Smart Antenna is not supported 
[   42.057552] Enabling TX checksum bit for the vap ath02 features 4000 
[   42.063959] Enabling SG bit for the vap ath02 features 4000 
[   42.069577] Enabling SG bit for the vap ath02 features 4000 
[   42.075251] Enabling TSO bit for the vap ath02 features 4000 
[   42.080949] Enabling LRO bit for the vap ath02 features 4000 
[   42.086695] VAP device ath02 created osifp: (ddca2cc0) os_if: (dc240000)
[   42.120904] siwfreq
[   42.121993] Set freq vap 0 stop send + dc240000
[   42.126777] Set freq vap 0 stop send -dc240000
[   42.152817] Set wait done --dc240000
[   42.323971] Setting Max Stations:64
[   42.374563]  
[   42.374563]  DES SSID SET= 
[   42.390074] vap-0(ath02):set SIOC80211NWID, 16 characters
[   42.394693]  
[   42.394693]  DES SSID SET=zEQQohyXxaOcCULy 
[   42.467304] ol_ath_set_config_param Set btcoex_wlan_priority:52 
[   42.472310] ol_ath_set_config_param Set default val btcoex_period:100 btcoex_duration:80 
[   42.863066]  ieee80211_ioctl_siwmode: imr.ifm_active=131712, new mode=3, valid=1 
[   42.913367]  DEVICE IS DOWN ifname=ath02
[   42.916415]  DEVICE IS DOWN ifname=ath02
[   43.133235] Sending SCAN START cmd
[   43.182087] ol_scan_unregister_event_handler: Failed to unregister evhandler=bf6171d0 arg=dab20000
[   43.182087] 
[   43.191587] osif_vap_init: Scan in progress.. Cancelling it. vap: 0xdc240000 
[   43.199066] send_vdev_down_cmd_non_tlv for vap 0 (df5ea000)
[   43.233211] Sending SCAN START cmd
[   43.255674] wlan_vap_create : enter. devhandle=0xdb5c04c0, opmode=IEEE80211_M_HOSTAP, flags=0x1
[   43.263504] send_vdev_create_cmd_non_tlv: ID = 1 Type = 1, Subtype = 0 VAP Addr = d2:32:e5:3a:29:bc:
[   43.272572] ieee80211_mbo_vattach:MBO Initialized 
[   43.277304] ieee80211_oce_vattach: OCE Initialized 
[   43.282326] wlan_vap_create : exit. devhandle=0xdb5c04c0, vap=0xdb580000, opmode=IEEE80211_M_HOSTAP, flags=0x1.
[   43.292396] __ieee80211_smart_ant_init: Smart Antenna is not supported 
[   43.298828] Enabling TX checksum bit for the vap ath0 features 4000 
[   43.305152] Enabling SG bit for the vap ath0 features 4000 
[   43.310653] Enabling SG bit for the vap ath0 features 4000 
[   43.316258] Enabling TSO bit for the vap ath0 features 4000 
[   43.321850] Enabling LRO bit for the vap ath0 features 4000 
[   43.327531] VAP device ath0 created osifp: (ded5fcc0) os_if: (db580000)
[   43.361939] siwfreq
[   43.363221] Set freq vap 0 stop send + dc240000
[   43.367575] ol_scan_unregister_event_handler: Failed to unregister evhandler=bf6171d0 arg=dab20000
[   43.367575] 
[   43.378806] osif_vap_acs_cancel: Scan in progress.. Cancelling it vap: 0xdc240000
[   43.386195] send_vdev_down_cmd_non_tlv for vap 0 (df5ea000)
[   43.391456] Set freq vap 0 stop send -dc240000
[   43.422853] Set wait done --dc240000
[   43.425422] Set freq vap 1 stop send + db580000
[   43.430260] Set freq vap 1 stop send -db580000
[   43.462803] Set wait done --db580000
[   43.493215] Sending SCAN START cmd
[   43.549309] ol_scan_unregister_event_handler: Failed to unregister evhandler=bf6171d0 arg=dab20000
[   43.549309] 
[   43.558823] osif_vap_init: Scan in progress.. Cancelling it. vap: 0xdc240000 
[   43.566219] send_vdev_down_cmd_non_tlv for vap 0 (df5ea000)
[   43.593194] Sending SCAN START cmd
[   43.709305] Setting Max Stations:64
[   43.760989]  
[   43.760989]  DES SSID SET= 
[   43.776971] vap-1(ath0):set SIOC80211NWID, 4 characters
[   43.781180]  
[   43.781180]  DES SSID SET=test 
[   43.809781] [wifi0] FWLOG: [50749] WAL_DBGID_SECURITY_ENCR_EN (  )
[   43.814938] [wifi0] FWLOG: [50749] WAL_DBGID_SECURITY_MCAST_KEY_SET ( 0x1 )
[   43.823525] [wifi0] FWLOG: [50783] WAL channel change freq=2412, mode=1 flags=0 rx_ok=1 tx_ok=1
[   43.832224] [wifi0] FWLOG: [50853] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   43.832247] [wifi0] FWLOG: [50853] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   43.832256] [wifi0] FWLOG: [51044] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   43.832267] [wifi0] FWLOG: [51044] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   43.832277] [wifi0] FWLOG: [51229] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   43.832286] [wifi0] FWLOG: [51229] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   43.883173] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   43.906313] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   43.924611] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   43.942869] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   43.949058] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   44.414968] ME Pool succesfully initialized vaddr - d8a00000 paddr - 0
[   44.414968] num_elems = 1424 buf_size - 64 pool_size = 102528
[   44.426506] Enable MCAST_TO_UCAST
[   44.442898]  ieee80211_ioctl_siwmode: imr.ifm_active=131712, new mode=3, valid=1 
[   44.503208]  DEVICE IS DOWN ifname=ath0
[   44.506099]  DEVICE IS DOWN ifname=ath0
[   44.723571] osif_vap_init: Scan in progress.. Cancelling it. vap: 0xdb580000 
[   44.809435] [wifi0] FWLOG: [51568] WAL channel change freq=2417, mode=1 flags=0 rx_ok=1 tx_ok=1
[   44.817332] [wifi0] FWLOG: [51883] WAL channel change freq=2422, mode=1 flags=0 rx_ok=1 tx_ok=1
[   44.826195] [wifi0] FWLOG: [52197] WAL channel change freq=2427, mode=1 flags=0 rx_ok=1 tx_ok=1
[   44.839608] [wifi0] FWLOG: [52409] WAL_DBGID_SECURITY_ENCR_EN (  )
[   44.849180] [wifi0] FWLOG: [52409] WAL_DBGID_SECURITY_MCAST_KEY_SET ( 0x1 )
[   45.038367] device ath0 entered promiscuous mode
[   45.043131] br-lan: port 3(ath0) entered forwarding state
[   45.047636] br-lan: port 3(ath0) entered forwarding state
[   45.053561] IPv6: ADDRCONF(NETDEV_CHANGE): br-lan: link becomes ready
[   45.103873] osif_vap_init: Scan in progress.. Cancelling it. vap: 0xdb580000 
[   45.674315] [ol_ath_iw_setcountry][1757] *p=55, *(p+1)=53
[   45.678720] isCountryCodeValid: EEPROM regdomain 0x0
[   45.683753] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x2) flags 0x2150
[   45.690769] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.690783] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.690793] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.690804] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.690814] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   45.690827] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x4) flags 0xa0
[   45.697584] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x8) flags 0xc0
[   45.704538] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x20) flags 0xd0
[   45.711338] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x40) flags 0x150
[   45.718387] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x800) flags 0x10080
[   45.725678] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x2000) flags 0x20080
[   45.733276] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x4000) flags 0x40080
[   45.740433] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.740444] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.740454] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.740465] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.740475] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   45.740495] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.740506] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.740525] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.740536] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.740556] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.740567] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.740577] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.740587] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.740597] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   45.740615] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.740626] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.740644] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.740655] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.740673] Add VHT80 channel: 5210
[   45.743910] Add VHT80 channel: 5290
[   45.747358] Add VHT80 channel: 5530
[   45.750826] Add VHT80 channel: 5610
[   45.754356] Add VHT80 channel: 5690
[   45.757776] Add VHT80 channel: 5775
[   45.761258] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.761269] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.761280] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.761290] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.761302] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   45.761316] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x200000) flags 0x4000100
[   45.769078] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x400000) flags 0x8000100
[   45.788949] isCountryCodeValid: EEPROM regdomain 0x0
[   45.792974] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x2) flags 0x2150
[   45.799936] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.799949] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.799960] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.799970] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.799980] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   45.799993] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x4) flags 0xa0
[   45.806813] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x8) flags 0xc0
[   45.809164] [wifi0] FWLOG: [52510] WAL channel change freq=2432, mode=1 flags=0 rx_ok=1 tx_ok=1
[   45.809176] [wifi0] FWLOG: [52825] WAL channel change freq=2437, mode=1 flags=0 rx_ok=1 tx_ok=1
[   45.809187] [wifi0] FWLOG: [53139] WAL channel change freq=2442, mode=1 flags=0 rx_ok=1 tx_ok=1
[   45.809198] [wifi0] FWLOG: [53452] WAL channel change freq=2447, mode=1 flags=0 rx_ok=1 tx_ok=1
[   45.848397] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x20) flags 0xd0
[   45.855336] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x40) flags 0x150
[   45.862331] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x800) flags 0x10080
[   45.869666] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x2000) flags 0x20080
[   45.877032] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x4000) flags 0x40080
[   45.884421] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.884433] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.884444] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.884454] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.884470] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   45.884507] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.884518] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.884536] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.884547] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.884567] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.884577] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.884587] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.884598] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.884608] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   45.884626] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.884638] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.884669] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.884700] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.884726] Add VHT80 channel: 5210
[   45.887850] Add VHT80 channel: 5290
[   45.891318] Add VHT80 channel: 5530
[   45.894821] Add VHT80 channel: 5610
[   45.898266] Add VHT80 channel: 5690
[   45.901736] Add VHT80 channel: 5775
[   45.905250] ol_regdmn_init_channels: c 5745 out of range [5150..5250]
[   45.905267] ol_regdmn_init_channels: c 5765 out of range [5150..5250]
[   45.905278] ol_regdmn_init_channels: c 5785 out of range [5150..5250]
[   45.905288] ol_regdmn_init_channels: c 5805 out of range [5150..5250]
[   45.905299] ol_regdmn_init_channels: c 5825 out of range [5150..5250]
[   45.905312] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x200000) flags 0x4000100
[   45.912969] ol_regdmn_init_channels: !avail mode 0x1f9001 (0x400000) flags 0x8000100
[   46.005395] set TXBF_SND_PERIOD: value 100 wmi_status 0
[   46.070076]  Disconnect_timeout value entered:10 
[   46.085846]  reconfiguration_timeout value entered:60 
[   46.333304] wlan_vap_create : enter. devhandle=0xda8404c0, opmode=IEEE80211_M_HOSTAP, flags=0x1
[   46.341054] send_vdev_create_cmd_non_tlv: ID = 0 Type = 1, Subtype = 0 VAP Addr = cc:32:e5:3a:29:bd:
[   46.350612] ieee80211_mbo_vattach:MBO Initialized 
[   46.354949] ieee80211_oce_vattach: OCE Initialized 
[   46.359975] wlan_vap_create : exit. devhandle=0xda8404c0, vap=0xd8a40000, opmode=IEEE80211_M_HOSTAP, flags=0x1.
[   46.369851] __ieee80211_smart_ant_init: Smart Antenna is not supported 
[   46.371364] [wifi1] FWLOG: [53488] UNKNOWN 22:55 ( 0x3a, 0xa10, 0x160, 0x10, 0x0 )
[   46.371384] [wifi1] FWLOG: [53636] UNKNOWN 22:55 ( 0x16, 0xa10, 0x810, 0x10, 0x0 )
[   46.391545] Enabling TX checksum bit for the vap ath12 features 4000 
[   46.397951] Enabling SG bit for the vap ath12 features 4000 
[   46.403584] Enabling SG bit for the vap ath12 features 4000 
[   46.409213] Enabling TSO bit for the vap ath12 features 4000 
[   46.414958] Enabling LRO bit for the vap ath12 features 4000 
[   46.420674] VAP device ath12 created osifp: (dc09acc0) os_if: (d8a40000)
[   46.461901] siwfreq
[   46.463110] Set freq vap 0 stop send + d8a40000
[   46.467697] Set freq vap 0 stop send -d8a40000
[   46.492872] Set wait done --d8a40000
[   46.664653] Setting Max Stations:64
[   46.715806]  
[   46.715806]  DES SSID SET= 
[   46.731368] vap-0(ath12):set SIOC80211NWID, 16 characters
[   46.735992]  
[   46.735992]  DES SSID SET=zEQQohyXxaOcCULy 
[   46.808635] [wifi0] FWLOG: [53766] WAL channel change freq=2452, mode=1 flags=0 rx_ok=1 tx_ok=1
[   46.816536] [wifi0] FWLOG: [54080] WAL channel change freq=2457, mode=1 flags=0 rx_ok=1 tx_ok=1
[   46.825358] [wifi0] FWLOG: [54394] WAL channel change freq=2462, mode=1 flags=0 rx_ok=1 tx_ok=1
[   46.967520] send_vdev_down_cmd_non_tlv for vap 0 (df5ea000)
[   46.972451] OL vap_start +
[   46.974795] VDEV START
[   46.977122] OL vap_start -
[   46.979823] ol_ath_vap_set_param: Now supported MGMT RATE is 1000(kbps) and rate code: 0x43
[   46.988316] OL vap_start +
[   46.990833] VDEV START
[   46.993186] OL vap_start -
[   46.995876] ol_ath_vap_set_param: Now supported MGMT RATE is 1000(kbps) and rate code: 0x43
[   47.164853] ol_vdev_start_resp_ev for vap 0 (df5ea000)
[   47.168996] send_wmm_update_cmd_non_tlv:
[   47.173092] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   47.179936] send_vdev_up_cmd_non_tlv for vap 0 (df5ea000)
[   47.185326] __ieee80211_smart_ant_init: Smart Antenna is not supported 
[   47.191935] ol_vdev_start_resp_ev for vap 1 (df5ea000)
[   47.197039] send_wmm_update_cmd_non_tlv:
[   47.201058] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   47.207988] send_vdev_up_cmd_non_tlv for vap 1 (df5ea000)
[   47.232962]  ieee80211_ioctl_siwmode: imr.ifm_active=66176, new mode=3, valid=1 
[   47.283136]  DEVICE IS DOWN ifname=ath12
[   47.286238]  DEVICE IS DOWN ifname=ath12
[   47.513144] Sending SCAN START cmd
[   47.570962] wlan_vap_create : enter. devhandle=0xda8404c0, opmode=IEEE80211_M_HOSTAP, flags=0x1
[   47.578912] send_vdev_create_cmd_non_tlv: ID = 1 Type = 1, Subtype = 0 VAP Addr = d2:32:e5:3a:29:bd:
[   47.588061] ieee80211_mbo_vattach:MBO Initialized 
[   47.592534] ieee80211_oce_vattach: OCE Initialized 
[   47.597653] wlan_vap_create : exit. devhandle=0xda8404c0, vap=0xd8a80000, opmode=IEEE80211_M_HOSTAP, flags=0x1.
[   47.607488] __ieee80211_smart_ant_init: Smart Antenna is not supported 
[   47.614121] Enabling TX checksum bit for the vap ath1 features 4000 
[   47.620395] Enabling SG bit for the vap ath1 features 4000 
[   47.625965] Enabling SG bit for the vap ath1 features 4000 
[   47.631508] Enabling TSO bit for the vap ath1 features 4000 
[   47.637165] Enabling LRO bit for the vap ath1 features 4000 
[   47.642807] VAP device ath1 created osifp: (dc098cc0) os_if: (d8a80000)
[   47.678626] siwfreq
[   47.679714] Set freq vap 0 stop send + d8a40000
[   47.684439] ol_scan_unregister_event_handler: Failed to unregister evhandler=bf6171d0 arg=d9920000
[   47.684439] 
[   47.694780] osif_vap_acs_cancel: Scan in progress.. Cancelling it vap: 0xd8a40000
[   47.702523] send_vdev_down_cmd_non_tlv for vap 0 (db65e000)
[   47.707995] Set freq vap 0 stop send -d8a40000
[   47.732837] Set wait done --d8a40000
[   47.735391] Set freq vap 1 stop send + d8a80000
[   47.740345] Set freq vap 1 stop send -d8a80000
[   47.772823] Set wait done --d8a80000
[   47.803112] Sending SCAN START cmd
[   47.808089] [wifi0] FWLOG: [54713] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   47.813582] [wifi0] FWLOG: [54713] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   47.820089] [wifi0] FWLOG: [54718] vap-0 VDEV_MGR_VDEV_START ( 0x980, 0x2, 0x0, 0x0 )
[   47.830078] [wifi0] FWLOG: [54719] WAL channel change freq=2432, mode=7 flags=0 rx_ok=1 tx_ok=1
[   47.838779] [wifi0] FWLOG: [54911] UNKNOWN 14:20 ( 0x0 )
[   47.838800] [wifi0] FWLOG: [54911] vap-1 VDEV_MGR_VDEV_START ( 0x980, 0x2, 0x0, 0x0 )
[   47.838821] [wifi0] FWLOG: [54938] VDEV_MGR_HP_START_TIME ( 0x0, 0x980, 0xc80001 )
[   47.838843] [wifi0] FWLOG: [54938] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x1 )
[   47.838854] [wifi0] FWLOG: [54938] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   47.838864] [wifi0] FWLOG: [54938] VDEV_MGR_AP_TBTT_CONFIG ( 0x0, 0x980, 0x0, 0x0 )
[   47.838882] [wifi0] FWLOG: [54938] UNKNOWN 14:20 ( 0x0 )
[   47.838893] [wifi0] FWLOG: [54962] VDEV_MGR_HP_START_TIME ( 0x0, 0x980, 0xc80001 )
[   47.838909] [wifi0] FWLOG: [54962] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x1 )
[   47.838919] [wifi0] FWLOG: [54962] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   47.838928] [wifi0] FWLOG: [54962] VDEV_MGR_AP_TBTT_CONFIG ( 0x1, 0x980, 0x0, 0x0 )
[   47.936534] ol_scan_unregister_event_handler: Failed to unregister evhandler=bf6171d0 arg=d9920000
[   47.936534] 
[   47.946033] osif_vap_init: Scan in progress.. Cancelling it. vap: 0xd8a40000 
[   47.953461] send_vdev_down_cmd_non_tlv for vap 0 (db65e000)
[   47.983251] Sending SCAN START cmd
[   48.099290] Setting Max Stations:64
[   48.151383]  
[   48.151383]  DES SSID SET= 
[   48.167128] vap-1(ath1):set SIOC80211NWID, 4 characters
[   48.171337]  
[   48.171337]  DES SSID SET=test 
[   48.228977] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   48.247742] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   48.266407] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   48.285373] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   48.291443] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   48.370444] [wifi1] FWLOG: [55237] WAL_DBGID_SECURITY_ENCR_EN (  )
[   48.375593] [wifi1] FWLOG: [55237] WAL_DBGID_SECURITY_MCAST_KEY_SET ( 0x1 )
[   48.382538] [wifi1] FWLOG: [55271] WAL channel change freq=5180, mode=0 flags=0 rx_ok=1 tx_ok=1
[   48.391228] [wifi1] FWLOG: [55467] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   48.397724] [wifi1] FWLOG: [55467] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   48.404237] [wifi1] FWLOG: [55724] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   48.410750] [wifi1] FWLOG: [55724] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   48.417256] [wifi1] FWLOG: [56066] WAL channel change freq=5200, mode=0 flags=0 rx_ok=1 tx_ok=1
[   48.756144] ME Pool succesfully initialized vaddr - d8b00000 paddr - 0
[   48.756144] num_elems = 1424 buf_size - 64 pool_size = 102528
[   48.767450] Enable MCAST_TO_UCAST
[   48.782890]  ieee80211_ioctl_siwmode: imr.ifm_active=66176, new mode=3, valid=1 
[   48.823248]  DEVICE IS DOWN ifname=ath1
[   48.826161]  DEVICE IS DOWN ifname=ath1
[   49.043566] osif_vap_init: Scan in progress.. Cancelling it. vap: 0xd8a80000 
[   49.213220] send_vdev_down_cmd_non_tlv for vap 0 (db65e000)
[   49.217916] ACS failed to derive the channel. So,selecting channel with least BSS 
[   49.225355] random channel is 48 
[   49.228625] ieee80211_acs_scan_report: not populating neighbor list 
[   49.234992] ******** ACS report ******** 
[   49.238946]  Channel | BSS  | minrssi | maxrssi | NF | Ch load | spect load | sec_chan 
[   49.246955] ---------------------------------------------------------------------
[   49.254443]  5180( 36)    4       20        49   -105       1           0          1   
[   49.262395] ieee80211_acs_scan_report: not populating neighbor list 
[   49.268756]  5200( 40)    2        8         9   -106       3           0          1   
[   49.276722] ieee80211_acs_scan_report: not populating neighbor list 
[   49.283062]  5220( 44)   10        8        29   -105       5           0          1   
[   49.291027] ieee80211_acs_scan_report: not populating neighbor list 
[   49.297416]  5240( 48)    0        0         0   -104       1           0          1   
[   49.305568] OL vap_start +
[   49.308051] VDEV START
[   49.310396] OL vap_start -
[   49.313163] ol_ath_vap_set_param: Now supported MGMT RATE is 6000(kbps) and rate code: 0x3
[   49.321488] OL vap_start +
[   49.324043] device ath1 entered promiscuous mode
[   49.324062] VDEV START
[   49.324084] OL vap_start -
[   49.324108] ol_ath_vap_set_param: Now supported MGMT RATE is 6000(kbps) and rate code: 0x3
[   49.344001] br-lan: port 4(ath1) entered forwarding state
[   49.348471] br-lan: port 4(ath1) entered forwarding state
[   49.496994] ol_vdev_start_resp_ev for vap 0 (db65e000)
[   49.501126] send_wmm_update_cmd_non_tlv:
[   49.505225] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   49.512063] send_vdev_up_cmd_non_tlv for vap 0 (db65e000)
[   49.517477] __ieee80211_smart_ant_init: Smart Antenna is not supported 
[   49.524102] ol_vdev_start_resp_ev for vap 1 (db65e000)
[   49.529152] send_wmm_update_cmd_non_tlv:
[   49.533222] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   49.540103] send_vdev_up_cmd_non_tlv for vap 1 (db65e000)
[   49.546030] [wifi1] FWLOG: [56381] WAL channel change freq=5220, mode=0 flags=0 rx_ok=1 tx_ok=1
[   49.555401] [wifi1] FWLOG: [56695] WAL channel change freq=5240, mode=0 flags=0 rx_ok=1 tx_ok=1
[   49.567885] [wifi1] FWLOG: [56836] WAL_DBGID_SECURITY_ENCR_EN (  )
[   49.573045] [wifi1] FWLOG: [56836] WAL_DBGID_SECURITY_MCAST_KEY_SET ( 0x1 )
[   49.580501] [wifi1] FWLOG: [57014] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   49.586564] [wifi1] FWLOG: [57014] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   49.599035] [wifi1] FWLOG: [57109] vap-0 VDEV_MGR_VDEV_START ( 0x1478, 0x2, 0x0, 0x0 )
[   49.605922] [wifi1] FWLOG: [57109] WAL channel change freq=5240, mode=10 flags=0 rx_ok=1 tx_ok=1
[   49.938655] [ol_ath_iw_setcountry][1757] *p=55, *(p+1)=53
[   49.943165] isCountryCodeValid: EEPROM regdomain 0x0
[   49.948004] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x2) flags 0x2150
[   49.955077] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   49.955091] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   49.955102] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   49.955112] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   49.955155] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x4) flags 0xa0
[   49.961872] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x8) flags 0xc0
[   49.968880] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x20) flags 0xd0
[   49.975702] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x40) flags 0x150
[   49.982707] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x800) flags 0x10080
[   49.990848] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x2000) flags 0x20080
[   49.997411] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x4000) flags 0x40080
[   50.004792] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.004807] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.004817] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.004827] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.004855] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.004865] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.004884] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.004895] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.004913] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.004924] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.004934] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.004944] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.004966] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.004977] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.004995] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.005006] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.005022] Add VHT80 channel: 5210
[   50.008222] Add VHT80 channel: 5290
[   50.011692] Add VHT80 channel: 5530
[   50.015184] Add VHT80 channel: 5610
[   50.018638] Add VHT80 channel: 5690
[   50.022106] Add VHT80 channel: 5775
[   50.025671] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.025686] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.025696] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.025723] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.025747] Skipping VHT80 channel 5825
[   50.029417] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5290
[   50.029430] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5210
[   50.029439] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5610
[   50.029449] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5530
[   50.029461] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.029472] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.029482] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.029492] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.029516] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5530
[   50.029526] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5210
[   50.029535] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5610
[   50.029544] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5210
[   50.029556] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5690
[   50.029565] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5210
[   50.029574] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5775
[   50.029583] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5210
[   50.029592] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5530
[   50.029601] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5290
[   50.029611] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5610
[   50.029620] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5290
[   50.029629] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5690
[   50.029639] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5290
[   50.029648] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5775
[   50.029658] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5290
[   50.029668] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5690
[   50.029677] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5530
[   50.029687] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5775
[   50.029696] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5530
[   50.029706] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5775
[   50.029715] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5610
[   50.029725] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5775
[   50.029734] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5690
[   50.029746] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.029756] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.029767] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.029777] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.045997] isCountryCodeValid: EEPROM regdomain 0x0
[   50.049977] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x2) flags 0x2150
[   50.057081] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.057097] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.057108] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.057118] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.057147] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x4) flags 0xa0
[   50.064013] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x8) flags 0xc0
[   50.070707] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x20) flags 0xd0
[   50.077664] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x40) flags 0x150
[   50.084730] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x800) flags 0x10080
[   50.092193] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x2000) flags 0x20080
[   50.099373] ol_regdmn_init_channels: !avail mode 0x7f9001 (0x4000) flags 0x40080
[   50.109854] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.109874] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.109886] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.109897] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.109926] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.109944] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.109972] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.109994] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.110019] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.110029] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.110040] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.110051] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.110072] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.110083] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.110103] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.110117] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.110134] Add VHT80 channel: 5210
[   50.112623] Add VHT80 channel: 5290
[   50.116174] Add VHT80 channel: 5530
[   50.119564] Add VHT80 channel: 5610
[   50.123199] Add VHT80 channel: 5690
[   50.126497] Add VHT80 channel: 5775
[   50.129963] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.129977] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.129987] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.129998] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.130021] Skipping VHT80 channel 5825
[   50.133823] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5290
[   50.133855] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5210
[   50.133883] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5610
[   50.133906] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5530
[   50.133920] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.133930] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.133941] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.133951] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.133978] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5530
[   50.133988] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5210
[   50.133998] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5610
[   50.134007] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5210
[   50.134016] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5690
[   50.134025] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5210
[   50.134035] Add VHT160/VHT80_80 pri80 and sec80 centers: 5210,5775
[   50.134044] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5210
[   50.134053] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5530
[   50.134062] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5290
[   50.134071] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5610
[   50.134080] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5290
[   50.134090] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5690
[   50.134099] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5290
[   50.134108] Add VHT160/VHT80_80 pri80 and sec80 centers: 5290,5775
[   50.134118] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5290
[   50.134127] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5690
[   50.134136] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5530
[   50.134146] Add VHT160/VHT80_80 pri80 and sec80 centers: 5530,5775
[   50.134155] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5530
[   50.134165] Add VHT160/VHT80_80 pri80 and sec80 centers: 5610,5775
[   50.134174] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5610
[   50.134205] Add VHT160/VHT80_80 pri80 and sec80 centers: 5690,5775
[   50.134233] Add VHT160/VHT80_80 pri80 and sec80 centers: 5775,5690
[   50.134262] ol_regdmn_init_channels: c 5180 out of range [5490..5850]
[   50.134291] ol_regdmn_init_channels: c 5200 out of range [5490..5850]
[   50.134319] ol_regdmn_init_channels: c 5220 out of range [5490..5850]
[   50.134348] ol_regdmn_init_channels: c 5240 out of range [5490..5850]
[   50.209991] set TXBF_SND_PERIOD: value 100 wmi_status 0
[   50.275206]  Disconnect_timeout value entered:10 
[   50.290947]  reconfiguration_timeout value entered:60 
[   50.346006] [wifi2] FWLOG: [50903] UNKNOWN 22:55 ( 0x3a, 0xa10, 0x160, 0x10, 0x0 )
[   50.352544] [wifi2] FWLOG: [51010] UNKNOWN 22:55 ( 0x16, 0xa10, 0x810, 0x10, 0x0 )
[   50.496462] [wifi1] FWLOG: [57300] UNKNOWN 14:20 ( 0x0 )
[   50.500744] [wifi1] FWLOG: [57301] vap-1 VDEV_MGR_VDEV_START ( 0x1478, 0x2, 0x0, 0x0 )
[   50.523971] [wifi1] FWLOG: [57322] VDEV_MGR_HP_START_TIME ( 0x0, 0x1478, 0xc35001 )
[   50.531606] [wifi1] FWLOG: [57322] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x1 )
[   50.538115] [wifi1] FWLOG: [57322] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   50.549807] [wifi1] FWLOG: [57322] VDEV_MGR_AP_TBTT_CONFIG ( 0x0, 0x1478
[   50.555794] wlan_vap_create : enter. devhandle=0xd9e804c0, opmode=IEEE80211_M_HOSTAP, flags=0x1
[   50.555860] send_vdev_create_cmd_non_tlv: ID = 0 Type = 1, Subtype = 0 VAP Addr = cc:32:e5:3a:29:be:
[   50.555967] ieee80211_mbo_vattach:MBO Initialized 
[   50.555973] ieee80211_oce_vattach: OCE Initialized 
[   50.556202] wlan_vap_create : exit. devhandle=0xd9e804c0, vap=0xd8b60000, opmode=IEEE80211_M_HOSTAP, flags=0x1.
[   50.556211] __ieee80211_smart_ant_init: Smart Antenna is not supported 
[   50.556225] Enabling TX checksum bit for the vap ath22 features 4000 
[   50.556230] Enabling SG bit for the vap ath22 features 4000 
[   50.556234] Enabling SG bit for the vap ath22 features 4000 
[   50.556239] Enabling TSO bit for the vap ath22 features 4000 
[   50.556243] Enabling LRO bit for the vap ath22 features 4000 
[   50.556251] VAP device ath22 created osifp: (dc2584c0) os_if: (d8b60000)
[   50.636525] , 0x0, 0x0 )
[   50.640845] [wifi1] FWLOG: [57322] UNKNOWN 14:20 ( 0x0 )
[   50.646138] [wifi1] FWLOG: [57354] VDEV_MGR_HP_START_TIME ( 0x0, 0x1478, 0xc4e001 )
[   50.651632] [wifi1] FWLOG: [57354] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x1 )
[   50.651653] [wifi1] FWLOG: [57354] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   50.651668] [wifi1] FWLOG: [57354] VDEV_MGR_AP_TBTT_CONFIG ( 0x1, 0x1478, 0x0, 0x0 )
[   50.686487] siwfreq
[   50.687589] Set freq vap 0 stop send + d8b60000
[   50.692281] Set freq vap 0 stop send -d8b60000
[   50.722814] Set wait done --d8b60000
[   50.894964] Setting Max Stations:64
[   50.946246]  
[   50.946246]  DES SSID SET= 
[   50.962208] vap-0(ath22):set SIOC80211NWID, 16 characters
[   50.966828]  
[   50.966828]  DES SSID SET=zEQQohyXxaOcCULy 
[   51.383050]  ieee80211_ioctl_siwmode: imr.ifm_active=66176, new mode=3, valid=1 
[   51.433470]  DEVICE IS DOWN ifname=ath22
[   51.436527]  DEVICE IS DOWN ifname=ath22
[   51.693219] Sending SCAN START cmd
[   51.756700] wlan_vap_create : enter. devhandle=0xd9e804c0, opmode=IEEE80211_M_HOSTAP, flags=0x1
[   51.764510] send_vdev_create_cmd_non_tlv: ID = 1 Type = 1, Subtype = 0 VAP Addr = d2:32:e5:3a:29:be:
[   51.773934] ieee80211_mbo_vattach:MBO Initialized 
[   51.778272] ieee80211_oce_vattach: OCE Initialized 
[   51.783420] wlan_vap_create : exit. devhandle=0xd9e804c0, vap=0xd8b90000, opmode=IEEE80211_M_HOSTAP, flags=0x1.
[   51.793343] __ieee80211_smart_ant_init: Smart Antenna is not supported 
[   51.799842] Enabling TX checksum bit for the vap ath2 features 4000 
[   51.806160] Enabling SG bit for the vap ath2 features 4000 
[   51.811686] Enabling SG bit for the vap ath2 features 4000 
[   51.817256] Enabling TSO bit for the vap ath2 features 4000 
[   51.822907] Enabling LRO bit for the vap ath2 features 4000 
[   51.828800] VAP device ath2 created osifp: (dc25bcc0) os_if: (d8b90000)
[   51.863349] siwfreq
[   51.864441] Set freq vap 0 stop send + d8b60000
[   51.869048] ol_scan_unregister_event_handler: Failed to unregister evhandler=bf6171d0 arg=d8fc0000
[   51.869048] 
[   51.879890] osif_vap_acs_cancel: Scan in progress.. Cancelling it vap: 0xd8b60000
[   51.887937] send_vdev_down_cmd_non_tlv for vap 0 (da0f4000)
[   51.892656] Set freq vap 0 stop send -d8b60000
[   51.922847] Set wait done --d8b60000
[   51.925426] Set freq vap 1 stop send + d8b90000
[   51.930284] Set freq vap 1 stop send -d8b90000
[   51.962827] Set wait done --d8b90000
[   51.993140] Sending SCAN START cmd
[   52.051257] ol_scan_unregister_event_handler: Failed to unregister evhandler=bf6171d0 arg=d8fc0000
[   52.051257] 
[   52.060753] osif_vap_init: Scan in progress.. Cancelling it. vap: 0xd8b60000 
[   52.060761] Ebtables v2.0 unregistered
[   52.072452] send_vdev_down_cmd_non_tlv for vap 0 (da0f4000)
[   52.103232] Sending SCAN START cmd
[   52.226858] Setting Max Stations:64
[   52.281064]  
[   52.281064]  DES SSID SET= 
[   52.300253] vap-1(ath2):set SIOC80211NWID, 4 characters
[   52.304680]  
[   52.304680]  DES SSID SET=test 
[   52.346274] [wifi2] FWLOG: [52575] WAL_DBGID_SECURITY_ENCR_EN (  )
[   52.351427] [wifi2] FWLOG: [52575] WAL_DBGID_SECURITY_MCAST_KEY_SET ( 0x1 )
[   52.358375] [wifi2] FWLOG: [52609] WAL channel change freq=5745, mode=0 flags=0 rx_ok=1 tx_ok=1
[   52.367425] [wifi2] FWLOG: [52810] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   52.375742] [wifi2] FWLOG: [52810] RESMGR_OCS_GEN_PERIODIC_NOA ( 
[   52.378772] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   52.389045] 0x0 )
[   52.393201] [wifi2] FWLOG: [52999] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   52.399436] [wifi2] FWLOG: [52999] RESMGR_OCS_GEN_PERIODIC_NOA ( 
[   52.403506] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   52.412736] 0x0 )
[   52.424853] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   52.443288] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   52.449351] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   52.962936]  ieee80211_ioctl_siwmode: imr.ifm_active=66176, new mode=3, valid=1 
[   52.993403]  DEVICE IS DOWN ifname=ath2
[   52.996333]  DEVICE IS DOWN ifname=ath2
[   53.005587] ME Pool succesfully initialized vaddr - d8400000 paddr - 0
[   53.005587] num_elems = 1424 buf_size - 64 pool_size = 102528
[   53.016988] Enable MCAST_TO_UCAST
[   53.273708] osif_vap_init: Scan in progress.. Cancelling it. vap: 0xd8b90000 
[   53.347994] [wifi2] FWLOG: [53344] WAL channel change freq=5765, mode=0 flags=0 rx_ok=1 tx_ok=1
[   53.355888] [wifi2] FWLOG: [53658] WAL channel change freq=5785, mode=0 flags=0 rx_ok=1 tx_ok=1
[   53.364712] [wifi2] FWLOG: [53972] WAL channel change freq=5805, mode=0 flags=0 rx_ok=1 tx_ok=1
[   53.373279] [wifi2] FWLOG: [54224] WAL_DBGID_SECURITY_ENCR_EN (  )
[   53.379189] [wifi2] FWLOG: [54224] WAL_DBGID_SECURITY_MCAST_KEY_SET ( 0x1 )
[   53.386135] [wifi2] FWLOG: [54286] WAL channel change freq=5825, mode=0 flags=0 rx_ok=1 tx_ok=1
[   53.614534] device ath2 entered promiscuous mode
[   53.621150] br-lan: port 5(ath2) entered forwarding state
[   53.625689] br-lan: port 5(ath2) entered forwarding state
[   53.640518] send_vdev_down_cmd_non_tlv for vap 0 (da0f4000)
[   53.645310] ACS failed to derive the channel. So,selecting channel with least BSS 
[   53.652638] random channel is 149 
[   53.656079] ieee80211_acs_scan_report: not populating neighbor list 
[   53.662349] ******** ACS report ******** 
[   53.666385]  Channel | BSS  | minrssi | maxrssi | NF | Ch load | spect load | sec_chan 
[   53.674374] ---------------------------------------------------------------------
[   53.681806]  5745(149)    1       20        20   -101       2           0          1   
[   53.689832] ieee80211_acs_scan_report: not populating neighbor list 
[   53.696177]  5765(153)    2        8         9   -102      10           0          1   
[   53.704172] ieee80211_acs_scan_report: not populating neighbor list 
[   53.710445]  5785(157)   11        7        57   -102       9           0          1   
[   53.718489] ieee80211_acs_scan_report: not populating neighbor list 
[   53.724818]  5805(161)    3        6        12   -103       9           0          1   
[   53.732759] ieee80211_acs_scan_report: not populating neighbor list 
[   53.739151]  5825(165)    0        0         0   -103       1           0          0   
[   53.747346] OL vap_start +
[   53.749797] VDEV START
[   53.752139] OL vap_start -
[   53.754917] ol_ath_vap_set_param: Now supported MGMT RATE is 6000(kbps) and rate code: 0x3
[   53.763306] OL vap_start +
[   53.765750] VDEV START
[   53.768101] OL vap_start -
[   53.770810] ol_ath_vap_set_param: Now supported MGMT RATE is 6000(kbps) and rate code: 0x3
[   53.963497] ol_vdev_start_resp_ev for vap 0 (da0f4000)
[   53.967646] send_wmm_update_cmd_non_tlv:
[   53.971763] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   53.978670] send_vdev_up_cmd_non_tlv for vap 0 (da0f4000)
[   53.984026] __ieee80211_smart_ant_init: Smart Antenna is not supported 
[   53.990610] ol_vdev_start_resp_ev for vap 1 (da0f4000)
[   53.995749] send_wmm_update_cmd_non_tlv:
[   53.999749] su bfee 1 mu bfee 0 su bfer 1 mu bfer 1 impl bf 0 sounding dim 1
[   54.006706] send_vdev_up_cmd_non_tlv for vap 1 (da0f4000)
[   54.348441] [wifi2] FWLOG: [54605] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   54.354023] [wifi2] FWLOG: [54605] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   54.362978] [wifi2] FWLOG: [54714] vap-0 VDEV_MGR_VDEV_START ( 0x1671, 0x2, 0x0, 0x0 )
[   54.370418] [wifi2] FWLOG: [54714] WAL channel change freq=5745, mode=10 flags=0 rx_ok=1 tx_ok=1
[   54.380577] [wifi2] FWLOG: [54930] UNKNOWN 14:20 ( 0x0 )
[   54.389787] [wifi2] FWLOG: [54931] vap-1 VDEV_MGR_VDEV_START ( 0x1671, 0x2, 0x0, 0x0 )
[   54.397681] [wifi2] FWLOG: [54952] VDEV_MGR_HP_START_TIME ( 0x0, 0x1671, 0xccb000 )
[   54.405434] [wifi2] FWLOG: [54952] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x1 )
[   54.411828] [wifi2] FWLOG: [54952] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   54.418339] [wifi2] FWLOG: [54952] VDEV_MGR_AP_TBTT_CONFIG ( 0x0, 0x1671, 0x0, 0x0 )
[   54.426062] [wifi2] FWLOG: [54952] UNKNOWN 14:20 ( 0x0 )
[   54.431350] [wifi2] FWLOG: [54980] VDEV_MGR_HP_START_TIME ( 0x0, 0x1671, 0xccb001 )
[   54.438995] [wifi2] FWLOG: [54980] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x1 )
[   54.445506] [wifi2] FWLOG: [54980] RESMGR_OCS_GEN_PERIODIC_NOA ( 0x0 )
[   54.452013] [wifi2] FWLOG: [54980] VDEV_MGR_AP_TBTT_CONFIG ( 0x1, 0x1671, 0x0, 0x0 )
[   54.929668] device ath12.1 entered promiscuous mode
[   54.948557] device ath12 entered promiscuous mode
[   54.955166] br-lan: port 6(ath12.1) entered forwarding state
[   54.960115] br-lan: port 6(ath12.1) entered forwarding state
[   55.119965] device ath22.1 entered promiscuous mode
[   55.136016] device ath22 entered promiscuous mode
[   55.142212] br-lan: port 7(ath22.1) entered forwarding state
[   55.146970] br-lan: port 7(ath22.1) entered forwarding state
[   55.319785] device ath02.1 entered promiscuous mode
[   55.333461] device ath02 entered promiscuous mode
[   55.339872] br-lan: port 8(ath02.1) entered forwarding state
[   55.344660] br-lan: port 8(ath02.1) entered forwarding state
[   55.722697] device ath12.2 entered promiscuous mode
[   55.741834] br-lan: port 9(ath12.2) entered forwarding state
[   55.746619] br-lan: port 9(ath12.2) entered forwarding state
[   55.893341] IPv6: ADDRCONF(NETDEV_CHANGE): ath12.2: link becomes ready
[   55.949737] device ath22.2 entered promiscuous mode
[   55.962337] br-lan: port 10(ath22.2) entered forwarding state
[   55.967213] br-lan: port 10(ath22.2) entered forwarding state
[   56.093745] ivalue value:
[   56.095374] bind_divece_num:1
[   56.212893] device ath02.2 entered promiscuous mode
[   56.237401] br-lan: port 11(ath02.2) entered forwarding state
[   56.242261] br-lan: port 11(ath02.2) entered forwarding state
[   56.724601] device eth0 left promiscuous mode
[   56.732681] br-lan: port 1(eth0) entered disabled state
[   56.806068] device eth0 entered promiscuous mode
[   56.892858] IPv6: ADDRCONF(NETDEV_CHANGE): ath22.2: link becomes ready
[   56.900372] IPv6: ADDRCONF(NETDEV_CHANGE): ath02.2: link becomes ready
[   57.068622] device eth1 left promiscuous mode
[   57.076189] br-lan: port 2(eth1) entered disabled state
[   57.114432] tipc: Started in network mode
[   57.115964] device eth1 entered promiscuous mode
[   57.122057] tipc: Own node address <75.1193.1>, network identity 4711
[   57.143381] tipc: Enabled bearer <deco:br-lan:1>, discovery domain <75.1193.0>, priority 10
[   60.151844] Not a Hy-Fi device, or device not found: br-iptv
[   60.157283] Not a Hy-Fi device, or device not found: br-iptv
[   61.254362] Sending SCAN START cmd
[   62.349733] [wifi2] FWLOG: [62870] WAL channel change freq=5765, mode=0 flags=0 rx_ok=1 tx_ok=1
[   62.357936] [wifi2] FWLOG: [63183] WAL channel change freq=5745, mode=10 flags=0 rx_ok=1 tx_ok=1
[   62.372578] [wifi2] FWLOG: [63288] WAL channel change freq=5785, mode=0 flags=0 rx_ok=1 tx_ok=1
[   63.349818] [wifi2] FWLOG: [63601] WAL channel change freq=5745, mode=10 flags=0 rx_ok=1 tx_ok=1
[   63.358872] [wifi2] FWLOG: [63706] WAL channel change freq=5805, mode=0 flags=0 rx_ok=1 tx_ok=1
[   63.367904] [wifi2] FWLOG: [64020] WAL channel change freq=5745, mode=10 flags=0 rx_ok=1 tx_ok=1
[   63.388587] [wifi2] FWLOG: [64125] WAL channel change freq=5825, mode=0 flags=0 rx_ok=1 tx_ok=1
[   63.409968] [wifi2] FWLOG: [64438] WAL channel change freq=5745, mode=10 flags=0 rx_ok=1 tx_ok=1
[   63.417602] [ath0] Band steering events being sent to PID:7583
[   63.417621] [ath1] Band steering events being sent to PID:7583
[   63.420111] [ath0] Band steering events being sent to PID:7583
[   63.420126] [ath1] Band steering events being sent to PID:7583
[   63.450738] [ath0] Band steering events being sent to PID:7583
[   63.455813] [ath1] Band steering events being sent to PID:7583
[   64.286583] work mode change to :AP
[   64.286583] 
[   64.297552] get dev num:2
[   64.299186] statistics: SET_STA_DEVICE dev_name=eth0
[   64.304151] statistics: SET_STA_DEVICE dev_name=eth1
[   64.309305] backhaul sta dev num:2
[   65.017365] [ath0] Band steering events being sent to PID:8044
[   65.024825] [ath1] Band steering events being sent to PID:8044
[   65.032362] [ath0] Band steering events being sent to PID:8044
[   65.052992] [ath1] Band steering events being sent to PID:8044
[   65.098661] [ath0] Band steering events being sent to PID:8044
[   65.115890] [ath1] Band steering events being sent to PID:8044
[   66.898068] mode:0
[  186.643316] IPv6: ADDRCONF(NETDEV_CHANGE): eth1: link becomes ready
[  186.648852] br-wan: port 2(eth1) entered forwarding state
[  186.654325] br-wan: port 2(eth1) entered forwarding state
[  186.666140] IPv6: ADDRCONF(NETDEV_CHANGE): br-wan: link becomes ready
[  186.858481] br-wan: port 2(eth1) entered disabled state
[  186.870581] br-wan: port 2(eth1) entered forwarding state
[  186.875286] br-wan: port 2(eth1) entered forwarding state
[  194.856823] device eth0 left promiscuous mode
[  194.863579] br-wan: port 1(eth0) entered disabled state
[  194.875107] device eth0 entered promiscuous mode
[  195.697001] device eth0.591 entered promiscuous mode
[  195.747736] IPv6: ADDRCONF(NETDEV_UP): eth0.591: link is not ready
[  200.138339] Not a Hy-Fi device, or device not found: br-iptv
[  200.143541] Not a Hy-Fi device, or device not found: br-iptv
[  206.423673] [wifi1] FWLOG: [217329] RATE: ChainMask 3, peer_mac 32:ac, phymode 10, ni_flags 0x06213006, vht_mcs_set 0xfffa, ht_mcs_set 0xffff, legacy_rate_set 0x0ff0
[  206.437608] [wifi1] FWLOG: [217330] WAL_DBGID_PEER_EXT_STATS ( 0x8 )
[  206.443751] [wifi1] FWLOG: [217330] RTT_REPORT ( 0x2804, 0x3, 0x479, 0x0, 0x9 )
[  206.451042] [wifi1] FWLOG: [217332] WAL_DBGID_SECURITY_ENCR_EN (  )
[  206.457295] [wifi1] FWLOG: [217332] WAL_DBGID_SECURITY_MCAST_KEY_SET ( 0x1 )
[  206.464327] [wifi1] FWLOG: [217359] WAL_DBGID_SECURITY_UCAST_KEY_SET ( 0x32ac, 0x0 )
[  206.472050] [wifi1] FWLOG: [217359] WAL_DBGID_SECURITY_ENCR_EN (  )
[  206.478300] [wifi1] FWLOG: [217359] WAL_DBGID_SECURITY_ALLOW_DATA ( 0x43f44c )
[  207.423503] [wifi1] FWLOG: [218188] WAL_DBGID_TX_BA_SETUP ( 0x43f44c, 0x32ac0006, 0x2, 0x40, 0x1 )
[  207.431439] [wifi1] FWLOG: [218190] RATE: ChainMask 3, peer_mac 32:ac, phymode 10, ni_flags 0x06213006, vht_mcs_set 0xfffa, ht_mcs_set 0xffff, legacy_rate_set 0x0ff0
[  209.422579] [wifi1] FWLOG: [221121] WAL_DBGID_TX_BA_SETUP ( 0x43f44c, 0x32ac0000, 0x0, 0x40, 0x1 )
[  229.414156] [wifi1] FWLOG: [240885] RATE: ChainMask 3, peer_mac 0:bd, phymode 10, ni_flags 0x06213006, vht_mcs_set 0xfffa, ht_mcs_set 0xffff, legacy_rate_set 0x0ff0
[  229.428368] [wifi1] FWLOG: [240886] WAL_DBGID_PEER_EXT_STATS ( 0x8 )
[  229.434173] [wifi1] FWLOG: [240886] RTT_REPORT ( 0x2804, 0x3, 0x479, 0x0, 0x9 )
[  229.441461] [wifi1] FWLOG: [240923] WAL_DBGID_SECURITY_UCAST_KEY_SET ( 0xbd, 0x0 )
[  229.449016] [wifi1] FWLOG: [240923] WAL_DBGID_SECURITY_ENCR_EN (  )
[  229.455370] [wifi1] FWLOG: [240923] WAL_DBGID_SECURITY_ALLOW_DATA ( 0x43f2f4 )
[  229.462485] [wifi1] FWLOG: [241540] WAL_DBGID_TX_BA_SETUP ( 0x43f2f4, 0xbd0000, 0x0, 0x40, 0x1 )
[  229.471251] [wifi1] FWLOG: [241542] RATE: ChainMask 3, peer_mac 0:bd, phymode 10, ni_flags 0x06213006, vht_mcs_set 0xfffa, ht_mcs_set 0xffff, legacy_rate_set 0x0ff0
[  229.488016] [wifi1] FWLOG: [241600] WAL_DBGID_TX_BA_SETUP ( 0x43f2f4, 0xbd0006, 0x2, 0x40, 0x1 )
[  233.412681] [wifi1] FWLOG: [244997] WAL_DBGID_TX_BA_SETUP ( 0x43f2f4, 0xbd0003, 0x0, 0x40, 0x1 )
[  304.643436] br-wan: port 2(eth1) entered disabled state
[  305.510744] IPv6: ADDRCONF(NETDEV_UP): br-wan: link is not ready
[  306.641495] br-lan: port 1(eth0) entered disabled state
[  307.266362] br-lan: port 2(eth0.591) entered disabled state
[  307.276587] device eth0.591 left promiscuous mode
[  307.280635] br-lan: port 2(eth0.591) entered disabled state
[  311.728751] Not a Hy-Fi device, or device not found: br-iptv
[  311.734158] Not a Hy-Fi device, or device not found: br-iptv
[  370.352308] [wifi1] FWLOG: [385944] WAL_DBGID_SECURITY_UCAST_KEY_SET ( 0x32ac, 0x0 )
[  370.359024] [wifi1] FWLOG: [385944] WAL_DBGID_SECURITY_ENCR_EN (  )
[  370.365288] [wifi1] FWLOG: [385944] WAL_DBGID_SECURITY_ALLOW_DATA ( 0x43f44c )
[  371.351907] [wifi1] FWLOG: [386268] RATE: ChainMask 3, peer_mac 32:ac, phymode 10, ni_flags 0x06213006, vht_mcs_set 0xfffa, ht_mcs_set 0xffff, legacy_rate_set 0x0ff0
[  371.365694] [wifi1] FWLOG: [386269] WAL_DBGID_PEER_EXT_STATS ( 0x8 )
[  371.371992] [wifi1] FWLOG: [386269] RTT_REPORT ( 0x2804, 0x3, 0x479, 0x0, 0x9 )
[  371.379295] [wifi1] FWLOG: [386298] WAL_DBGID_SECURITY_UCAST_KEY_SET ( 0x32ac, 0x0 )
[  371.387011] [wifi1] FWLOG: [386298] WAL_DBGID_SECURITY_ENCR_EN (  )
[  371.393272] [wifi1] FWLOG: [386298] WAL_DBGID_SECURITY_ALLOW_DATA ( 0x43f44c )
[  371.400464] [wifi1] FWLOG: [386411] WAL_DBGID_TX_BA_SETUP ( 0x43f44c, 0x32ac0006, 0x2, 0x40, 0x1 )
[  371.409413] [wifi1] FWLOG: [386413] RATE: ChainMask 3, peer_mac 32:ac, phymode 10, ni_flags 0x06213006, vht_mcs_set 0xfffa, ht_mcs_set 0xffff, legacy_rate_set 0x0ff0
[  374.350275] [wifi1] FWLOG: [389502] WAL_DBGID_TX_BA_SETUP ( 0x43f44c, 0x32ac0000, 0x0, 0x40, 0x1 )
[  385.345630] [wifi1] FWLOG: [400670] WAL_DBGID_SECURITY_UCAST_KEY_SET ( 0xbd, 0x0 )
[  385.352172] [wifi1] FWLOG: [400670] WAL_DBGID_SECURITY_ENCR_EN (  )
[  385.358424] [wifi1] FWLOG: [400670] WAL_DBGID_SECURITY_ALLOW_DATA ( 0x43f2f4 )
[  739.724183] ess_edma c080000.edma: eth0: GMAC Link is up with phy_speed=1000
[  739.730322] IPv6: ADDRCONF(NETDEV_CHANGE): eth0: link becomes ready
[  739.737240] br-wan: port 1(eth0) entered forwarding state
[  739.742140] br-wan: port 1(eth0) entered forwarding state
[  739.752016] IPv6: ADDRCONF(NETDEV_CHANGE): br-wan: link becomes ready
[  740.536001] br-wan: port 1(eth0) entered disabled state
[  740.542282] br-wan: port 1(eth0) entered forwarding state
[  740.547035] br-wan: port 1(eth0) entered forwarding state
[  743.933291] ess_edma c080000.edma: IPv6 not supported
[  745.179037] [wifi1] FWLOG: [769675] WAL_DBGID_SECURITY_UCAST_KEY_SET ( 0x32ac, 0x0 )
[  745.185772] [wifi1] FWLOG: [769675] WAL_DBGID_SECURITY_ENCR_EN (  )
[  745.192041] [wifi1] FWLOG: [769675] WAL_DBGID_SECURITY_ALLOW_DATA ( 0x43f44c )
[  813.744198] ess_edma c080000.edma: eth0: GMAC Link is down
[  813.748954] br-wan: port 1(eth0) entered disabled state
[  815.058260] IPv6: ADDRCONF(NETDEV_UP): br-wan: link is not ready
[  818.683474] br-wan: port 2(eth1) entered forwarding state
[  818.688151] br-wan: port 2(eth1) entered forwarding state
[  818.699281] IPv6: ADDRCONF(NETDEV_CHANGE): br-wan: link becomes ready
[  819.638597] br-wan: port 2(eth1) entered disabled state
[  819.646203] br-wan: port 2(eth1) entered forwarding state
[  819.650870] br-wan: port 2(eth1) entered forwarding state
[  821.096230] ess_edma c080000.edma: IPv6 not supported
[  854.683594] br-wan: port 2(eth1) entered disabled state
[  855.025486] IPv6: ADDRCONF(NETDEV_UP): br-wan: link is not ready
[ 1006.683573] br-wan: port 2(eth1) entered forwarding state
[ 1006.688269] br-wan: port 2(eth1) entered forwarding state
[ 1006.706719] IPv6: ADDRCONF(NETDEV_CHANGE): br-wan: link becomes ready
[ 1006.854229] br-wan: port 2(eth1) entered disabled state
[ 1006.860407] br-wan: port 2(eth1) entered forwarding state
[ 1006.865157] br-wan: port 2(eth1) entered forwarding state
[ 1076.683721] br-wan: port 2(eth1) entered disabled state
[ 1077.308611] IPv6: ADDRCONF(NETDEV_UP): br-wan: link is not ready
[ 1177.977384] [wifi1] FWLOG: [1213297] RATE: ChainMask 3, peer_mac 32:ac, phymode 10, ni_flags 0x06213006, vht_mcs_set 0xfffa, ht_mcs_set 0xffff, legacy_rate_set 0x0ff0
[ 1177.991770] [wifi1] FWLOG: [1213298] WAL_DBGID_PEER_EXT_STATS ( 0x8 )
[ 1177.997663] [wifi1] FWLOG: [1213298] RTT_REPORT ( 0x2804, 0x3, 0x479, 0x0, 0x9 )
[ 1178.005039] [wifi1] FWLOG: [1213334] WAL_DBGID_SECURITY_UCAST_KEY_SET ( 0x32ac, 0x0 )
[ 1178.012850] [wifi1] FWLOG: [1213334] WAL_DBGID_SECURITY_ENCR_EN (  )
[ 1178.019187] [wifi1] FWLOG: [1213334] WAL_DBGID_SECURITY_ALLOW_DATA ( 0x43f44c )
[ 1178.026481] [wifi1] FWLOG: [1213496] WAL_DBGID_TX_BA_SETUP ( 0x43f44c, 0x32ac0006, 0x2, 0x40, 0x1 )
[ 1178.035510] [wifi1] FWLOG: [1213498] RATE: ChainMask 3, peer_mac 32:ac, phymode 10, ni_flags 0x06213006, vht_mcs_set 0xfffa, ht_mcs_set 0xffff, legacy_rate_set 0x0ff0
[ 1183.974239] [wifi1] FWLOG: [1219603] WAL_DBGID_TX_BA_SETUP ( 0x43f44c, 0x32ac0000, 0x0, 0x40, 0x1 )