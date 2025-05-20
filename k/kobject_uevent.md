# Function: <code>kobject_uevent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff813ed110)
Location: lib/kobject_uevent.c:372
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/module.c:store_uevent
  - kernel/module.c:load_module
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove
  - block/elevator.c:elv_register_queue
  - block/elevator.c:elv_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-mq-sysfs.c:blk_mq_unregister_disk
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/genhd.c:add_disk
  - block/genhd.c:add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:invalidate_partitions
  - block/blk-integrity.c:blk_integrity_add
  - block/blk-integrity.c:blk_integrity_del
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kset_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/scan.c:acpi_device_add_finalize
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/base/core.c:device_del
  - drivers/base/core.c:uevent_store
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:device_online
  - drivers/base/bus.c:uevent_store
  - drivers/base/bus.c:bus_uevent_store
  - drivers/base/driver.c:driver_register
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/block/loop.c:figure_loop_size
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:lo_ioctl
  - drivers/power/power_supply_core.c:power_supply_changed_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:do_md_stop
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_update_state
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_uevent_work
```
**Symbols:**

```
ffffffff813ed110-ffffffff813ed11d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81433520)
Location: lib/kobject_uevent.c:372
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/module.c:load_module
  - kernel/module.c:store_uevent
  - mm/slub.c:sysfs_slab_remove
  - mm/slub.c:sysfs_slab_add
  - block/elevator.c:elv_unregister_queue
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/blk-mq-sysfs.c:__blk_mq_unregister_disk
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_device_add_finalize
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:uevent_store
  - drivers/base/bus.c:bus_uevent_store
  - drivers/base/bus.c:uevent_store
  - drivers/base/driver.c:driver_register
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/power_supply_core.c:power_supply_changed_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_update_state
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
**Symbols:**

```
ffffffff81433520-ffffffff8143352d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8144f790)
Location: lib/kobject_uevent.c:372
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/module.c:load_module
  - kernel/module.c:store_uevent
  - mm/slub.c:sysfs_slab_remove
  - mm/slub.c:sysfs_slab_add
  - block/elevator.c:elv_unregister_queue
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_unregister_dev
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_device_add_finalize
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:uevent_store
  - drivers/base/bus.c:bus_uevent_store
  - drivers/base/bus.c:uevent_store
  - drivers/base/driver.c:driver_register
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
**Symbols:**

```
ffffffff8144f790-ffffffff8144f79d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff818ef940)
Location: lib/kobject_uevent.c:513
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/module.c:load_module
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/driver.c:driver_register
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff818ef940-ffffffff818ef94d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81975d80)
Location: lib/kobject_uevent.c:564
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/module.c:load_module
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81975d80-ffffffff81975d8d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff819d2570)
Location: lib/kobject_uevent.c:634
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff819d2570-ffffffff819d257d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0b920)
Location: lib/kobject_uevent.c:636
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81a0b920-ffffffff81a0b92d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a7b300)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81a7b300-ffffffff81a7b30d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ab2660)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81ab2660-ffffffff81ab266d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815ecaa0)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:kernel_add_sysfs_param
  - kernel/module.c:mod_sysfs_setup
  - fs/block_dev.c:bdev_disk_changed
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:__kobject_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/power/supply/charger-manager.c:uevent_notify
  - drivers/power/supply/charger-manager.c:uevent_notify
  - drivers/hwmon/hwmon.c:hwmon_notify_event
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
**Symbols:**

```
ffffffff815ecaa0-ffffffff815ecaad: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81611280)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:kernel_add_sysfs_param
  - kernel/module.c:do_init_module
  - fs/block_dev.c:bdev_disk_changed
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:__kobject_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:wakeup_sysfs_add
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/hwmon/hwmon.c:hwmon_notify_event
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
**Symbols:**

```
ffffffff81611280-ffffffff8161128d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815f4940)
Location: lib/kobject_uevent.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/module.c:do_init_module
  - fs/block_dev.c:bdev_disk_changed
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:__kobject_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:wakeup_sysfs_add
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/hwmon/hwmon.c:hwmon_notify_event
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_device_register
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
**Symbols:**

```
ffffffff815f4940-ffffffff815f494d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81661d10)
Location: lib/kobject_uevent.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/module.c:do_init_module
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:__kobject_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:wakeup_sysfs_add
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/hwmon/hwmon.c:hwmon_notify_event
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_device_register
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
**Symbols:**

```
ffffffff81661d10-ffffffff81661d1d: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8177ba10)
Location: lib/kobject_uevent.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/module/main.c:do_init_module
  - block/elevator.c:elv_unregister_queue
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:__kobject_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:wakeup_sysfs_add
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/roles/class.c:usb_role_switch_set_role
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_device_register
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
**Symbols:**

```
ffffffff8177ba10-ffffffff8177ba27: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff82024c60)
Location: lib/kobject_uevent.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/module/main.c:do_init_module
  - block/elevator.c:elv_unregister_queue
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:wakeup_sysfs_add
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/roles/class.c:usb_role_switch_set_role
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:__kobject_del
```
**Symbols:**

```
ffffffff82024c60-ffffffff82024c77: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff820a4d70)
Location: lib/kobject_uevent.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/module/main.c:do_init_module
  - block/elevator.c:elv_unregister_queue
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:add_partition
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:wakeup_sysfs_add
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/usb/core/sysfs.c:usb_update_wireless_status_attr
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/roles/class.c:usb_role_switch_set_role
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:__kobject_del
```
**Symbols:**

```
ffffffff820a4d70-ffffffff820a4d87: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8217cea0)
Location: lib/kobject_uevent.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/module/main.c:do_init_module
  - block/elevator.c:elv_unregister_queue
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:blk_add_partitions
  - block/partitions/core.c:add_partition
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_sysfs_link
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:wakeup_sysfs_add
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/usb/core/sysfs.c:usb_update_wireless_status_attr
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/usb/roles/class.c:usb_role_switch_set_role
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:__kobject_del
```
**Symbols:**

```
ffffffff8217cea0-ffffffff8217ceb7: kobject_uevent (STB_GLOBAL)
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
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffff800010d8c7d8)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffff800010d8c7d8-ffff800010d8c7f0: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (c0e86bb8)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/usb/gadget/udc/core.c:udc_bind_to_driver
  - drivers/usb/gadget/udc/core.c:usb_del_gadget_udc
  - drivers/usb/gadget/udc/core.c:usb_gadget_remove_driver
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
c0e86bb8-c0e86bd0: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (c000000000ece8f0)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/platforms/powernv/opal-elog.c:elog_event
  - arch/powerpc/platforms/powernv/opal-dump.c:process_dump
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
c000000000ece8f0-c000000000ece900: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffe0008b5980)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffe0008b5980-ffffffe0008b599a: kobject_uevent (STB_GLOBAL)
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
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a514b0)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/container.c:container_device_online
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81a514b0-ffffffff81a514bd: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0e5b0)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/container.c:container_device_online
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/hv/vmbus_drv.c:vmbus_add_channel_kobj
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81a0e5b0-ffffffff81a0e5bd: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81abd8a0)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81abd8a0-ffffffff81abd8ad: kobject_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kobject_uevent(struct kobject *kobj, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ac9d20)
Location: lib/kobject_uevent.c:639
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:invalidate_partitions
  - block/partition-generic.c:rescan_partitions
  - block/partition-generic.c:add_partition
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/container.c:container_device_online
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_bound
  - drivers/base/driver.c:driver_register
  - drivers/base/swnode.c:swnode_register
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:figure_loop_size
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81ac9d20-ffffffff81ac9d2d: kobject_uevent (STB_GLOBAL)
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
