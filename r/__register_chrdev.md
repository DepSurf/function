# Function: <code>__register_chrdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210ea0)
Location: fs/char_dev.c:242
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
```
**Symbols:**

```
ffffffff81210ea0-ffffffff81210f77: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81237970)
Location: fs/char_dev.c:246
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff81237970-ffffffff81237a3e: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a620)
Location: fs/char_dev.c:246
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff8124a620-ffffffff8124a6ee: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812561d0)
Location: fs/char_dev.c:246
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff812561d0-ffffffff8125629e: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812783e0)
Location: fs/char_dev.c:271
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff812783e0-ffffffff812784ae: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129eb60)
Location: fs/char_dev.c:271
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff8129eb60-ffffffff8129ec39: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3ac0)
Location: fs/char_dev.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff812b3ac0-ffffffff812b3b99: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d07d0)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff812d07d0-ffffffff812d08a2: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e2380)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff812e2380-ffffffff812e2452: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81319550)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff81319550-ffffffff81319622: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81324c30)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff81324c30-ffffffff81324d02: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132ad00)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff8132ad00-ffffffff8132add2: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81378410)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff81378410-ffffffff813784e2: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f7770)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff813f7770-ffffffff813f784d: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81480ae0)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff81480ae0-ffffffff81480bbd: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b5700)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff814b5700-ffffffff814b57dd: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7a10)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fb_chrdev.c:fb_register_chrdev
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/gpu/drm/drm_drv.c:drm_core_init
  - drivers/accel/drm_accel.c:accel_core_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff814e7a10-ffffffff814e7aed: __register_chrdev (STB_GLOBAL)
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff800010389b38)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffff800010389b38-ffff800010389c54: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571e8c)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/mtd/mtdchar.c:init_mtdchar
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
  - sound/sound_core.c:init_soundcore
  - sound/core/sound.c:alsa_sound_init
```
**Symbols:**

```
c0571e8c-c0571f4c: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000481110)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
c000000000481110-c0000000004812e4: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025bcc4)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffe00025bcc4-ffffffe00025bda6: __register_chrdev (STB_GLOBAL)
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
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da960)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff812da960-ffffffff812daa32: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb5e0)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff812cb5e0-ffffffff812cb6b2: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d8770)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff812d8770-ffffffff812d8842: __register_chrdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __register_chrdev(unsigned int major, unsigned int baseminor, unsigned int count, const char *name, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e9660)
Location: fs/char_dev.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_major_init
```
**Symbols:**

```
ffffffff812e9660-ffffffff812e9732: __register_chrdev (STB_GLOBAL)
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
