# Function: <code>raw_copy_in_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff812b4307)
Location: arch/x86/include/asm/uaccess_64.h:165
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
In fs/quota/compat.c (ffffffff812c5a39)
Location: arch/x86/include/asm/uaccess_64.h:165
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
In block/compat_ioctl.c (ffffffff81454816)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e9c40)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff816c02f1)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff817afd9c)
Location: arch/x86/include/asm/uaccess_64.h:165
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
In net/compat.c (ffffffff817fa3c9)
Location: arch/x86/include/asm/uaccess_64.h:165
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
In fs/compat_ioctl.c (ffffffff812d7a32)
Location: arch/x86/include/asm/uaccess_64.h:166
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
In fs/quota/compat.c (ffffffff812e98e9)
Location: arch/x86/include/asm/uaccess_64.h:166
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
In block/compat_ioctl.c (ffffffff814804a9)
Location: arch/x86/include/asm/uaccess_64.h:166
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e7a6)
Location: arch/x86/include/asm/uaccess_64.h:166
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8172bd21)
Location: arch/x86/include/asm/uaccess_64.h:166
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81827f19)
Location: arch/x86/include/asm/uaccess_64.h:166
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
In net/compat.c (ffffffff81877d1a)
Location: arch/x86/include/asm/uaccess_64.h:166
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
In fs/compat_ioctl.c (ffffffff81301be6)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/quota/compat.c (ffffffff8131681e)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In block/compat_ioctl.c (ffffffff814b5013)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81554334)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8176b16e)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81870c31)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In net/compat.c (ffffffff818c98fa)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/compat_ioctl.c (ffffffff813175c3)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/quota/compat.c (ffffffff8132d7ce)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In block/compat_ioctl.c (ffffffff814c88d3)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156bd8f)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8178f6fe)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81891da7)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In net/compat.c (ffffffff818f47d1)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/compat_ioctl.c (ffffffff8133f472)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/quota/compat.c (ffffffff8135550e)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In block/compat_ioctl.c (ffffffff814f70d9)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159c067)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817cd8f3)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818dbd01)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In net/compat.c (ffffffff819542ee)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/compat_ioctl.c (ffffffff813576b2)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/quota/compat.c (ffffffff8136d84e)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In block/compat_ioctl.c (ffffffff8151559e)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd667)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817fe339)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff8190e85b)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In net/compat.c (ffffffff8198a7fa)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/quota/compat.c (ffffffff813b5349)
Location: arch/x86/include/asm/uaccess_64.h:78
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81666871)
Location: arch/x86/include/asm/uaccess_64.h:78
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/usb/core/devio.c (ffffffff818ce747)
Location: arch/x86/include/asm/uaccess_64.h:78
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff819e0512)
Location: arch/x86/include/asm/uaccess_64.h:78
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
In net/socket.c (ffffffff819dd8e3)
Location: arch/x86/include/asm/uaccess_64.h:62
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
In net/socket.c (ffffffff819c5ad5)
Location: arch/x86/include/asm/uaccess_64.h:62
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int raw_copy_in_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (c00000000052a860)
Location: arch/powerpc/include/asm/uaccess.h:311
Inline: True
Inline callers:
  - fs/compat_ioctl.c:sg_ioctl_trans
Direct callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
```
```
In block/compat_ioctl.c (c0000000007ba6b8)
Location: arch/powerpc/include/asm/uaccess.h:311
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_cdrom_generic_command
Direct callers:
  - block/compat_ioctl.c:compat_cdrom_generic_command
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a6614)
Location: arch/powerpc/include/asm/uaccess.h:311
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/usb/core/devio.c (c000000000aef97c)
Location: arch/powerpc/include/asm/uaccess.h:311
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (c000000000c7a5fc)
Location: arch/powerpc/include/asm/uaccess.h:311
Inline: True
Inline callers:
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (c000000000d2d04c)
Location: arch/powerpc/include/asm/uaccess.h:311
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
Direct callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
**Symbols:**

```
c000000000529c90-c000000000529d14: raw_copy_in_user (STB_LOCAL)
c0000000007b94b0-c0000000007b9534: raw_copy_in_user (STB_LOCAL)
c000000000c77830-c000000000c778b4: raw_copy_in_user (STB_LOCAL)
c000000000d2c320-c000000000d2c3a4: raw_copy_in_user (STB_LOCAL)
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
In fs/compat_ioctl.c (ffffffff8134fc92)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/quota/compat.c (ffffffff81365e2e)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In block/compat_ioctl.c (ffffffff8150db7e)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b17b7)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817b6719)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818ae85b)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In net/compat.c (ffffffff8192a66a)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/compat_ioctl.c (ffffffff81340972)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/quota/compat.c (ffffffff81356ace)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In block/compat_ioctl.c (ffffffff814fdfae)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a0947)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817a8139)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818687ab)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In net/compat.c (ffffffff818e441a)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/compat_ioctl.c (ffffffff8134d762)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/quota/compat.c (ffffffff813638fe)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In block/compat_ioctl.c (ffffffff81509c0e)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1d47)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817f31b9)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818ff85b)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In net/compat.c (ffffffff8197b7fa)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/compat_ioctl.c (ffffffff81360ce2)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In fs/quota/compat.c (ffffffff81376fae)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In block/compat_ioctl.c (ffffffff8152327e)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb7b7)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8180d439)
Location: arch/x86/include/asm/uaccess_64.h:182
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff8192084b)
Location: arch/x86/include/asm/uaccess_64.h:182
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
In net/compat.c (ffffffff8199dd4a)
Location: arch/x86/include/asm/uaccess_64.h:182
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
<b>Arch</b>
<ul>
</ul>
