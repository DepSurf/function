# Function: <code>kobject_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eb690)
Location: lib/kobject.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_get
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/genhd.c:get_disk
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/bus.c:bus_create_file
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff813eb690-ffffffff813eb70f: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff814319f0)
Location: lib/kobject.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - fs/char_dev.c:cdev_get
  - fs/block_dev.c:bd_link_disk_holder
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/genhd.c:get_disk
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff814319f0-ffffffff81431a6f: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144dc60)
Location: lib/kobject.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - fs/char_dev.c:cdev_get
  - fs/block_dev.c:bd_link_disk_holder
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_register_dev
  - block/genhd.c:get_disk
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8144dc60-ffffffff8144dcdf: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818ede90)
Location: lib/kobject.c:591
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/char_dev.c:cdev_get
  - fs/block_dev.c:bd_link_disk_holder
  - block/blk-core.c:blk_init_rl
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff818ede90-ffffffff818edec3: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974140)
Location: lib/kobject.c:591
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/char_dev.c:cdev_get
  - fs/block_dev.c:bd_link_disk_holder
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81974140-ffffffff81974182: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0660)
Location: lib/kobject.c:606
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/char_dev.c:cdev_get
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff819d0660-ffffffff819d06a1: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a09bc0)
Location: lib/kobject.c:606
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/char_dev.c:cdev_get
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a09bc0-ffffffff81a09c01: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79450)
Location: lib/kobject.c:637
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/char_dev.c:cdev_get
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a79450-ffffffff81a79491: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab07b0)
Location: lib/kobject.c:637
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81ab07b0-ffffffff81ab07f1: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eaa50)
Location: lib/kobject.c:655
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff815eaa50-ffffffff815eaabe: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f370)
Location: lib/kobject.c:652
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8160f370-ffffffff8160f3de: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2ab0)
Location: lib/kobject.c:652
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:fw_devlink_link_device
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff815f2ab0-ffffffff815f2b1e: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8165fc90)
Location: lib/kobject.c:652
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - fs/char_dev.c:cdev_add
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/holder.c:bd_link_disk_holder
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8165fc90-ffffffff8165fcfe: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff817797c0)
Location: lib/kobject.c:620
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - fs/char_dev.c:cdev_add
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/holder.c:bd_link_disk_holder
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff817797c0-ffffffff8177983e: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022750)
Location: lib/kobject.c:628
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - fs/char_dev.c:cdev_add
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
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
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:get_device
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff82022750-ffffffff820227ce: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a27c0)
Location: lib/kobject.c:629
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - fs/char_dev.c:cdev_add
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
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
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:get_device
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:fw_devlink_dev_sync_state
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:bus_to_subsys
  - drivers/base/class.c:class_to_subsys
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff820a27c0-ffffffff820a283e: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217a840)
Location: lib/kobject.c:636
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - fs/char_dev.c:cdev_add
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/holder.c:bd_link_disk_holder
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:generic_single_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:get_device
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:fw_devlink_dev_sync_state
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:bus_to_subsys
  - drivers/base/class.c:class_to_subsys
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8217a840-ffffffff8217a8be: kobject_get (STB_GLOBAL)
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
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8a620)
Location: lib/kobject.c:637
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/of/dynamic.c:of_changeset_action
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffff800010d8a620-ffff800010d8a670: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e84f74)
Location: lib/kobject.c:637
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/of/dynamic.c:of_changeset_action
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c0e84f74-c0e84fd8: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecb690)
Location: lib/kobject.c:637
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/of/dynamic.c:of_changeset_action
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c000000000ecb690-c000000000ecb710: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b3bac)
Location: lib/kobject.c:637
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/of/dynamic.c:of_changeset_action
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffe0008b3bac-ffffffe0008b3bf0: kobject_get (STB_GLOBAL)
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
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4f600)
Location: lib/kobject.c:637
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a4f600-ffffffff81a4f641: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0c700)
Location: lib/kobject.c:637
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a0c700-ffffffff81a0c741: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abb9f0)
Location: lib/kobject.c:637
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81abb9f0-ffffffff81abba31: kobject_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kobject *kobject_get(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac7f10)
Location: lib/kobject.c:637
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
  - fs/char_dev.c:cdev_add
  - fs/block_dev.c:bd_link_disk_holder
  - fs/sysfs/file.c:sysfs_break_active_protection
  - block/blk-core.c:blk_get_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - drivers/pci/host-bridge.c:pci_get_host_bridge_device
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_group_ref_get
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:__class_register
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:software_node_get
  - drivers/pps/pps.c:pps_cdev_open
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81ac7f10-ffffffff81ac7f51: kobject_get (STB_GLOBAL)
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
