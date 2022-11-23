---
title: busybox安装失败解决方法
date: 2022-11-23
category:
  - android
tag:
  - 解决
order: -0.2
---

安卓4安装**busybox**，报错信息如下
# ./busybox --install
```busybox: /usr/bin/[: No such file or directory
busybox: /usr/bin/[[: No such file or directory
busybox: /sbin/acpid: Invalid cross-device link
busybox: /usr/bin/add-shell: No such file or directory
busybox: /bin/addgroup: No such file or directory
busybox: /bin/adduser: No such file or directory
busybox: /sbin/adjtimex: Invalid cross-device link
busybox: /sbin/arp: Invalid cross-device link
busybox: /usr/bin/arping: No such file or directory
busybox: /bin/ash: No such file or directory
busybox: /usr/bin/awk: No such file or directory
busybox: /bin/base64: No such file or directory
busybox: /usr/bin/basename: No such file or directory
busybox: /usr/bin/beep: No such file or directory
busybox: /sbin/blkid: Invalid cross-device link
busybox: /sbin/blockdev: Invalid cross-device link
busybox: /sbin/bootchartd: Invalid cross-device link
busybox: /usr/sbin/brctl: No such file or directory
busybox: /usr/bin/bunzip2: No such file or directory
busybox: /usr/bin/bzcat: No such file or directory
busybox: /usr/bin/bzip2: No such file or directory
busybox: /usr/bin/cal: No such file or directory
busybox: /bin/cat: No such file or directory
busybox: /bin/catv: No such file or directory
busybox: /usr/bin/chat: No such file or directory
busybox: /bin/chattr: No such file or directory
busybox: /bin/chgrp: No such file or directory
busybox: /bin/chmod: No such file or directory
busybox: /bin/chown: No such file or directory
busybox: /usr/sbin/chpasswd: No such file or directory
busybox: /usr/bin/chpst: No such file or directory
busybox: /usr/sbin/chroot: No such file or directory
busybox: /usr/bin/chrt: No such file or directory
busybox: /usr/bin/chvt: No such file or directory
busybox: /usr/bin/cksum: No such file or directory
busybox: /usr/bin/clear: No such file or directory
busybox: /usr/bin/cmp: No such file or directory
busybox: /usr/bin/comm: No such file or directory
busybox: /bin/cp: No such file or directory
busybox: /bin/cpio: No such file or directory
busybox: /usr/sbin/crond: No such file or directory
busybox: /usr/bin/crontab: No such file or directory
busybox: /usr/bin/cryptpw: No such file or directory
busybox: /bin/cttyhack: No such file or directory
busybox: /usr/bin/cut: No such file or directory
busybox: /bin/date: No such file or directory
busybox: /usr/bin/dc: No such file or directory
busybox: /bin/dd: No such file or directory
busybox: /usr/bin/deallocvt: No such file or directory
busybox: /bin/delgroup: No such file or directory
busybox: /bin/deluser: No such file or directory
busybox: /sbin/depmod: Invalid cross-device link
busybox: /sbin/devmem: Invalid cross-device link```

解决方案：
**busybox --install /system/bin**