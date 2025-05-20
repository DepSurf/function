# Function: <code>device_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81546460)
Location: drivers/base/core.c:587
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_dh.c:scsi_dh_add_device
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81546460-ffffffff815464eb: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815980d0)
Location: drivers/base/core.c:587
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff815980d0-ffffffff8159815b: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c5ca0)
Location: drivers/base/core.c:1153
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files
  - drivers/rapidio/rio-sysfs.c:rio_create_sysfs_dev_files
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff815c5ca0-ffffffff815c5d2b: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815daad0)
Location: drivers/base/core.c:1151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/video/console/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff815daad0-ffffffff815dab4d: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81641a80)
Location: drivers/base/core.c:1286
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff81641a80-ffffffff81641afd: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167d690)
Location: drivers/base/core.c:1328
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff8167d690-ffffffff8167d70d: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d080)
Location: drivers/base/core.c:1402
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff8169d080-ffffffff8169d0fd: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d54c0)
Location: drivers/base/core.c:1547
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff816d54c0-ffffffff816d553e: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9270)
Location: drivers/base/core.c:1584
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff816f9270-ffffffff816f92ee: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b2140)
Location: drivers/base/core.c:2062
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:tick_init_sysfs
  - kernel/time/clockevents.c:tick_init_sysfs
  - kernel/time/clockevents.c:tick_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partitions/core.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817b2140-ffffffff817b21b8: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c6a10)
Location: drivers/base/core.c:2472
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:tick_init_sysfs
  - kernel/time/clockevents.c:tick_init_sysfs
  - kernel/time/clockevents.c:tick_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partitions/core.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817c6a10-ffffffff817c6a88: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817a9ed0)
Location: drivers/base/core.c:2684
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partitions/core.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817a9ed0-ffffffff817a9f48: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833050)
Location: drivers/base/core.c:2749
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partitions/core.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81833050-ffffffff818330c8: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819749b0)
Location: drivers/base/core.c:2774
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partitions/core.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff819749b0-ffffffff81974a3c: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae00e0)
Location: drivers/base/core.c:2972
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partitions/core.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81ae00e0-ffffffff81ae016c: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2e300)
Location: drivers/base/core.c:2978
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partitions/core.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b2e300-ffffffff81b2e38c: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b85b00)
Location: drivers/base/core.c:2993
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partitions/core.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_device_create
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b85b00-ffffffff81b85b8c: device_create_file (STB_GLOBAL)
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
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e3418)
Location: drivers/base/core.c:1584
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/arch_topology.c:register_cpu_capacity_sysctl
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffff8000108e3418-ffff8000108e34c4: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d1e90)
Location: drivers/base/core.c:1584
Inline: False
Direct callers:
  - arch/arm/mach-omap2/id.c:omap_soc_device_init
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/soc/imx/soc-imx8.c:imx8_soc_init
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/arch_topology.c:register_cpu_capacity_sysctl
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
c09d1e90-c09d1f58: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c0000000009783e0)
Location: drivers/base/core.c:1584
Inline: False
Direct callers:
  - arch/powerpc/kernel/sysfs.c:topology_init
  - arch/powerpc/kernel/sysfs.c:topology_init
  - arch/powerpc/kernel/sysfs.c:topology_init
  - arch/powerpc/kernel/sysfs.c:cpu_add_dev_attr
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_add_device
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_add_device
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_add_device
  - arch/powerpc/kernel/eeh_sysfs.c:eeh_sysfs_add_device
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/subcore.c:__machine_initcall_powernv_subcore_init
  - arch/powerpc/platforms/pseries/suspend.c:__machine_initcall_pseries_pseries_suspend_init
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/attribute_container.c:attribute_container_add_attrs
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
c0000000009783e0-c0000000009784c8: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe0005787ea)
Location: drivers/base/core.c:1584
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/arch_topology.c:register_cpu_capacity_sysctl
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffe0005787ea-ffffffe000578872: device_create_file (STB_GLOBAL)
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
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bea60)
Location: drivers/base/core.c:1584
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
```
**Symbols:**

```
ffffffff816bea60-ffffffff816beade: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81699d10)
Location: drivers/base/core.c:1584
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
```
**Symbols:**

```
ffffffff81699d10-ffffffff81699d8e: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ecf30)
Location: drivers/base/core.c:1584
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff816ecf30-ffffffff816ecfae: device_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_create_file(struct device *dev, const struct device_attribute *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81707770)
Location: drivers/base/core.c:1584
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:wq_sysfs_init
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/events/core.c:pmu_dev_alloc
  - mm/compaction.c:compaction_register_node
  - mm/dmapool.c:dma_pool_create
  - block/partition-generic.c:add_partition
  - drivers/pci/hotplug/shpchp_sysfs.c:shpchp_create_ctrl_files
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/battery.c:sysfs_add_battery
  - drivers/pnp/card.c:pnp_add_card
  - drivers/pnp/card.c:pnp_add_card
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_host
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81707770-ffffffff817077ee: device_create_file (STB_GLOBAL)
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
