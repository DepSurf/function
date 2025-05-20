# Function: <code>register_chrdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81fa0071)
Location: include/linux/fs.h:2367
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81fa63aa)
Location: include/linux/fs.h:2367
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff81fa783c)
Location: include/linux/fs.h:2367
Inline: True
```
```
In drivers/char/misc.c (ffffffff81fa80e7)
Location: include/linux/fs.h:2367
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff815189d6)
Location: include/linux/fs.h:2367
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81fade9a)
Location: include/linux/fs.h:2367
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81fb009f)
Location: include/linux/fs.h:2367
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81617726)
Location: include/linux/fs.h:2367
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
```
In drivers/i2c/i2c-dev.c (ffffffff81fb2a56)
Location: include/linux/fs.h:2367
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81fcb87c)
Location: include/linux/fs.h:2466
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81fd2729)
Location: include/linux/fs.h:2466
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff81fd3c4d)
Location: include/linux/fs.h:2466
Inline: True
```
```
In drivers/char/misc.c (ffffffff81fd44fb)
Location: include/linux/fs.h:2466
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff8156b6f2)
Location: include/linux/fs.h:2466
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81fda992)
Location: include/linux/fs.h:2466
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81fdcc13)
Location: include/linux/fs.h:2466
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff816777e6)
Location: include/linux/fs.h:2466
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff820088b7)
Location: include/linux/fs.h:2448
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff820100e9)
Location: include/linux/fs.h:2448
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff8201160d)
Location: include/linux/fs.h:2448
Inline: True
```
```
In drivers/char/misc.c (ffffffff82011ebb)
Location: include/linux/fs.h:2448
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff81597e62)
Location: include/linux/fs.h:2448
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8201840e)
Location: include/linux/fs.h:2448
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8201a7eb)
Location: include/linux/fs.h:2448
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff816a54c6)
Location: include/linux/fs.h:2448
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
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
In drivers/video/fbdev/core/fbmem.c (ffffffff820e9b7f)
Location: include/linux/fs.h:2502
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff820f1bac)
Location: include/linux/fs.h:2502
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff820f318b)
Location: include/linux/fs.h:2502
Inline: True
```
```
In drivers/char/misc.c (ffffffff820f3a41)
Location: include/linux/fs.h:2502
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff815abe02)
Location: include/linux/fs.h:2502
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff820fa2cd)
Location: include/linux/fs.h:2502
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff820fc888)
Location: include/linux/fs.h:2502
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff816ba836)
Location: include/linux/fs.h:2502
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
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
In drivers/video/fbdev/core/fbmem.c (ffffffff826f2627)
Location: include/linux/fs.h:2551
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff826fb3a2)
Location: include/linux/fs.h:2551
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff826fc87b)
Location: include/linux/fs.h:2551
Inline: True
```
```
In drivers/char/misc.c (ffffffff826fd12e)
Location: include/linux/fs.h:2551
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff816127a2)
Location: include/linux/fs.h:2551
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff82703ae2)
Location: include/linux/fs.h:2551
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82705ffd)
Location: include/linux/fs.h:2551
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817261f6)
Location: include/linux/fs.h:2551
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8271c58b)
Location: include/linux/fs.h:2574
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff827256bf)
Location: include/linux/fs.h:2574
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff82726b71)
Location: include/linux/fs.h:2574
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff82727429)
Location: include/linux/fs.h:2574
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff8164c829)
Location: include/linux/fs.h:2574
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8272d865)
Location: include/linux/fs.h:2574
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8272fe3e)
Location: include/linux/fs.h:2574
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81764f85)
Location: include/linux/fs.h:2574
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d9c5)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828d4558)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff828dd868)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff828ded55)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff828df624)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff8166a6f9)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff828e622e)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff828e8afb)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81789605)
Location: include/linux/fs.h:2660
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060d75)
Location: include/linux/fs.h:2661
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828ee5da)
Location: include/linux/fs.h:2661
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff828f8154)
Location: include/linux/fs.h:2661
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff828f9674)
Location: include/linux/fs.h:2661
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff828fa052)
Location: include/linux/fs.h:2661
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff816a04fd)
Location: include/linux/fs.h:2661
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff82900995)
Location: include/linux/fs.h:2661
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82903443)
Location: include/linux/fs.h:2661
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817c7a95)
Location: include/linux/fs.h:2661
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061625)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828f7723)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff82901055)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff82902577)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff82902f45)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff816c32ad)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff82909bdf)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8290c640)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817f85b5)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810672a5)
Location: include/linux/fs.h:2719
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff82d0e542)
Location: include/linux/fs.h:2719
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff82d18378)
Location: include/linux/fs.h:2719
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff82d19939)
Location: include/linux/fs.h:2719
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff82d19df0)
Location: include/linux/fs.h:2719
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff81776ced)
Location: include/linux/fs.h:2719
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff82d1fe18)
Location: include/linux/fs.h:2719
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82d21245)
Location: include/linux/fs.h:2719
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff818c86d5)
Location: include/linux/fs.h:2719
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810654d5)
Location: include/linux/fs.h:2596
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff82ffbf4c)
Location: include/linux/fs.h:2596
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff83005ff1)
Location: include/linux/fs.h:2596
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff8300763d)
Location: include/linux/fs.h:2596
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff83007af0)
Location: include/linux/fs.h:2596
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff81791a1d)
Location: include/linux/fs.h:2596
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8300dbf4)
Location: include/linux/fs.h:2596
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8300f030)
Location: include/linux/fs.h:2596
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff818d3885)
Location: include/linux/fs.h:2596
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065ba5)
Location: include/linux/fs.h:2830
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff83206cda)
Location: include/linux/fs.h:2830
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff83210b7f)
Location: include/linux/fs.h:2830
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff83212232)
Location: include/linux/fs.h:2830
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff83212602)
Location: include/linux/fs.h:2830
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff8177451d)
Location: include/linux/fs.h:2830
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff83218a1f)
Location: include/linux/fs.h:2830
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8321a014)
Location: include/linux/fs.h:2830
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8321a15b)
Location: include/linux/fs.h:2830
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_init
```
```
In drivers/usb/core/file.c (ffffffff818b6de5)
Location: include/linux/fs.h:2830
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106fcc5)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff832eea86)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff832f9bcd)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff832fb409)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff832fb88a)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff817fa91d)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff83302448)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83303ae9)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff8194c7f5)
Location: include/linux/fs.h:2811
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107d555)
Location: include/linux/fs.h:2688
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff834a6a92)
Location: include/linux/fs.h:2688
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff834b2423)
Location: include/linux/fs.h:2688
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff834b3e06)
Location: include/linux/fs.h:2688
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff834b42b5)
Location: include/linux/fs.h:2688
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff81939879)
Location: include/linux/fs.h:2688
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff834bb5b1)
Location: include/linux/fs.h:2688
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff834bcabd)
Location: include/linux/fs.h:2688
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81aa5325)
Location: include/linux/fs.h:2688
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108ea65)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff83edd670)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff83eecae5)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff83eeec45)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff83eef2d2)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff81a99a29)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff83ef94c3)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83efaf9a)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81c2bd25)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81091925)
Location: include/linux/fs.h:2450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff83703140)
Location: include/linux/fs.h:2450
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff837127b5)
Location: include/linux/fs.h:2450
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff837148a5)
Location: include/linux/fs.h:2450
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff83714f30)
Location: include/linux/fs.h:2450
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff81ae5299)
Location: include/linux/fs.h:2450
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8371f163)
Location: include/linux/fs.h:2450
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83720d8a)
Location: include/linux/fs.h:2450
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81c92cb5)
Location: include/linux/fs.h:2450
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098cf5)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fb_chrdev.c (ffffffff819cb115)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_chrdev.c:fb_register_chrdev
```
```
In drivers/tty/vt/vc_screen.c (ffffffff839461c5)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff83948305)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff83948990)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff81b3868d)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff83952b33)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff839541d3)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_core_init
```
```
In drivers/accel/drm_accel.c (ffffffff83954543)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - drivers/accel/drm_accel.c:accel_core_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83954c8a)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81d47765)
Location: include/linux/fs.h:2685
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
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
In drivers/video/fbdev/core/fbmem.c (ffff80001147aac0)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffff8000114930ac)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffff800011495564)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffff800011495fe0)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffff8000108b56d0)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffff80001149935c)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffff80001149be4c)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffff800010a292dc)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c1552ba8)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (c1593d24)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (c1595fbc)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (c1596c0c)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (c09b02e8)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/net/ppp/ppp_generic.c (c159cfa8)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (c0aff2a8)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
```
In sound/sound_core.c (c15b2184)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - sound/sound_core.c:init_soundcore
```
```
In sound/core/sound.c (c15b2274)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - sound/core/sound.c:alsa_sound_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c0000000013a2f20)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (c0000000013a5858)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (c0000000013a81f0)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (c0000000013a8fc8)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (c00000000094fcf4)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (c0000000013acb68)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (c0000000013b0184)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (c000000000ae5720)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffe00002c73c)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffe00002e1c6)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffe00002f87a)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffe0000301ee)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffe000566c1a)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffe000032848)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe000034e7e)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffe00064acfc)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810611a5)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828e04e6)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff828e8872)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff828e9d5e)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff828ea72c)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff81688cfd)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff828f0f84)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff828f3ffd)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817b0995)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81051605)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828d8bbf)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff828dffd5)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff828e11eb)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff828e1bb9)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff816667ad)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff828e828c)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff828eb577)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817a23c5)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810615d5)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828f3376)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff828fc378)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff828fd89a)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff828fe268)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff816b6f7d)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff82904f02)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82907a3b)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817ed435)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062b85)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828f8777)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/tty/vt/vc_screen.c (ffffffff829020a9)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_init
```
```
In drivers/char/mem.c (ffffffff829035d9)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/mem.c:chr_dev_init
```
```
In drivers/char/misc.c (ffffffff82903fa7)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/char/virtio_console.c (ffffffff816d1588)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8290ac41)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8290d6a2)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81807675)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_init
```
</details>
</li>
</ul>

## Differences
