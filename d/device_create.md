# Function: <code>device_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81548c90)
Location: drivers/base/core.c:1778
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff81548c90-ffffffff81548cf8: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159a8c0)
Location: drivers/base/core.c:1778
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_register_dev
```
**Symbols:**

```
ffffffff8159a8c0-ffffffff8159a928: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c8e20)
Location: drivers/base/core.c:2369
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_register_dev
```
**Symbols:**

```
ffffffff815c8e20-ffffffff815c8e88: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815ddb40)
Location: drivers/base/core.c:2367
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff815ddb40-ffffffff815ddb9f: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81644b40)
Location: drivers/base/core.c:2502
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff81644b40-ffffffff81644b9f: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167ff60)
Location: drivers/base/core.c:2549
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff8167ff60-ffffffff8167ffbf: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169eca0)
Location: drivers/base/core.c:2624
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff8169eca0-ffffffff8169ecff: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d7250)
Location: drivers/base/core.c:2878
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff816d7250-ffffffff816d72af: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fb350)
Location: drivers/base/core.c:2915
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff816fb350-ffffffff816fb3af: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b4570)
Location: drivers/base/core.c:3382
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff817b4570-ffffffff817b45cf: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817cab90)
Location: drivers/base/core.c:3794
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff817cab90-ffffffff817cabef: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ae500)
Location: drivers/base/core.c:4021
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff817ae500-ffffffff817ae55f: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81837720)
Location: drivers/base/core.c:4086
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff81837720-ffffffff8183777f: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81979800)
Location: drivers/base/core.c:4120
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - mm/backing-dev.c:bdi_register_va
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff81979800-ffffffff8197987f: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae6300)
Location: drivers/base/core.c:4339
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - mm/backing-dev.c:bdi_register_va
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff81ae6300-ffffffff81ae637f: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *device_create(const struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b346a0)
Location: drivers/base/core.c:4345
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - mm/backing-dev.c:bdi_register_va
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff81b346a0-ffffffff81b3471f: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *device_create(const struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8c0d0)
Location: drivers/base/core.c:4358
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - mm/backing-dev.c:bdi_register_va
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbsysfs.c:fb_device_create
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff81b8c0d0-ffffffff81b8c14f: device_create (STB_GLOBAL)
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
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e5a00)
Location: drivers/base/core.c:2915
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/bus/vexpress-config.c:vexpress_config_bridge_register
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffff8000108e5a00-ffff8000108e5ac0: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d40e8)
Location: drivers/base/core.c:2915
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/bus/vexpress-config.c:vexpress_config_bridge_register
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
c09d40e8-c09d4158: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097b4d0)
Location: drivers/base/core.c:2915
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
c00000000097b4d0-c00000000097b51c: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057a678)
Location: drivers/base/core.c:2915
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffe00057a678-ffffffe00057a6d6: device_create (STB_GLOBAL)
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
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c0b40)
Location: drivers/base/core.c:2915
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff816c0b40-ffffffff816c0b9f: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169bdf0)
Location: drivers/base/core.c:2915
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - block/bsg.c:bsg_register_queue
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff8169bdf0-ffffffff8169be4f: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ef010)
Location: drivers/base/core.c:2915
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff816ef010-ffffffff816ef06f: device_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *device_create(struct class *class, struct device *parent, dev_t devt, void *drvdata, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81709670)
Location: drivers/base/core.c:2915
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - block/bsg.c:bsg_register_queue
  - drivers/pwm/sysfs.c:pwmchip_sysfs_export
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_make_sysfs
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff81709670-ffffffff817096cf: device_create (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class *class</code> ➡️ <code>const struct class *class</code>
</li>
</ul>
</details>
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
