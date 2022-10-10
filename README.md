# Mitrastart_vivo_GPT-2741GNAC-N1-SV

- Kernel: `Linux MitraStar 2.6.36 #1 SMP Mon Apr 18 23:24:52 CST 2022 mips GNU/Linux`
- Default route panel: `http://192.168.15.1/padrao`.

- enable sshd: `http://192.168.15.1/cgi-bin/ping.cgi` ping: `$(sshd; echo '192.168.15.1')`.
- Root user: ? avaible, so not acessibl

- ls /:

```
drwxrwxr-x   17 support  root           295 Apr 18 15:43 .
drwxrwxr-x   17 support  root           295 Apr 18 15:43 ..
drwxr-xr-x    1 support  root          2048 Aug  1  2016 app
drwxrwxr-x    2 support  root          1027 Apr 18 15:43 bin
drwxr-xr-x    1 support  root          2048 Aug  1  2016 bosa
drwxr-xr-x    1 support  root          2048 Aug  1  2016 bosabackup
drwxr-xr-x    1 support  root          2048 Aug  1  2016 data
drwxrwxr-x    5 support  root          1212 Apr 18 15:43 dev
lrwxrwxrwx    1 support  root             8 Apr 18 15:43 etc -> /tmp/etc
drwxrwxr-x    2 support  root             3 Apr 18 15:43 fwbuffer
drwxrwxr-x    7 support  root          5687 Apr 18 15:43 lib
lrwxrwxrwx    1 support  root            11 Apr 18 15:43 linuxrc -> bin/busybox
drwxrwxrwx    5 support  root           246 Apr 18 15:43 mini_httpdroot
dr-xr-xr-x  111 support  root             0 Jan  1  1970 proc
drwxrwxr-x    2 support  root           442 Apr 18 15:43 sbin
drwxrwxr-x    2 support  root             3 Apr 18 15:43 sys
drwxr-xr-x    8 support  root             0 Oct 10 14:57 tmp
drwxrwxr-x    4 support  root           172 Apr 18 15:43 userfs
drwxrwxr-x    8 support  root           112 Apr 18 15:43 usr
lrwxrwxrwx    1 support  root             8 Apr 18 15:43 var -> /tmp/var
--IPv4 Test Fin--
This area is read only.
```

- /sbin/

```
drwxrwxr-x    2 support  root           442 Apr 18 15:43 .
drwxrwxr-x   17 support  root           295 Apr 18 15:43 ..
-rwxr-xr-x    1 support  root         90944 Apr 18 15:43 address
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 arp -> ../bin/busybox
-rwxrwxr-x    1 support  root         13600 Apr 18 15:43 call_qcsapi_sockrpc
-rwxr-xr-x    1 support  root        104256 Apr 18 15:43 cert
-rwxr-xr-x    1 support  root        110892 Apr 18 15:43 devinf
-rwxr-xr-x    1 support  root        111716 Apr 18 15:43 devinf_mstc
-rwxr-xr-x    1 support  root         98400 Apr 18 15:43 getstations
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 getty -> ../bin/busybox
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 ifconfig -> ../bin/busybox
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 init -> ../bin/busybox
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 insmod -> ../bin/busybox
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 klogd -> ../bin/busybox
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 lsmod -> ../bin/busybox
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 mdev -> ../bin/busybox
-rwxr-xr-x    1 support  root        146928 Apr 18 15:43 netinf
-rwxr-xr-x    1 support  root        175164 Apr 18 15:43 netper
-rwxr-xr-x    1 support  root        132228 Apr 18 15:43 prog
-rwxr-xr-x    1 support  root         94808 Apr 18 15:43 read
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 reboot -> ../bin/busybox
-rwxr-xr-x    1 support  root        108616 Apr 18 15:43 reset
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 rmmod -> ../bin/busybox
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 route -> ../bin/busybox
-rwxr-xr-x    1 support  root        119168 Apr 18 15:43 stats
-rwxr-xr-x    1 support  root        123264 Apr 18 15:43 stats_mstc
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 sysctl -> ../bin/busybox
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 syslogd -> ../bin/busybox
lrwxrwxrwx    1 support  root            14 Apr 18 15:43 udhcpc -> ../bin/busybox
-rwxr-xr-x    1 support  root        199096 Apr 18 15:43 um
-rwxr-xr-x    1 support  root         92056 Apr 18 15:43 version
-rwxr-xr-x    1 support  root         99320 Apr 18 15:43 write
--IPv6 Test Fin--
This area is read only.
```

