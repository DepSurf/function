# Function: <code>class_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8154ccc0)
Location: drivers/base/class.c:274
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:init
  - drivers/char/virtio_console.c:fini
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/usb/core/file.c:release_usb_class
  - drivers/rtc/class.c:rtc_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/power/power_supply_core.c:power_supply_class_exit
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_exit
  - drivers/devfreq/devfreq-event.c:devfreq_event_exit
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff8154ccc0-ffffffff8154ccdf: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8159eab0)
Location: drivers/base/class.c:274
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/power/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff8159eab0-ffffffff8159eacf: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815cd070)
Location: drivers/base/class.c:289
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff815cd070-ffffffff815cd08f: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815e1b50)
Location: drivers/base/class.c:256
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff815e1b50-ffffffff815e1b70: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81648cc0)
Location: drivers/base/class.c:256
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff81648cc0-ffffffff81648ce0: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816842a0)
Location: drivers/base/class.c:254
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff816842a0-ffffffff816842bf: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a3f70)
Location: drivers/base/class.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff816a3f70-ffffffff816a3f8f: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816dcea0)
Location: drivers/base/class.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff816dcea0-ffffffff816dcebf: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81700f50)
Location: drivers/base/class.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff81700f50-ffffffff81700f6f: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817baec0)
Location: drivers/base/class.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff817baec0-ffffffff817baedf: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817cfac0)
Location: drivers/base/class.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/usb/roles/class.c:usb_roles_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff817cfac0-ffffffff817cfadf: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817b34d0)
Location: drivers/base/class.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/usb/roles/class.c:usb_roles_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff817b34d0-ffffffff817b34ef: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8183c9b0)
Location: drivers/base/class.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/usb/roles/class.c:usb_roles_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff8183c9b0-ffffffff8183c9cf: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8197f460)
Location: drivers/base/class.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtio_console_fini
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/usb/roles/class.c:usb_roles_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff8197f460-ffffffff8197f48b: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81aeccc0)
Location: drivers/base/class.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtio_console_fini
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/usb/roles/class.c:usb_roles_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff81aeccc0-ffffffff81aecceb: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void class_destroy(const struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b3b3a0)
Location: drivers/base/class.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_exit
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff81b3b3a0-ffffffff81b3b3cb: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void class_destroy(const struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b92ef0)
Location: drivers/base/class.c:288
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_core_exit
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_destroy
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff81b92ef0-ffffffff81b92f1b: class_destroy (STB_GLOBAL)
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
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffff8000108ec738)
Location: drivers/base/class.c:260
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/usb/roles/class.c:usb_roles_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffff8000108ec738-ffff8000108ec770: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c09da600)
Location: drivers/base/class.c:260
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/usb/gadget/udc/core.c:usb_udc_exit
  - drivers/usb/roles/class.c:usb_roles_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
  - sound/sound_core.c:cleanup_soundcore
```
**Symbols:**

```
c09da600-c09da62c: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c000000000984060)
Location: drivers/base/class.c:260
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
c000000000984060-c000000000984088: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffe00057fa78)
Location: drivers/base/class.c:260
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:usb_deregister_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffe00057fa78-ffffffe00057faaa: class_destroy (STB_GLOBAL)
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
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816c6740)
Location: drivers/base/class.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff816c6740-ffffffff816c675f: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a19a0)
Location: drivers/base/class.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/devfreq/devfreq.c:devfreq_init
```
**Symbols:**

```
ffffffff816a19a0-ffffffff816a19bf: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816f4c10)
Location: drivers/base/class.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff816f4c10-ffffffff816f4c2f: class_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void class_destroy(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170f4a0)
Location: drivers/base/class.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit
  - drivers/video/backlight/backlight.c:backlight_class_exit
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:fini
  - drivers/char/virtio_console.c:init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/file.c:release_usb_class
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/power/supply/power_supply_core.c:power_supply_class_exit
  - drivers/leds/led-class.c:leds_exit
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/extcon/extcon.c:extcon_class_exit
```
**Symbols:**

```
ffffffff8170f4a0-ffffffff8170f4bf: class_destroy (STB_GLOBAL)
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
<code>struct class *cls</code> ➡️ <code>const struct class *cls</code>
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
