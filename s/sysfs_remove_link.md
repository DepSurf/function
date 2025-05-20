# Function: <code>sysfs_remove_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8128ced0)
Location: fs/sysfs/symlink.c:142
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/bsg.c:bsg_unregister_queue
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_del
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:level_store
  - drivers/md/md.c:do_md_stop
  - net/core/dev.c:netdev_adjacent_sysfs_del
  - net/core/dev.c:__netdev_adjacent_dev_remove
```
**Symbols:**

```
ffffffff8128ced0-ffffffff8128cefb: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff812ba550)
Location: fs/sysfs/symlink.c:142
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/bsg.c:bsg_unregister_queue
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff812ba550-ffffffff812ba57b: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff812cfc80)
Location: fs/sysfs/symlink.c:142
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/bsg.c:bsg_unregister_queue
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff812cfc80-ffffffff812cfcab: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff812dd350)
Location: fs/sysfs/symlink.c:142
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff812dd350-ffffffff812dd37b: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff81301c80)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff81301c80-ffffffff81301cab: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8132fb20)
Location: fs/sysfs/symlink.c:142
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff8132fb20-ffffffff8132fb4b: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff81346ed0)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff81346ed0-ffffffff81346efb: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8136f230)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff8136f230-ffffffff8136f25b: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff813875a0)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff813875a0-ffffffff813875cb: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff813d2270)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff813d2270-ffffffff813d229b: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff813e3f90)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/regulator/core.c:destroy_regulator
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:netdev_adjacent_del_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff813e3f90-ffffffff813e3fbb: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff813eab90)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff813eab90-ffffffff813eabbb: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8143c910)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_unregister_queue
  - block/holder.c:bd_register_pending_holders
  - block/holder.c:bd_register_pending_holders
  - block/holder.c:bd_register_pending_holders
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff8143c910-ffffffff8143c93b: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff814b8150)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_unregister_queue
  - block/holder.c:bd_register_pending_holders
  - block/holder.c:bd_register_pending_holders
  - block/holder.c:bd_register_pending_holders
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/regulator/core.c:_regulator_put
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:connector_unbind
  - drivers/usb/core/port.c:connector_unbind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff814b8150-ffffffff814b8193: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8154f6e0)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_unregister_queue
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/regulator/core.c:_regulator_put
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:connector_unbind
  - drivers/usb/core/port.c:connector_unbind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff8154f6e0-ffffffff8154f723: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff815873b0)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_unregister_queue
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/acpi/thermal.c:acpi_thermal_register_thermal_zone
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/regulator/core.c:_regulator_put
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:__iommu_group_release_device
  - drivers/iommu/iommu.c:__iommu_group_release_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:connector_unbind
  - drivers/usb/core/port.c:connector_unbind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff815873b0-ffffffff815873f3: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff815bff40)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_alias
  - mm/slub.c:sysfs_slab_add
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_unregister_queue
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/fan_core.c:acpi_fan_remove
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_exit
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/regulator/core.c:_regulator_put
  - drivers/iommu/iommu.c:iommu_group_alloc_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_remove_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/core.c:devlink_add_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:really_probe
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_remove_early
  - drivers/gpu/drm/drm_sysfs.c:typec_connector_unbind
  - drivers/gpu/drm/drm_sysfs.c:typec_connector_unbind
  - drivers/gpu/drm/drm_sysfs.c:typec_connector_bind
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:connector_unbind
  - drivers/usb/core/port.c:connector_unbind
  - drivers/usb/core/port.c:connector_bind
  - drivers/usb/core/port.c:link_peers
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_unbind_cdev_from_trip
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:netdev_adjacent_rename_links
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
**Symbols:**

```
ffffffff815bff40-ffffffff815bff83: sysfs_remove_link (STB_GLOBAL)
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
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffff800010457468)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffff800010457468-ffff8000104574c4: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (c0619554)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
c0619554-c0619588: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (c0000000005718c0)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - arch/powerpc/kernel/sysfs.c:sysfs_remove_device_from_node
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
c0000000005718c0-c000000000571938: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffe0002e892a)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffe0002e892a-ffffffe0002e896a: sysfs_remove_link (STB_GLOBAL)
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
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8137fb80)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/nvme/host/core.c:nvme_free_ctrl
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff8137fb80-ffffffff8137fbab: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff81370610)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/scsi_transport_fc.c:fc_vport_terminate
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/nvme/host/core.c:nvme_free_ctrl
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff81370610-ffffffff8137063b: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff8137d650)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff8137d650-ffffffff8137d67b: sysfs_remove_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sysfs_remove_link(struct kobject *kobj, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/symlink.c (ffffffff81391130)
Location: fs/sysfs/symlink.c:143
Inline: False
Direct callers:
  - kernel/module.c:del_usage_links
  - mm/slub.c:sysfs_slab_add
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_link_disk_holder
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - drivers/pci/slot.c:pci_hp_remove_module_link
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_remove
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/dd.c:driver_sysfs_add
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_remove_link
  - drivers/base/class.c:class_compat_create_link
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/module.c:module_remove_driver
  - drivers/base/module.c:module_remove_driver
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:level_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - net/core/dev.c:netdev_adjacent_sysfs_del
```
**Symbols:**

```
ffffffff81391130-ffffffff8139115b: sysfs_remove_link (STB_GLOBAL)
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