- /bin:

```
drwxrwxr-x    2 support  root          1027 Apr 18 15:43 .
drwxrwxr-x   17 support  root           295 Apr 18 15:43 ..
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 ash -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 bash -> busybox
-rwxrwxr-x    1 support  root         63576 Apr 18 15:43 bob
-rwxr-xr-x    1 support  root        544716 Apr 18 15:43 busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 cat -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 chmod -> busybox
-rwxrwxr-x    1 support  root         24796 Apr 18 15:43 cmdsh
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 cp -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 date -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 dd -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 dmesg -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 echo -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 false -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 grep -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 gzip -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 hostname -> busybox
-rwxrwxr-x    1 support  root        130220 Apr 18 15:43 hz_service
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 kill -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 ln -> busybox
-rwxr-xr-x    1 support  root         35016 Apr 18 15:43 loggen
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 login -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 ls -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 maceui -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 mkdir -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 more -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 mount -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 mv -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 netstat -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 nice -> busybox
-rwxr-xr-x    1 support  root        135352 Apr 18 15:43 pdbtool
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 pidof -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 pidofzombie -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 ping -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 ping6 -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 ps -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 pwd -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 rm -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 rmdir -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 run-parts -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 sed -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 sh -> busybox
-rwxr-xr-x    1 support  root         16342 Apr 18 15:43 shgw
-rwxr-xr-x    1 support  root          8757 Apr 18 15:43 shgw_access_restriction
-rwxr-xr-x    1 support  root        137404 Apr 18 15:43 shgw_device_discovery
-rwxr-xr-x    1 support  root        205344 Apr 18 15:43 shgw_dnsproxy
-rwxr-xr-x    1 support  root         75412 Apr 18 15:43 shgw_encrypt_sql
-rwxr-xr-x    1 support  root          2200 Apr 18 15:43 shgw_hard_block_get_n_set.sh
-rwxr-xr-x    1 support  root         77280 Apr 18 15:43 shgw_httpd
-rwxr-xr-x    1 support  root          1745 Apr 18 15:43 shgw_log_trimmer
-rwxr-xr-x    1 support  root          3055 Apr 18 15:43 shgw_router_reset
-rwxr-xr-x    1 support  root          2188 Apr 18 15:43 shgw_run_ndp_scan.sh
-rwxr-xr-x    1 support  root          1881 Apr 18 15:43 shgw_version
-rwxr-xr-x    1 support  root        256480 Apr 18 15:43 shgw_watchdogd
-rwxr-xr-x    1 support  root         11722 Apr 18 15:43 shgw_wd_dpwrap
-rwxr-xr-x    1 support  root          2936 Apr 18 15:43 shgw_wd_monit
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 sleep -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 tar -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 touch -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 true -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 umount -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 uname -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 uncompress -> busybox
-rwxrwxr-x    1 support  root         20344 Apr 18 15:43 unqKeyHandler
-rwxr-xr-x    1 support  root           215 Apr 18 15:39 update-patterndb
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 usleep -> busybox
lrwxrwxrwx    1 support  root             7 Apr 18 15:43 vi -> busybox
--IPv6 Test Fin--
This area is read only.
```

- /data:

```
drwxr-xr-x    1 support  root          2048 Aug  1  2016 .
drwxrwxr-x   17 support  root           295 Apr 18 15:43 ..
-rw-r--r--    1 support  root            21 Aug  1  2016 gpon_passwd
drwx------    1 support  root          2048 Jan  1  1970 lost+found
drwxr-xr-x    1 support  root          2048 Jan  1  1970 manufStat
-rw-r--r--    1 support  root             2 Aug  1  2016 subcountry
--IPv6 Test Fin--
This area is read only.
```

