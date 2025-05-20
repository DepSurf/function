# Function: <code>kobject_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eb7b0)
Location: lib/kobject.c:684
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - kernel/ksysfs.c:ksysfs_init
  - kernel/livepatch/core.c:klp_unregister_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:free_notes_attrs
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/padata.c:padata_free
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_exit
  - mm/hugetlb.c:hugetlb_exit
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_remove
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:walk_memory_range
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/char_dev.c:cdev_put
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-mq-sysfs.c:blk_mq_unregister_disk
  - block/blk-mq-sysfs.c:blk_mq_unregister_disk
  - block/blk-mq-sysfs.c:blk_mq_unregister_disk
  - block/blk-mq-sysfs.c:blk_mq_unregister_disk
  - block/genhd.c:put_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
  - block/partition-generic.c:add_partition
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - lib/kobject.c:kobj_kset_leave
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_create_and_add
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/bus.c:bus_create_file
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/node.c:register_one_node
  - drivers/base/module.c:module_add_driver
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
```
**Symbols:**

```
ffffffff813eb7b0-ffffffff813eb7fb: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431ba0)
Location: lib/kobject.c:684
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/ksysfs.c:ksysfs_init
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_unregister_patch
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_remove
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:walk_memory_range
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:cdev_put
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-sysfs.c:__blk_mq_unregister_disk
  - block/blk-mq-sysfs.c:__blk_mq_unregister_disk
  - block/blk-mq-sysfs.c:__blk_mq_unregister_disk
  - block/blk-mq-sysfs.c:__blk_mq_unregister_disk
  - block/genhd.c:put_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/node.c:register_one_node
  - drivers/base/module.c:module_add_driver
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81431ba0-ffffffff81431beb: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144de10)
Location: lib/kobject.c:684
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/ksysfs.c:ksysfs_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_unregister_patch
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_remove
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:walk_memory_range
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:cdev_put
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-sysfs.c:__blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:__blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:__blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:__blk_mq_unregister_dev
  - block/genhd.c:put_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/base/node.c:register_one_node
  - drivers/base/module.c:module_add_driver
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8144de10-ffffffff8144de5b: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818ee0e0)
Location: lib/kobject.c:687
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/ksysfs.c:ksysfs_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:walk_memory_range
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_exit
  - block/blk-core.c:blk_exit_rl
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:put_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/node.c:link_mem_sections
  - drivers/base/module.c:module_add_driver
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffff818ee0e0-ffffffff818ee272: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819742e0)
Location: lib/kobject.c:687
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/ksysfs.c:ksysfs_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:walk_memory_range
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_exit
  - block/blk-core.c:blk_exit_rl
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/node.c:link_mem_sections
  - drivers/base/module.c:module_add_driver
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffff819742e0-ffffffff81974323: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0a90)
Location: lib/kobject.c:701
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:walk_memory_range
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_exit
  - block/blk-core.c:blk_exit_rl
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/node.c:link_mem_sections
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffff819d0a90-ffffffff819d0ad5: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0a0b0)
Location: lib/kobject.c:701
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:walk_memory_range
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffff81a0a0b0-ffffffff81a0a0f5: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79900)
Location: lib/kobject.c:732
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_free_patch_finish
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:__elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffff81a79900-ffffffff81a79945: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab0c60)
Location: lib/kobject.c:732
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_free_patch_finish
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:__elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffff81ab0c60-ffffffff81ab0ca5: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eae80)
Location: lib/kobject.c:749
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:kernel_add_sysfs_param
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_init
  - kernel/module.c:mod_sysfs_init
  - kernel/module.c:add_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_flush_sync_list
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_register_nodes
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:register_entries
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff815eae80-ffffffff815eaee9: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f7a0)
Location: lib/kobject.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:kernel_add_sysfs_param
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_init
  - kernel/module.c:mod_sysfs_init
  - kernel/module.c:add_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_flush_sync_list
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:register_entries
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8160f7a0-ffffffff8160f809: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2ee0)
Location: lib/kobject.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:add_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:fw_devlink_link_device
  - drivers/base/core.c:fw_devlink_link_device
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_flush_sync_list
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff815f2ee0-ffffffff815f2f49: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff816600b0)
Location: lib/kobject.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:add_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/mempolicy.c:numa_init_sysfs
  - mm/slub.c:sysfs_slab_release
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:__register_chrdev
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - block/mq-deadline.c:dd_init_sched
  - block/blk-integrity.c:blk_integrity_del
  - block/holder.c:bd_unlink_disk_holder
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_flush_sync_list
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff816600b0-ffffffff81660119: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779bc0)
Location: lib/kobject.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/build_utility.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/migrate.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:__register_chrdev
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/mq-deadline.c:dd_init_sched
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_unregister
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_register
  - block/holder.c:bd_unlink_disk_holder
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_flush_sync_list
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81779bc0-ffffffff81779c55: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022bc0)
Location: lib/kobject.c:722
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/build_utility.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/memory-tiers.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:__register_chrdev
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/mq-deadline.c:dd_init_sched
  - block/blk-integrity.c:blk_integrity_del
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_unregister
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_register
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_link_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_flush_sync_list
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff82022bc0-ffffffff82022c55: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2c30)
Location: lib/kobject.c:723
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/build_utility.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/memory-tiers.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:__register_chrdev
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/mq-deadline.c:dd_init_sched
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_unregister
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_register
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_link_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:__iommu_group_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_flush_sync_list
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/bus.c:bus_get_dev_root
  - drivers/base/bus.c:bus_is_registered
  - drivers/base/bus.c:driver_find
  - drivers/base/bus.c:driver_find
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_get_kset
  - drivers/base/bus.c:bus_notify
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_uevent_store
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_probe_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:drivers_autoprobe_store
  - drivers/base/bus.c:drivers_autoprobe_show
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/class.c:class_is_registered
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:class_remove_file_ns
  - drivers/base/class.c:class_create_file_ns
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff820a2c30-ffffffff820a2cc5: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217acb0)
Location: lib/kobject.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/build_utility.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/padata.c:padata_free
  - mm/slub.c:sysfs_slab_release
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/memory-tiers.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_exit_sysfs
  - mm/huge_memory.c:hugepage_exit_sysfs
  - mm/huge_memory.c:hugepage_init_sysfs
  - mm/huge_memory.c:hugepage_init_sysfs
  - mm/huge_memory.c:hugepage_init_sysfs
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:__unregister_chrdev
  - fs/char_dev.c:__register_chrdev
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/mq-deadline.c:dd_init_sched
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_unregister
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_register
  - block/holder.c:bd_unlink_disk_holder
  - block/holder.c:bd_link_disk_holder
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:__iommu_group_remove_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_class_symlinks
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_links_flush_sync_list
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/bus.c:bus_get_dev_root
  - drivers/base/bus.c:bus_is_registered
  - drivers/base/bus.c:driver_find
  - drivers/base/bus.c:driver_find
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_get_kset
  - drivers/base/bus.c:bus_notify
  - drivers/base/bus.c:bus_unregister_notifier
  - drivers/base/bus.c:bus_register_notifier
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_uevent_store
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_probe_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_for_each_drv
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:drivers_autoprobe_store
  - drivers/base/bus.c:drivers_autoprobe_show
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/class.c:class_is_registered
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_for_each_device
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:class_remove_file_ns
  - drivers/base/class.c:class_create_file_ns
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_put_kobj
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8217acb0-ffffffff8217ad45: kobject_put (STB_GLOBAL)
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
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8ab58)
Location: lib/kobject.c:732
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:__elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_state_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_node_dup
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffff800010d8ab58-ffff800010d8ad44: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e85010)
Location: lib/kobject.c:732
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:__elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_delete_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_state_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_node_dup
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
c0e85010-c0e8522c: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecb830)
Location: lib/kobject.c:732
Inline: False
Direct callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/platforms/powernv/opal-elog.c:elog_event
  - arch/powerpc/platforms/powernv/opal-elog.c:elog_event
  - arch/powerpc/platforms/powernv/opal-elog.c:elog_event
  - arch/powerpc/platforms/powernv/opal-elog.c:elog_ack_store
  - arch/powerpc/platforms/powernv/opal-dump.c:opal_platform_dump_init
  - arch/powerpc/platforms/powernv/opal-dump.c:process_dump
  - arch/powerpc/platforms/powernv/opal-dump.c:process_dump
  - arch/powerpc/platforms/powernv/opal-dump.c:dump_ack_store
  - arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init
  - arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init
  - arch/powerpc/platforms/powernv/opal-psr.c:opal_psr_init
  - arch/powerpc/platforms/powernv/opal-sensor-groups.c:opal_sensor_groups_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_free_patch_finish
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:__elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_delete_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_node_dup
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
c000000000ecb830-c000000000ecbb24: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b40b0)
Location: lib/kobject.c:732
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:__elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_delete_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_node_dup
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffe0008b40b0-ffffffe0008b4298: kobject_put (STB_GLOBAL)
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
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4fab0)
Location: lib/kobject.c:732
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_free_patch_finish
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:__elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffff81a4fab0-ffffffff81a4faf5: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0cbb0)
Location: lib/kobject.c:732
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_free_patch_finish
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:__elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/hv/channel_mgmt.c:vmbus_add_channel_work
  - drivers/hv/channel_mgmt.c:hv_process_channel_removal
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffff81a0cbb0-ffffffff81a0cbf5: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abbea0)
Location: lib/kobject.c:732
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_free_patch_finish
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:__elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffff81abbea0-ffffffff81abbee5: kobject_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kobject_put(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac80a0)
Location: lib/kobject.c:732
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/ksysfs.c:ksysfs_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/livepatch/core.c:klp_free_patch_finish
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/livepatch/core.c:__klp_free_objects
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_kobject_put
  - kernel/module.c:free_notes_attrs
  - kernel/padata.c:padata_free
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_unregister_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/slub.c:sysfs_slab_release
  - mm/slub.c:sysfs_slab_remove_workfn
  - mm/huge_memory.c:hugepage_init
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cdev_del
  - fs/char_dev.c:__register_chrdev
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:do_sysfs_unregistration
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_sysfs_cleanup
  - block/elevator.c:__elevator_exit
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_ctx_sysfs_release
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - block/mq-deadline.c:dd_init_queue
  - block/blk-integrity.c:blk_integrity_del
  - drivers/pci/host-bridge.c:pci_put_host_bridge_device
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:pci_destroy_slot
  - drivers/pci/slot.c:pci_create_slot
  - drivers/pci/slot.c:make_slot_name
  - drivers/acpi/device_sysfs.c:acpi_hide_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_exit
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:device_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_put
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_remove_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_find
  - drivers/base/class.c:class_compat_unregister
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_put
  - drivers/base/module.c:module_add_driver
  - drivers/pps/pps.c:pps_cdev_release
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/dm-sysfs.c:dm_sysfs_exit
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_block_release
  - drivers/edac/edac_device_sysfs.c:edac_device_ctrl_instance_release
  - drivers/edac/edac_device_sysfs.c:edac_device_unregister_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_instance_release
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor_attr_set.c:gov_attr_set_put
  - drivers/cpuidle/sysfs.c:cpuidle_remove_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_remove_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_sysfs_destroy
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - net/core/dev.c:netdev_run_todo
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
**Symbols:**

```
ffffffff81ac80a0-ffffffff81ac80e5: kobject_put (STB_GLOBAL)
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
