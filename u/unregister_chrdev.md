# Function: <code>unregister_chrdev</code>

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
In drivers/char/virtio_console.c (ffffffff81518355)
Location: include/linux/fs.h:2373
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81fadf18)
Location: include/linux/fs.h:2373
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff820b067d)
Location: include/linux/fs.h:2373
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81617776)
Location: include/linux/fs.h:2373
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
```
```
In drivers/i2c/i2c-dev.c (ffffffff820b0ae2)
Location: include/linux/fs.h:2373
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81fcb8e8)
Location: include/linux/fs.h:2472
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff8156b065)
Location: include/linux/fs.h:2472
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff815edf51)
Location: include/linux/fs.h:2472
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff820e81cd)
Location: include/linux/fs.h:2472
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81677836)
Location: include/linux/fs.h:2472
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In drivers/video/fbdev/core/fbmem.c (ffffffff82008923)
Location: include/linux/fs.h:2454
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff815977d5)
Location: include/linux/fs.h:2454
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8161ad61)
Location: include/linux/fs.h:2454
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff821cdf51)
Location: include/linux/fs.h:2454
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff816a5516)
Location: include/linux/fs.h:2454
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In drivers/video/fbdev/core/fbmem.c (ffffffff820e9beb)
Location: include/linux/fs.h:2508
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff815ab7f1)
Location: include/linux/fs.h:2508
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8162ef71)
Location: include/linux/fs.h:2508
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff822c3155)
Location: include/linux/fs.h:2508
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff816ba886)
Location: include/linux/fs.h:2508
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In drivers/video/fbdev/core/fbmem.c (ffffffff826f2693)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff81612197)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/nvdimm/bus.c (ffffffff816976e1)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff828d636d)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81726246)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8271c610)
Location: include/linux/fs.h:2580
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff8164ca09)
Location: include/linux/fs.h:2580
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff816d3831)
Location: include/linux/fs.h:2580
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82907c4b)
Location: include/linux/fs.h:2580
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81764fc5)
Location: include/linux/fs.h:2580
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105da7f)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828d45dd)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff8166a8d9)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff816f4f31)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82adfa6f)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81789645)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060e2f)
Location: include/linux/fs.h:2667
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828ee662)
Location: include/linux/fs.h:2667
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff816a08e4)
Location: include/linux/fs.h:2667
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff8172e6f1)
Location: include/linux/fs.h:2667
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82b04adc)
Location: include/linux/fs.h:2667
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817c7ad5)
Location: include/linux/fs.h:2667
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810616df)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828f77ab)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff816c3698)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff81752991)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82b139ab)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817f85f5)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106735f)
Location: include/linux/fs.h:2725
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff82d0e5ca)
Location: include/linux/fs.h:2725
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff81777c63)
Location: include/linux/fs.h:2725
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff818113c1)
Location: include/linux/fs.h:2725
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82f2545c)
Location: include/linux/fs.h:2725
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff818c8715)
Location: include/linux/fs.h:2725
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106558f)
Location: include/linux/fs.h:2602
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff82ffbfd4)
Location: include/linux/fs.h:2602
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff81c08856)
Location: include/linux/fs.h:2602
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff81820301)
Location: include/linux/fs.h:2602
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8321d9c9)
Location: include/linux/fs.h:2602
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff818d38c5)
Location: include/linux/fs.h:2602
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065c5f)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff83206d61)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff81bfa3f8)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff818035e1)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83451982)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/net/wwan/wwan_core.c (ffffffff834519c5)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_exit
```
```
In drivers/usb/core/file.c (ffffffff818b6e25)
Location: include/linux/fs.h:2836
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106fd7f)
Location: include/linux/fs.h:2817
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff832eeb0d)
Location: include/linux/fs.h:2817
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff81cfadd4)
Location: include/linux/fs.h:2817
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff8188db61)
Location: include/linux/fs.h:2817
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83544f9f)
Location: include/linux/fs.h:2817
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff8194c835)
Location: include/linux/fs.h:2817
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107d62f)
Location: include/linux/fs.h:2694
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff834a6b1a)
Location: include/linux/fs.h:2694
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff81ec35d1)
Location: include/linux/fs.h:2694
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff819d70b1)
Location: include/linux/fs.h:2694
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83723388)
Location: include/linux/fs.h:2694
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81aa5375)
Location: include/linux/fs.h:2694
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108eb4f)
Location: include/linux/fs.h:2842
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff83edd73a)
Location: include/linux/fs.h:2842
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff81a99cf7)
Location: include/linux/fs.h:2842
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff81b51dc1)
Location: include/linux/fs.h:2842
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff842b1e30)
Location: include/linux/fs.h:2842
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81c2bda5)
Location: include/linux/fs.h:2842
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810919ff)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff83703201)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff81ae5567)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff81ba52a1)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83af4af0)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81c92d35)
Location: include/linux/fs.h:2456
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098da5)
Location: include/linux/fs.h:2691
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fb_chrdev.c (ffffffff819cb195)
Location: include/linux/fs.h:2691
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_chrdev.c:fb_unregister_chrdev
```
```
In drivers/char/virtio_console.c (ffffffff81b38926)
Location: include/linux/fs.h:2691
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff81bf9521)
Location: include/linux/fs.h:2691
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff83954238)
Location: include/linux/fs.h:2691
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_core_init
```
```
In drivers/accel/drm_accel.c (ffffffff81cbd015)
Location: include/linux/fs.h:2691
Inline: True
Inline callers:
  - drivers/accel/drm_accel.c:accel_core_exit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83d508f0)
Location: include/linux/fs.h:2691
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff81d477e5)
Location: include/linux/fs.h:2691
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In drivers/video/fbdev/core/fbmem.c (ffff80001147ab38)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffff8000108b59a8)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffff800010952fe8)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000114ba4e4)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffff800010a29338)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In drivers/video/fbdev/core/fbmem.c (c1552c34)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (c09b059c)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/net/ppp/ppp_generic.c (c15c0674)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (c0aff308)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
```
```
In sound/sound_core.c (c15c1824)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - sound/sound_core.c:cleanup_soundcore
  - sound/sound_core.c:init_soundcore
```
```
In sound/core/sound.c (c15c1860)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - sound/core/sound.c:alsa_sound_exit
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
In drivers/video/fbdev/core/fbmem.c (c0000000013a2fc4)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (c000000000950090)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (c000000000a00158)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (c0000000013cdbf4)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (c000000000ae579c)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In drivers/video/fbdev/core/fbmem.c (ffffffe00002c7b0)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffe0005670a6)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffe0005c2a7e)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe0000a1f88)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffe00064ad56)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106125f)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828e056e)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff816890e8)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff81707081)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82af39fc)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817b09d5)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810516bf)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828d8c47)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff81666bc3)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff816dab01)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82ac3e2f)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817a2405)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106168f)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828f33fe)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff816b7399)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff81745e51)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82b0ecc1)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff817ed475)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062c3f)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff828f87ff)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/char/virtio_console.c (ffffffff816d1996)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
```
```
In drivers/nvdimm/bus.c (ffffffff81761291)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff82b037e3)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
```
In drivers/usb/core/file.c (ffffffff818076b5)
Location: include/linux/fs.h:2702
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_major_cleanup
```
</details>
</li>
</ul>

## Differences