- /etc:
´´´
drwxrwxr-x   51 support  root             0 Oct  9 14:48 .
drwxr-xr-x    8 support  root             0 Oct 10 15:07 ..
-rwxr-xr-x    1 support  root             0 Jan  1  1970 AppFilter.sh
-rw-r--r--    1 support  root          3104 Jan  1  1970 ParentalCtrl.sh
-rwxrwxr-x    1 support  root           512 Jan  1  1970 RT30xxEEPROM.bin
-rwxr-xr-x    1 support  root             0 Jan  1  1970 UrlFilter.sh
drwxrwxr-x    3 support  root             0 Oct 10 15:00 Wireless
-r----x--t    1 support  root          4585 Aug  1  2016 acl.sh
-rw-r--r--    1 support  root            67 Jan  1  1970 adsl.conf
-rw-r--r--    1 support  root            47 Jan  1  1970 adsl.sh
drwxr-xr-x    4 support  root             0 Apr 18 15:42 automount
-rwxrwxr-x    1 support  root          1240 Apr 18 15:22 bftpd.conf
-rwxrwxr-x    1 support  root           405 Apr 18 15:22 boa.conf
-rw-rw-r--    1 support  root           406 Apr 18 15:22 boa_TEF_HGU_COLOMBIA.conf
-rw-rw-r--    1 support  root           408 Apr 18 15:22 boa_argentina.conf
-rwxrwxr-x    1 support  root           407 Apr 18 15:22 boa_chile.conf
-rwxrwxr-x    1 support  root           406 Apr 18 15:22 boa_colombia.conf
-rwxrwxr-x    1 support  root           405 Apr 18 15:22 boa_peru.conf
-rwxrwxr-x    1 support  root           406 Apr 18 15:22 boa_user.conf
-rw-rw-r--    1 support  root           407 Apr 18 15:22 boa_user_TEF_HGU_SPAIN.conf
-rw-rw-r--    1 support  root           403 Apr 18 15:22 boa_user_argentina.conf
-rwxrwxr-x    1 support  root           404 Apr 18 15:22 boa_user_chile.conf
-rw-rw-r--    1 support  root           407 Apr 18 15:22 boa_user_sophia_FTTH.conf
-rwxrwxr-x    1 support  root            39 Apr 18 15:22 cmdp.sh
drwxrwxr-x    2 support  root             0 Apr 18 15:43 config
-rwxrwxr-x    1 support  root          3102 Jan  1  1970 csmd.json
-r----x--t    1 support  root          1382 Jan  1  1970 cwmprule.sh
-rw-r--r--    1 support  root           288 Oct  9 19:38 ddns.conf
-rwxrwxr-x    1 support  root           181 Apr 18 15:22 defaultWan.conf
-rwxrwxr-x    1 support  root            81 Apr 18 15:22 devInf.conf
-rw-r--r--    1 support  root            13 Oct 10 14:13 device_hostindex.conf
-rwxrwxr-x    1 support  root           187 Apr 18 15:42 dhcp6c.conf
-rw-r--r--    1 support  root           189 Oct  8 20:50 dhcp6c_ppp0.conf
-r----x--t    1 support  root            99 Oct  8 20:51 dhcp6s.conf
drwxrwxr-x    2 support  root             0 Apr 18 15:43 dhcpd
drwxrwxr-x    2 support  root             0 Apr 18 15:43 dist
-rw-r--r--    1 support  root           132 Oct  9 19:27 dnsmasq.conf
-rw-r--r--    1 support  root            54 Oct  9 19:27 dnsmasq_ipv4.conf
-rw-r--r--    1 support  root            78 Oct  9 19:27 dnsmasq_ipv6.conf
-rwxrwxr-x    1 support  root          1696 Apr 18 15:22 dproxy.conf
-rwxrwxr-x    1 support  root          1728 Apr 18 15:22 dproxy.conf.tmp
drwxrwxr-x    2 support  root             0 Apr 18 15:43 dropbear
-rwxrwxr-x    1 support  root          1317 Apr 18 15:42 ethertypes
-rwxrwxr-x    1 support  root          3117 Apr 18 15:22 extra_func.sh
-r----x--t    1 support  root           332 Jan  1  1970 firewall_dos.sh
-rwxrwxr-x    1 support  root            95 Apr 18 15:22 fstab
-rwxrwxr-x    1 support  root            27 Jan  1  1970 fwTCver.conf
-rwxrwxr-x    1 support  root            21 Apr 18 15:22 fwver.conf
-rwxrwxr-x    1 support  root           877 Apr 18 15:22 group
-rwxrwxr-x    1 support  root           162 Apr 18 15:22 guiDebug.sh
-rwxrwxr-x    1 support  root           209 Oct  9 19:28 hosts
drwxrwxr-x    2 support  root             0 Apr 18 15:43 igd
-rw-r--r--    1 support  root           104 Oct  9 19:38 inadyn.conf
drwxrwxr-x    2 support  root             0 Apr 18 15:43 init.d
-rwxrwxr-x    1 support  root            75 Apr 18 15:22 inittab
-rwxrwxr-x    1 support  root            75 Apr 18 15:22 inittab_no_ra_menu
-rwxrwxr-x    1 support  root            60 Apr 18 15:22 inittab_ra_menu
drwxrwxr-x    2 support  root             0 Apr 18 15:43 iproute2
-rwxrwxrwx    1 support  root           785 Aug  1  2016 isp0.conf
-rwxrwxrwx    1 support  root           376 Aug  1  2016 isp1.conf
-rw-r--r--    1 support  root           405 Aug  1  2016 isp2.conf
drwxrwxr-x    2 support  root             0 Jan  1  1970 l7-protocols
-rwxrwxrwx    1 support  root            58 Jan  1  1970 lanAlias0.conf
-rw-r--r--    1 support  root            35 Jan  1  1970 lan_rip.conf
-r----x--t    1 support  root           215 Oct  9 19:27 lanconfig.sh
-rwxrwxrwx    1 support  root            52 Aug  1  2016 mac.conf
-rw-r--r--    1 support  root           195 Jan  1  1970 macfilterBlack_cmd.sh
-rwxrwxrwx    1 support  root           711 Jan  1  1970 mcafee_down.sh
-rwxrwxrwx    1 support  root           729 Jan  1  1970 mcafee_up.sh
-rw-rw-r--    1 support  root            52 Apr 18 15:42 mdev.conf
-rw-rw-r--    1 support  root          2969 Jan  1  1970 mini_httpd.pem
-rw-rw-r--    1 support  root           120 Apr 18 15:42 mini_httpd_BR.conf
-rw-rw-r--    1 support  root           123 Apr 18 15:42 mini_httpd_cpeInfo_BR.conf
-rw-rw-r--    1 support  root           194 Apr 18 15:42 mini_httpd_ssl_BR.conf
-rwxrwxr-x    1 support  root            27 Apr 18 15:43 minifw_version
-rw-rw-r--    1 support  root          4943 Jan  1  1970 miniupnpd.conf
-rwxrwxr-x    1 support  root            71 Apr 18 15:22 mnt.conf
-rw-r--r--    1 support  root          1304 Jan  1  1970 mosuserconfig
-rw-rw-r--    1 support  root            16 Apr 18 15:43 mosv
drwxrwxr-x    2 support  root             0 Jan  1  1970 mycert
-rw-r--r--    1 support  root            20 Oct 10 14:50 nas1_gateway.conf
drwxrwxr-x    2 support  root             0 Oct 10 13:06 nat_pvc0
drwxrwxr-x    2 support  root             0 Jan  1  1970 nat_pvc1
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc10
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc10_0
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc10_1
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc10_2
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc10_3
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc10_4
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc10_5
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc10_6
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc10_7
drwxrwxr-x    2 support  root             0 Jan  1  1970 nat_pvc2
drwxrwxr-x    2 support  root             0 Jan  1  1970 nat_pvc3
drwxrwxr-x    2 support  root             0 Jan  1  1970 nat_pvc4
drwxrwxr-x    2 support  root             0 Jan  1  1970 nat_pvc5
drwxrwxr-x    2 support  root             0 Jan  1  1970 nat_pvc6
drwxrwxr-x    2 support  root             0 Jan  1  1970 nat_pvc7
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc8
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc8_0
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc8_1
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc8_2
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc8_3
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc8_4
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc8_5
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc8_6
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc8_7
drwxrwxr-x    2 support  root             0 Apr 18 15:43 nat_pvc9
drwxrwxr-x    3 support  root             0 Apr 18 15:43 net-snmp
-rw-r--r--    1 support  root             2 Jan  1  1970 noCASupport
--wxrw--wt    1 support  root            91 Aug  1  2016 ntp.sh
-rw-rw-r--    1 support  root         10835 Apr 18 15:27 openssl.cnf
-rwxrwxr-x    1 support  root           210 Apr 18 15:22 opentftp.ini
-rwxrwxr-x    1 support  root           101 Jan  1  1970 passwd
drwxr-xr-x    2 support  root             0 Apr 18 15:39 patterndb.d
-rwxrwxrwx    1 support  root           464 Aug  1  2016 pon_wan_down_0
-rwxrwxrwx    1 support  root           477 Aug  1  2016 pon_wan_down_1
-rwxrwxrwx    1 support  root           477 Aug  1  2016 pon_wan_down_2
-rwxrwxrwx    1 support  root             0 Aug  1  2016 pon_wan_down_3
-rwxrwxrwx    1 support  root             0 Aug  1  2016 pon_wan_down_4
-rwxrwxrwx    1 support  root             0 Aug  1  2016 pon_wan_down_5
-rwxrwxrwx    1 support  root             0 Aug  1  2016 pon_wan_down_6
-rwxrwxrwx    1 support  root             0 Aug  1  2016 pon_wan_down_7
-rwxrwxrwx    1 support  root           654 Aug  1  2016 pon_wan_up_0
-rwxrwxrwx    1 support  root           585 Aug  1  2016 pon_wan_up_1
-rwxrwxrwx    1 support  root           585 Aug  1  2016 pon_wan_up_2
-rwxrwxrwx    1 support  root             0 Aug  1  2016 pon_wan_up_3
-rwxrwxrwx    1 support  root             0 Aug  1  2016 pon_wan_up_4
-rwxrwxrwx    1 support  root             0 Aug  1  2016 pon_wan_up_5
-rwxrwxrwx    1 support  root             0 Aug  1  2016 pon_wan_up_6
-rwxrwxrwx    1 support  root             0 Aug  1  2016 pon_wan_up_7
drwxrwxr-x    3 support  root             0 Aug  1  2016 ppp
-rw-r--r--    1 support  root            84 Aug  1  2016 ppp_parameter.conf
-rwxrwxr-x    1 support  root          1595 Apr 18 15:22 protocols
-rwxr-xr-x    1 support  root           148 Apr 18 15:32 qharvestd.conf
-rwxrwxr-x    1 support  root          5090 Apr 18 15:22 qtn_reinit.sh
-r----x--t    1 support  root           664 Oct  8 20:51 radvd.conf
-r----x--t    1 support  root           654 Oct  8 20:51 radvd_deprecated.conf
-r----x--t    1 support  root           654 Oct  8 20:51 radvd_old.conf
-rwxrwxr-x    1 support  root            36 Apr 18 15:22 resolv.conf
-rwxrwxr-x    1 support  root            21 Apr 18 15:22 resolv_ipv4.conf
-rwxrwxr-x    1 support  root            36 Apr 18 15:22 resolv_ipv6.conf
-rw-r--r--    1 support  root             0 Oct 10 14:50 resolv_nas1.conf
-rwxr-xr-x    1 support  root            15 Apr 18 15:32 rmt_ip.conf
-rw-rw-r--    1 support  root         30109 Apr 18 15:43 romfile_GVT.cfg.compress
-rw-rw-r--    1 support  root         29976 Apr 18 15:43 romfile_Sophia.cfg.compress
drwxrwxr-x    2 support  root             0 Apr 18 15:43 samba
-rw-r--r--    1 support  root          1413 Apr 18 15:39 scl.conf
-rw-r--r--    1 support  root            14 Jan  1  1970 serialNumForSyslog.info
-rwxrwxr-x    1 support  root         19938 Apr 18 15:22 services
drwxrwxr-x    4 support  root             0 Apr 18 15:43 shaper
drwxrwxr-x    3 support  root             0 Apr 18 15:43 share
-rwxrwxr-x    1 support  root            19 Apr 18 15:22 shells
drwxrwxr-x    2 support  root             0 Apr 18 15:43 shgw
drwxrwxr-x    2 support  root             0 Jan  1  1970 snmp
-rwxrwxr-x    1 support  root          4120 Apr 18 15:22 snmpd.conf.tmp
-rwxrwxr-x    1 support  root           800 Apr 18 15:22 swu.crt
drwxrwxr-x    2 support  root             0 Apr 18 15:43 sysconfig
-rwxrwxr-x    1 support  root           289 Mar 30  2022 syslog-ng.conf
drwxrwxr-x    2 support  root             0 Apr 18 15:43 system
-rw-r--r--    1 support  root             0 Jan  1  1970 tmphttpfile
-r----x--t    1 support  root          7921 Oct  8 20:50 tr181firewall.sh
-rw-r--r--    1 support  root           286 Jan  1  1970 tr69Black_cmd.sh
-rw-r--r--    1 support  root          1283 Oct 10 15:06 udhcp_lease
-rw-r--r--    1 support  root           472 Oct  9 19:28 udhcpd.conf
-rw-r--r--    1 support  root           574 Oct  9 19:28 udhcpd_conserpool1.conf
-rw-r--r--    1 support  root           534 Oct  9 19:28 udhcpd_conserpool2.conf
-rw-r--r--    1 support  root            57 Jan  1  1970 userssh
-rw-r--r--    1 support  root            60 Jan  1  1970 usertelnetonly
-rw-r--r--    1 support  root            57 Jan  1  1970 usertty
-rw-rw-r--    1 support  root            16 Apr 18 15:43 v
drwxrwxr-x    2 support  root             0 Apr 18 15:43 xml
--IPv6 Test Fin--
This area is read only.
´´´

