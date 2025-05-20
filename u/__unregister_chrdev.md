# Function: <code>__unregister_chrdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210b50)
Location: fs/char_dev.c:309
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff81210b50-ffffffff81210b80: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812375f0)
Location: fs/char_dev.c:313
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff812375f0-ffffffff81237620: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a2a0)
Location: fs/char_dev.c:313
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff8124a2a0-ffffffff8124a2d0: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255bc0)
Location: fs/char_dev.c:313
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff81255bc0-ffffffff81255bf0: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277d50)
Location: fs/char_dev.c:338
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff81277d50-ffffffff81277d80: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129e6b0)
Location: fs/char_dev.c:338
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff8129e6b0-ffffffff8129e6e0: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3990)
Location: fs/char_dev.c:338
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff812b3990-ffffffff812b39c0: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d0690)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff812d0690-ffffffff812d06c2: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e2230)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff812e2230-ffffffff812e2262: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813197d0)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff813197d0-ffffffff8131981d: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81324eb0)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove
```
**Symbols:**

```
ffffffff81324eb0-ffffffff81324efd: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132ae80)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff8132ae80-ffffffff8132aecd: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81378590)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff81378590-ffffffff813785dd: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f79a0)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff813f79a0-ffffffff813f79f9: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81480d50)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff81480d50-ffffffff81480da9: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b5970)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff814b5970-ffffffff814b59c9: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7c80)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fb_chrdev.c:fb_unregister_chrdev
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/gpu/drm/drm_drv.c:drm_core_init
  - drivers/accel/drm_accel.c:accel_core_exit
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff814e7c80-ffffffff814e7cd9: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff800010389990)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffff800010389990-ffff8000103899f0: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571d2c)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/mtd/mtdchar.c:cleanup_mtdchar
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
  - sound/sound_core.c:sound_remove_unit
  - sound/sound_core.c:cleanup_soundcore
  - sound/sound_core.c:init_soundcore
  - sound/core/sound.c:alsa_sound_exit
  - sound/core/sound.c:alsa_sound_init
```
**Symbols:**

```
c0571d2c-c0571d68: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000480410)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
c000000000480410-c000000000480470: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025bb50)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffe00025bb50-ffffffe00025bba4: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da810)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff812da810-ffffffff812da842: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb490)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff812cb490-ffffffff812cb4c2: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d8620)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff812d8620-ffffffff812d8652: __unregister_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __unregister_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e9510)
Location: fs/char_dev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_cleanup
```
**Symbols:**

```
ffffffff812e9510-ffffffff812e9542: __unregister_chrdev (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
