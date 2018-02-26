Router v9 only

flash 16MB only

W25Q128FWSIG is used for modification

1.Grab mtd0 & mtd4 partitions from your current openwrt installed flash
2.Prepare empty 16mb bin in Hex editor
3.Insert mtd0 to the begining
4.Insert (replace) to the begining u-boot_mod__tp-link_tl-wr841n_v9__20180204__git_master-4fbf43bf.bin
5.Burn your rom into the new 16MB flash W25Q128FWSIG
6.Replace flash and boot
7.Disconnect wan cable
8.Get to the 192.168.1.1 in browser. If there no connection - write down manualy in you adapter ipv4 settings:

192.168.1.X
255.255.255.0
192.168.1.1

192.168.1.1
9.Navigate to 192.168.1.1/art.html. Select mtd4 and burn
10.Navigate to 192.168.1.1 and select one of the builds from "bin" folder. Burn - connect - Enjoy.

"u-boot_mod__tp-link_tl-wr841n_v9__20180204__git_master-4fbf43bf.bin"
16 MB emptypepe2k u-boot_mod

"openwrt-ar71xx-generic-tl-wr841n-v9-squashfs-factory-chaos_calmer.bin"
Model	TP-Link TL-WR841N/ND v9
Firmware Version	OpenWrt Chaos Calmer 15.05.1 r49617 / LuCI for-15.05 branch (git-18.021.57137-5fa2132)