- /tmp:

´´´
drwxr-xr-x    8 support  root             0 Oct 10 15:12 .
drwxrwxr-x   17 support  root           295 Apr 18 15:43 ..
srwxr-xr-x    1 support  root             0 Aug  1  2016 .QTNCSMD_CLI_AF_UNIX
srwxr-xr-x    1 support  root             0 Aug  1  2016 .QTNCommM_AF_UNIX
srwxr-xr-x    1 support  root             0 Aug  1  2016 .QTNSL_AF_UNIX
srwxr-xr-x    1 support  root             0 Jan  1  1970 .QTN_RPECAT_AF_UNIX
-rw-r--r--    1 support  root             8 Oct 10 13:29 .sid
-rw-r--r--    1 support  root             4 Oct 10 14:37 5G_channel
----------    1 support  root           256 Jan  1  1970 7570_bob.conf
drwxr-xr-x    2 support  root             0 Oct  9 14:26 Certificates
-rw-r--r--    1 support  root             5 Jan  1  1970 HPNAAutoDetect.txt
-rw-r--r--    1 support  root            21 Jan  1  1970 HPNAVersion.txt
----------    1 support  root            48 Jan  1  1970 HT_Cap_and_Info
-rw-r--r--    1 support  root             0 Oct  8 20:50 NtpUp
-rw-r--r--    1 support  root             6 Jan  1  1970 RX_threshold
-rw-r--r--    1 support  root             2 Oct  8 20:51 WirelessSchedule
-rw-r--r--    1 support  root             2 Aug  1  2016 adv_mode
-rw-r--r--    1 support  root           734 Oct 10 12:45 arplist
-rw-r--r--    1 support  root             2 Aug  1  2016 authresult
----------    1 support  root             0 Oct 10 15:12 cfg_mq_still_alive
-rw-r--r--    1 support  root           718 Oct 10 13:28 cgi-debug.log
-rw-r--r--    1 support  root             0 Jan  1  1970 channel_info
-rw-r--r--    1 support  root             0 Oct 10 15:12 check11n
----------    1 support  root        106305 Oct 10 13:31 customer_defaultromfile
---------x    1 support  root        180824 Jan  1  1970 customer_runningromfile
drwxr-xr-x    2 support  root             0 Aug  1  2016 cwmp
-rw-r--r--    1 support  root            29 Oct 10 14:37 datetime
-rw-r--r--    1 support  root            30 Oct  8 20:50 dhcp6c_duid
-rw-r--r--    1 support  root             4 Aug  1  2016 dhcpc_interface
-rw-r--r--    1 support  root             4 Jan  1  1970 dns_cache_servfail_ttl
-rw-r--r--    1 support  root           158 Oct 10 15:11 dropbearPs
drwxrwxr-x   51 support  root             0 Oct  9 14:48 etc
srwxr-xr-x    1 support  root             0 Jan  1  1970 hotspot
drwxr-xr-x    2 support  root             0 Jan  1  1970 hpna
-rw-r--r--    1 support  root           322 Jan  1  1970 ifconfig.txt
-rw-r--r--    1 support  root           304 Oct 10 13:12 in_ap_cfg
-rw-r--r--    1 support  root           104 Oct  9 19:38 inadyn.conf
-rw-r--r--    1 support  root           132 Oct  8 20:51 ip6dfrt.info
-r----x--t    1 support  root          1806 Oct 10 13:06 ipaddr_mapping.sh
-r----x--t    1 support  root            34 Aug  1  2016 ipaddr_mapping0.sh
-r----x--t    1 support  root            34 Aug  1  2016 ipaddr_mapping1.sh
-rw-r--r--    1 support  root             0 Oct 10 15:12 ipmroute
-rw-r--r--    1 support  root             2 Aug  1  2016 ipv6cp_is_up
-rw-r--r--    1 support  root            14 Oct 10 14:37 lanPortStatus
-rw-r--r--    1 support  root            90 Oct 10 14:37 lanStatus
-rw-r--r--    1 support  root            14 Oct  8 20:55 lan_IP
-rw-r--r--    1 support  root           456 Oct 10 15:12 lan_arp
-rw-r--r--    1 support  root           191 Oct 10 15:12 lan_port
-rw-r--r--    1 support  root            26 Aug  1  2016 lcp
-rw-r--r--    1 support  root            27 Aug  1  2016 macAddress
----------    1 support  root           256 Jan  1  1970 main_trx.bin
-rw-r--r--    1 support  root           147 Jan  1  1970 md5.txt
-rw-r--r--    1 support  root            11 Jan  1  1970 md5_secondary.txt
-rw-r--r--    1 support  root             1 Jan  1  1970 mibReset
-rw-r--r--    1 support  root             0 Jan  1  1970 mini_httpd
-rw-r--r--    1 support  root        147552 Oct 10 15:00 mini_httpd.log
-rw-r--r--    1 support  root             4 Jan  1  1970 mini_httpd.pid
-rw-r--r--    1 support  root            33 Oct 10 15:00 numberAssoc
-rw-r--r--    1 support  root             2 Oct  8 20:52 numberAssocCC
-rw-r--r--    1 support  root            73 Oct 10 13:12 out_fdbk_file
-rw-r--r--    1 support  root             0 Oct 10 14:37 ping
-rw-r--r--    1 support  root             0 Oct 10 15:02 ping_resul
-rw-r--r--    1 support  root             0 Oct 10 15:12 ping_result
----------    1 support  root             0 Jan  1  1970 pmq
-rw-r--r--    1 support  root             2 Jan  1  1970 pon_up
-rw-r--r--    1 support  root            23 Aug  1  2016 pppsid-nas0
-rw-r--r--    1 support  root             2 Aug  1  2016 pppuptime-ppp0
-rw-r--r--    1 support  root             3 Aug  1  2016 pppuptime-ppp1
---s--s--T    1 support  root             0 Aug  1  2016 qoslockfd
-rw-r--r--    1 support  root             0 Oct 10 15:00 rmt_process
-rw-r--r--    1 support  root            33 Jan  1  1970 rt_device
drwxr-xr-x    2 support  root             0 Jan  1  1970 scpbin
prw-r--r--    1 support  root             0 Oct  9 19:28 sigtoudhcpdfifo
srwxr-xr-x    1 support  root             0 Jan  1  1970 smd_sock
-rw-r--r--    1 support  root             2 Oct 10 15:11 sshSessionNum
-rw-r--r--    1 support  root             2 Oct 10 13:12 sync_soniq_status
-rw-r--r--    1 support  root            37 Jan  1  1970 sync_wps_uuid
---s--S---    1 support  root             0 Jan  1  1970 syslockfd
srwxr-xr-x    1 support  root             0 Jan  1  1970 tcapi_sock
-rw-r--r--    1 support  root            50 Jan  1  1970 thresholds.ini
-rw-r--r--    1 support  root        131072 Oct 10 13:31 tmp_compress
-rw-r--r--    1 support  root           304 Oct 10 13:12 update_ap_cfg
-rw-------    1 support  root            49 Jan  1  1970 upnpfake.conf
drwxrwxrwx    9 support  root             0 Oct 10 15:11 var
-rw-r--r--    1 support  root             2 Jan  1  1970 wifiAuthMode
-rw-r--r--    1 support  root           135 Oct 10 15:00 wlan_assocSTA
-rw-r--r--    1 support  root             2 Oct 10 15:12 wlan_curr_channel
--wSr--r--    1 support  root             0 Aug  1  2016 wlanlockfd
-rw-r--r--    1 support  root           385 Oct 10 14:37 wps
--IPv6 Test Fin--
This area is read only.
´´´