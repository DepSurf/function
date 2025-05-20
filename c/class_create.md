# Function: <code>class_create</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct class *class_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b3b110)
Location: drivers/base/class.c:256
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/tty/vt/vc_screen.c:vcs_init
  - drivers/tty/vt/vt.c:vtconsole_class_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
  - drivers/usb/core/file.c:usb_register_dev
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
ffffffff81b3b110-ffffffff81b3b18c: class_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct class *class_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b92c30)
Location: drivers/base/class.c:255
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_core_init
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/sg.c:init_sg
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/rtc/class.c:rtc_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/power/supply/power_supply_core.c:power_supply_class_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - drivers/devfreq/devfreq-event.c:devfreq_event_init
  - drivers/extcon/extcon.c:extcon_class_init
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff81b92c30-ffffffff81b92cd9: class_create (STB_GLOBAL)
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
