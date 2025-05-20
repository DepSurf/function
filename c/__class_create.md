# Function: <code>__class_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8154d4c0)
Location: drivers/base/class.c:239
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/power/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
```
**Symbols:**

```
ffffffff8154d4c0-ffffffff8154d53b: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8159f2b0)
Location: drivers/base/class.c:239
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/power/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
```
**Symbols:**

```
ffffffff8159f2b0-ffffffff8159f328: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815cd8b0)
Location: drivers/base/class.c:254
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
```
**Symbols:**

```
ffffffff815cd8b0-ffffffff815cd928: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815e2310)
Location: drivers/base/class.c:221
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
```
**Symbols:**

```
ffffffff815e2310-ffffffff815e2388: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81649480)
Location: drivers/base/class.c:221
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
```
**Symbols:**

```
ffffffff81649480-ffffffff816494f8: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81684a30)
Location: drivers/base/class.c:219
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_class_init
  - mm/hmm.c:hmm_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
ffffffff81684a30-ffffffff81684ab2: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a46e0)
Location: drivers/base/class.c:219
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - mm/hmm.c:hmm_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
ffffffff816a46e0-ffffffff816a4762: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816dd5f0)
Location: drivers/base/class.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
ffffffff816dd5f0-ffffffff816dd66f: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817016a0)
Location: drivers/base/class.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
ffffffff817016a0-ffffffff8170171f: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817bb250)
Location: drivers/base/class.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/dma-buf/dma-heap.c:dma_heap_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:init_usb_class
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff817bb250-ffffffff817bb2d2: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817cfe40)
Location: drivers/base/class.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/dma-buf/dma-heap.c:dma_heap_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:init_usb_class
  - drivers/usb/roles/class.c:usb_roles_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff817cfe40-ffffffff817cfec2: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817b3850)
Location: drivers/base/class.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/dma-buf/dma-heap.c:dma_heap_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/roles/class.c:usb_roles_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff817b3850-ffffffff817b38d2: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8183cd30)
Location: drivers/base/class.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/dma-buf/dma-heap.c:dma_heap_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/roles/class.c:usb_roles_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff8183cd30-ffffffff8183cdb2: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8197f8b0)
Location: drivers/base/class.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dma-buf/dma-heap.c:dma_heap_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/usb/roles/class.c:usb_roles_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:create_extcon_class
```
**Symbols:**

```
ffffffff8197f8b0-ffffffff8197f945: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81aed1a0)
Location: drivers/base/class.c:231
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dma-buf/dma-heap.c:dma_heap_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/usb/roles/class.c:usb_roles_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
  - drivers/extcon/extcon.c:extcon_class_init
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff81aed1a0-ffffffff81aed235: __class_create (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffff8000108ec608)
Location: drivers/base/class.c:225
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/bus/vexpress-config.c:vexpress_config_bridge_register
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/roles/class.c:usb_roles_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
ffff8000108ec608-ffff8000108ec6a0: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c09da4f0)
Location: drivers/base/class.c:225
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/bus/vexpress-config.c:vexpress_config_bridge_register
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/gadget/udc/core.c:usb_udc_init
  - drivers/usb/roles/class.c:usb_roles_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
  - sound/sound_core.c:init_soundcore
```
**Symbols:**

```
c09da4f0-c09da574: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c000000000984b70)
Location: drivers/base/class.c:225
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
c000000000984b70-c000000000984c58: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffe000580126)
Location: drivers/base/class.c:225
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
ffffffe000580126-ffffffe0005801a6: __class_create (STB_GLOBAL)
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
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816c6e90)
Location: drivers/base/class.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/rtc/class.c:rtc_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
ffffffff816c6e90-ffffffff816c6f0f: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a20f0)
Location: drivers/base/class.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/rtc/class.c:rtc_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
ffffffff816a20f0-ffffffff816a216f: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816f5360)
Location: drivers/base/class.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
ffffffff816f5360-ffffffff816f53df: __class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct class *__class_create(struct module *owner, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170fbf0)
Location: drivers/base/class.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - mm/backing-dev.c:bdi_class_init
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/tty_io.c:tty_class_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/mem.c:chr_dev_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/class.c:rtc_init
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/leds/led-class.c:leds_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
```
**Symbols:**

```
ffffffff8170fbf0-ffffffff8170fc6f: __class_create (STB_GLOBAL)
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
