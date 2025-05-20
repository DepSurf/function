# Function: <code>device_remove_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815464f0)
Location: drivers/base/core.c:611
Inline: True
Inline callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/bus.c:bus_add_device
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_dh.c:scsi_dh_remove_device
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
```
**Symbols:**

```
ffffffff815464f0-ffffffff8154650c: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81598b63)
Location: drivers/base/core.c:611
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/bus.c:bus_add_device
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81598160-ffffffff8159817c: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c7614)
Location: drivers/base/core.c:1177
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_remove_sysfs_dev_files
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/bus.c:bus_add_device
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff815c5d30-ffffffff815c5d4c: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dc2bc)
Location: drivers/base/core.c:1175
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff815dab50-ffffffff815dab6d: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81643250)
Location: drivers/base/core.c:1310
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff81641b00-ffffffff81641b1d: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167e35e)
Location: drivers/base/core.c:1352
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff8167cda0-ffffffff8167cdbc: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169dd6e)
Location: drivers/base/core.c:1426
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff8169c730-ffffffff8169c74c: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d615b)
Location: drivers/base/core.c:1571
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff816d5540-ffffffff816d5558: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fa198)
Location: drivers/base/core.c:1608
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff816f92f0-ffffffff816f9308: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b3319)
Location: drivers/base/core.c:2086
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - mm/dmapool.c:dma_pool_destroy
  - block/partitions/core.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817b21c0-ffffffff817b21d8: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7bf6)
Location: drivers/base/core.c:2496
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817c6a90-ffffffff817c6aa8: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ab106)
Location: drivers/base/core.c:2708
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817a9f50-ffffffff817a9f68: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81834456)
Location: drivers/base/core.c:2773
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff818330d0-ffffffff818330e8: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff81975f1c)
Location: drivers/base/core.c:2798
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff819757c0-ffffffff819757dc: device_remove_file.part.0 (STB_LOCAL)
ffffffff81975ba0-ffffffff81975bcc: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff81ae1fcc)
Location: drivers/base/core.c:2996
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81ae1350-ffffffff81ae136c: device_remove_file.part.0 (STB_LOCAL)
ffffffff81ae1a50-ffffffff81ae1a7c: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff81b2fecb)
Location: drivers/base/core.c:3002
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b2f5a0-ffffffff81b2f5bc: device_remove_file.part.0 (STB_LOCAL)
ffffffff81b2f870-ffffffff81b2f89c: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff81b876cb)
Location: drivers/base/core.c:3017
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_driver_bound
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_device_destroy
  - drivers/video/fbdev/core/fbsysfs.c:fb_device_create
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/thermal/thermal_core.c:thermal_unbind_cdev_from_trip
  - drivers/thermal/thermal_core.c:thermal_unbind_cdev_from_trip
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b86da0-ffffffff81b86dbc: device_remove_file.part.0 (STB_LOCAL)
ffffffff81b87070-ffffffff81b8709c: device_remove_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4988)
Location: drivers/base/core.c:1608
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffff8000108e34c8-ffff8000108e3504: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d33a4)
Location: drivers/base/core.c:1608
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/sm501.c:sm501_dev_remove
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
c09d1f58-c09d1f80: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000979e0c)
Location: drivers/base/core.c:1608
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/powerpc/kernel/sysfs.c:cpu_remove_dev_attr
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_remove_device
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_remove_device
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_remove_device
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_remove_device
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
c0000000009784d0-c000000000978510: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe0005797fe)
Location: drivers/base/core.c:1608
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffe000578872-ffffffe0005788a8: device_remove_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf988)
Location: drivers/base/core.c:1608
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
```
**Symbols:**

```
ffffffff816beae0-ffffffff816beaf8: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169ac38)
Location: drivers/base/core.c:1608
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
```
**Symbols:**

```
ffffffff81699d90-ffffffff81699da8: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ede58)
Location: drivers/base/core.c:1608
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff816ecfb0-ffffffff816ecfc8: device_remove_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void device_remove_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81708698)
Location: drivers/base/core.c:1608
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/events/core.c:perf_pmu_unregister
  - mm/compaction.c:compaction_unregister_node
  - block/partition-generic.c:add_partition
  - drivers/pci/pci-sysfs.c:pci_remove_sysfs_dev_files
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_remove_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_cleanup_device
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/power.c:acpi_power_sysfs_remove
  - drivers/acpi/battery.c:sysfs_remove_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/attribute_container.c:attribute_container_remove_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_exit
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/scsi/scsi_sysfs.c:sdev_store_delete
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_remove_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817077f0-ffffffff81707808: device_remove_file (STB_GLOBAL)
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
