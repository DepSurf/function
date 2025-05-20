# Function: <code>device_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815470d0)
Location: drivers/base/core.c:1850
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nvdimm_bus_destroy_ndctl
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
```
**Symbols:**

```
ffffffff815470d0-ffffffff81547113: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81598d50)
Location: drivers/base/core.c:1850
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
```
**Symbols:**

```
ffffffff81598d50-ffffffff81598d93: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c7810)
Location: drivers/base/core.c:2441
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff815c7810-ffffffff815c7853: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dc500)
Location: drivers/base/core.c:2439
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff815dc500-ffffffff815dc543: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81643540)
Location: drivers/base/core.c:2574
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81643540-ffffffff81643583: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167e640)
Location: drivers/base/core.c:2621
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:__unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8167e640-ffffffff8167e683: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169e050)
Location: drivers/base/core.c:2696
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:__unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8169e050-ffffffff8169e093: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d6420)
Location: drivers/base/core.c:2950
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff816d6420-ffffffff816d6464: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fa460)
Location: drivers/base/core.c:2980
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff816fa460-ffffffff816fa4c7: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b3530)
Location: drivers/base/core.c:3448
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff817b3530-ffffffff817b3595: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c80c0)
Location: drivers/base/core.c:3860
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff817c80c0-ffffffff817c8125: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ab5d0)
Location: drivers/base/core.c:4087
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff817ab5d0-ffffffff817ab635: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81834a50)
Location: drivers/base/core.c:4152
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff81834a50-ffffffff81834ab5: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819765a0)
Location: drivers/base/core.c:4186
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff819765a0-ffffffff81976612: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae26e0)
Location: drivers/base/core.c:4405
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff81ae26e0-ffffffff81ae2752: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_destroy(const struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b30600)
Location: drivers/base/core.c:4408
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:unregister_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff81b30600-ffffffff81b30672: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_destroy(const struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b87e00)
Location: drivers/base/core.c:4421
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbsysfs.c:fb_device_destroy
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff81b87e00-ffffffff81b87e72: device_destroy (STB_GLOBAL)
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
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4c78)
Location: drivers/base/core.c:2980
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffff8000108e4c78-ffff8000108e4d00: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d36b4)
Location: drivers/base/core.c:2980
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/mtd/mtdcore.c:mtd_release
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
  - sound/sound_core.c:sound_remove_unit
```
**Symbols:**

```
c09d36b4-c09d3734: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097a1f0)
Location: drivers/base/core.c:2980
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
c00000000097a1f0-c00000000097a284: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000579a94)
Location: drivers/base/core.c:2980
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffe000579a94-ffffffe000579aec: device_destroy (STB_GLOBAL)
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
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bfc50)
Location: drivers/base/core.c:2980
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff816bfc50-ffffffff816bfcb7: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169af00)
Location: drivers/base/core.c:2980
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff8169af00-ffffffff8169af67: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ee120)
Location: drivers/base/core.c:2980
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff816ee120-ffffffff816ee187: device_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_destroy(struct class *class, dev_t devt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81708960)
Location: drivers/base/core.c:2980
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - drivers/video/fbdev/core/fbmem.c:unlink_framebuffer
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vc_screen.c:vcs_remove_sysfs
  - drivers/tty/vt/vt.c:con_driver_unregister_callback
  - drivers/char/misc.c:misc_deregister
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/pps/pps.c:pps_unregister_cdev
```
**Symbols:**

```
ffffffff81708960-ffffffff817089c7: device_destroy (STB_GLOBAL)
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
