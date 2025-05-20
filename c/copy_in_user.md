# Function: <code>copy_in_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int copy_in_user(void *to, const void *from, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff813f79f0)
Location: arch/x86/lib/usercopy_64.c:57
Inline: False
Direct callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
**Symbols:**

```
ffffffff813f79f0-ffffffff813f7a30: copy_in_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int copy_in_user(void *to, const void *from, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8143e8a0)
Location: arch/x86/lib/usercopy_64.c:57
Inline: False
Direct callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
**Symbols:**

```
ffffffff8143e8a0-ffffffff8143e8de: copy_in_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int copy_in_user(void *to, const void *from, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8145b8f0)
Location: arch/x86/lib/usercopy_64.c:57
Inline: False
Direct callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
**Symbols:**

```
ffffffff8145b8f0-ffffffff8145b92f: copy_in_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff812b42de)
Location: include/linux/uaccess.h:159
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/quota/compat.c (ffffffff812c5a13)
Location: include/linux/uaccess.h:159
Inline: True
Inline callers:
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
```
```
In block/compat_ioctl.c (ffffffff814547f0)
Location: include/linux/uaccess.h:159
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e9c17)
Location: include/linux/uaccess.h:159
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff816c02cb)
Location: include/linux/uaccess.h:159
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff817afd6e)
Location: include/linux/uaccess.h:159
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff817fa3a8)
Location: include/linux/uaccess.h:159
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff812d7a09)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/quota/compat.c (ffffffff812e98c3)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
```
```
In block/compat_ioctl.c (ffffffff81480483)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e77d)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8172bcfb)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81827eeb)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff81877cf9)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81301bc0)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff813167f8)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff814b4fed)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8155431e)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8176b145)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81870bfe)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff818c98e4)
Location: include/linux/uaccess.h:160
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81317589)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff8132d7a8)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff814c88ad)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156bd79)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8178f6d5)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81891d74)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff818f47b7)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8133f457)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
```
```
In fs/quota/compat.c (ffffffff813554e8)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff814f70b3)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159c041)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817cd8ca)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818dbccc)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff819542d3)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81357678)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff8136d828)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff81515570)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd641)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817fe318)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff8190e826)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8198a7e7)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/compat.c (ffffffff813b5323)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81666848)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/usb/core/devio.c (ffffffff818ce729)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff819e04e1)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dd8bb)
Location: include/linux/uaccess.h:205
Inline: True
Inline callers:
  - net/socket.c:compat_ifreq_ioctl
  - net/socket.c:compat_ifreq_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c5aa4)
Location: include/linux/uaccess.h:205
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffff80001041d768)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
```
```
In block/compat_ioctl.c (ffff80001061b960)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
```
```
In drivers/video/fbdev/core/fbmem.c (ffff8000107459d0)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/usb/core/devio.c (ffff800010a31bc8)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffff800010ba6ff0)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffff800010c34290)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (c00000000052b608)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
```
```
In block/compat_ioctl.c (c0000000007ba538)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a65b8)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/usb/core/devio.c (c000000000aeee30)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (c000000000c7b284)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (c000000000d2d030)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8134fc58)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff81365e08)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff8150db50)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1791)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817b66f8)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818ae826)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8192a657)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81340938)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff81356aa8)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff814fdf80)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a0921)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817a8118)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81868776)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff818e4407)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8134d728)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff813638d8)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff81509be0)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1d21)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817f3198)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818ff826)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8197b7e7)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81360ca8)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff81376f88)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff81523250)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb791)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8180d418)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81920816)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8199dd37)
Location: include/linux/uaccess.h:157
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
