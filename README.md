<b>Router WR841n_v9</b>

<b>v9 only</b>
<p>
flash 16MB only<p>
<p>
W25Q128FWSIG is used for modification<p>

1.Grab mtd0 & mtd4 partitions from your current openwrt installed flash<p>
2.Prepare empty 16mb bin in Hex editor<p>
3.Insert mtd0 to the begining<p>
4.Insert (replace) to the begining u-boot_mod__tp-link_tl-wr841n_v9__20180204__git_master-4fbf43bf.bin<p>
5.Burn your rom into the new 16MB flash W25Q128FWSIG<p>
6.Replace flash and boot<p>
7.Disconnect wan cable<p>
8.Get to the 192.168.1.1 in browser. If there no connection - write down manualy in you adapter ipv4 settings:<p>

192.168.1.X<p>
255.255.255.0<p>
192.168.1.1<p>
<p>
192.168.1.1<p>
9.Navigate to 192.168.1.1/art.html. Select mtd4 and burn<p>
10.Navigate to 192.168.1.1 and select one of the builds from "bin" folder. Burn - connect - Enjoy.<p>
<p>
"u-boot_mod__tp-link_tl-wr841n_v9__20180204__git_master-4fbf43bf.bin"<p>
16 MB emptypepe2k u-boot_mod<p>
<p>
"openwrt-ar71xx-generic-tl-wr841n-v9-squashfs-factory-chaos_calmer.bin"<p>
Model	TP-Link TL-WR841N/ND v9<p>
Firmware Version	OpenWrt Chaos Calmer 15.05.1 r49617 / LuCI for-15.05 branch (git-18.021.57137-5fa2132)<p>