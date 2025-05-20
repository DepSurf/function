# Function: <code>sysfs_create_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8128d060)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:add_disk
  - block/genhd.c:add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_run
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff8128d060-ffffffff8128d096: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff812ba6e0)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff812ba6e0-ffffffff812ba716: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff812cfe10)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff812cfe10-ffffffff812cfe46: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff812dd4f0)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff812dd4f0-ffffffff812dd526: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff81301e20)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff81301e20-ffffffff81301e56: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8132fcd0)
Location: fs/sysfs/symlink.c:88
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff8132fcd0-ffffffff8132fd06: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff81347070)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff81347070-ffffffff813470a6: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8136f3b0)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff8136f3b0-ffffffff8136f3e6: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff81387730)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff81387730-ffffffff81387766: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff813d2400)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff813d2400-ffffffff813d2432: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff813e4120)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:netdev_adjacent_add_links
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff813e4120-ffffffff813e4152: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff813ead20)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_device_register
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff813ead20-ffffffff813ead52: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8143caa0)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - block/holder.c:bd_register_pending_holders
  - block/holder.c:bd_register_pending_holders
  - block/holder.c:bd_link_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/firmware/edd.c:edd_device_register
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff8143caa0-ffffffff8143cad2: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff814b8100)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - block/holder.c:bd_register_pending_holders
  - block/holder.c:bd_register_pending_holders
  - block/holder.c:bd_link_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/firmware/edd.c:edd_device_register
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff814b8100-ffffffff814b814a: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8154f680)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - block/holder.c:bd_link_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff8154f680-ffffffff8154f6ca: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff81587350)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - block/holder.c:bd_link_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff81587350-ffffffff8158739a: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff815bfee0)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_alias
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - block/holder.c:bd_link_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/iommu/iommu.c:iommu_group_alloc_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/gpu/drm/drm_drv.c:drm_dev_register
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add_late
  - drivers/gpu/drm/drm_sysfs.c:typec_connector_bind
  - drivers/gpu/drm/drm_sysfs.c:typec_connector_bind
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff815bfee0-ffffffff815bff2a: sysfs_create_link (STB_GLOBAL)
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
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffff8000104576e0)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffff8000104576e0-ffff800010457744: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (c06194cc)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
c06194cc-c0619510: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (c000000000571bd0)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - arch/powerpc/kernel/sysfs.c:sysfs_add_device_to_node
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
c000000000571bd0-c000000000571c18: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffe0002e8afc)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffe0002e8afc-ffffffe0002e8b4c: sysfs_create_link (STB_GLOBAL)
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
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8137fd10)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff8137fd10-ffffffff8137fd46: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff813707a0)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/scsi/scsi_transport_fc.c:fc_vport_setup
  - drivers/scsi/sg.c:sg_add_device
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff813707a0-ffffffff813707d6: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8137d7e0)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff8137d7e0-ffffffff8137d816: sysfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_create_link(struct kobject *kobj, struct kobject *target, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff813912d0)
Location: fs/sysfs/symlink.c:89
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bd_link_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_register_queue
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_add_driver
  - drivers/base/module.c:module_add_driver
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_powers
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
  - drivers/firmware/edd.c:edd_init
  - net/core/dev.c:netdev_adjacent_sysfs_add
```
**Symbols:**

```
ffffffff813912d0-ffffffff81391306: sysfs_create_link (STB_GLOBAL)
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
