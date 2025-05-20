# Function: <code>kobject_init_and_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813ec5f0)
Location: lib/kobject.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:load_module
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
```
**Symbols:**

```
ffffffff813ec5f0-ffffffff813ec691: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff814328b0)
Location: lib/kobject.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:load_module
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff814328b0-ffffffff81432954: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144eb20)
Location: lib/kobject.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:load_module
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8144eb20-ffffffff8144ebc4: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818eed40)
Location: lib/kobject.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:load_module
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff818eed40-ffffffff818eede9: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81975000)
Location: lib/kobject.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:load_module
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81975000-ffffffff819750a9: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:444
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff819d1803-ffffffff819d1817: kobject_init_and_add.cold.14 (STB_LOCAL)
ffffffff819d1390-ffffffff819d1427: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:444
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81a0adba-ffffffff81a0adce: kobject_init_and_add.cold.16 (STB_LOCAL)
ffffffff81a0aaf0-ffffffff81a0ab87: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81a7a78d-ffffffff81a7a7a1: kobject_init_and_add.cold (STB_LOCAL)
ffffffff81a7a4b0-ffffffff81a7a547: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81ab1aed-ffffffff81ab1b01: kobject_init_and_add.cold (STB_LOCAL)
ffffffff81ab1810-ffffffff81ab18a7: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:register_entries
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff815ebe09-ffffffff815ebe1d: kobject_init_and_add.cold (STB_LOCAL)
ffffffff815eb9b0-ffffffff815eba47: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:register_entries
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81bf4b90-ffffffff81bf4ba4: kobject_init_and_add.cold (STB_LOCAL)
ffffffff816102d0-ffffffff81610367: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_device_register
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81be6a99-ffffffff81be6aad: kobject_init_and_add.cold (STB_LOCAL)
ffffffff815f3a10-ffffffff815f3aa7: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_device_register
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81cdf386-ffffffff81cdf39a: kobject_init_and_add.cold (STB_LOCAL)
ffffffff81660be0-ffffffff81660c77: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, const struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:432
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/build_utility.c:sugov_init
  - kernel/module/sysfs.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-integrity.c:blk_integrity_add
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_register
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_device_register
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81ea5b59-ffffffff81ea5b6c: kobject_init_and_add.cold (STB_LOCAL)
ffffffff8177a750-ffffffff8177a812: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, const struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82023890)
Location: lib/kobject.c:440
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/build_utility.c:sugov_init
  - kernel/module/sysfs.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-integrity.c:blk_integrity_add
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_register
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff82023890-ffffffff8202395e: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, const struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a3900)
Location: lib/kobject.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/build_utility.c:sugov_init
  - kernel/module/sysfs.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_register
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff820a3900-ffffffff820a39ce: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, const struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217b9e0)
Location: lib/kobject.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/build_utility.c:sugov_init
  - kernel/module/sysfs.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/huge_memory.c:hugepage_init_sysfs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_register
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff8217b9e0-ffffffff8217baae: kobject_init_and_add (STB_GLOBAL)
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
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8b7a8)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffff800010d8b7a8-ffff800010d8b874: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e85fec)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
c0e85fec-c0e86088: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecd340)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
c000000000ecd340-c000000000ecd3dc: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b4c34)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffe0008b4c34-ffffffe0008b4ca4: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81a5093d-ffffffff81a50951: kobject_init_and_add.cold (STB_LOCAL)
ffffffff81a50660-ffffffff81a506f7: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/hv/vmbus_drv.c:vmbus_add_channel_kobj
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81a0da3d-ffffffff81a0da51: kobject_init_and_add.cold (STB_LOCAL)
ffffffff81a0d760-ffffffff81a0d7f7: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81abcd2d-ffffffff81abcd41: kobject_init_and_add.cold (STB_LOCAL)
ffffffff81abca50-ffffffff81abcae7: kobject_init_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kobject_init_and_add(struct kobject *kobj, struct kobj_type *ktype, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - kernel/params.c:locate_module_kobject
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/module.c:mod_sysfs_setup
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - block/blk-integrity.c:blk_integrity_add
  - drivers/pci/slot.c:pci_create_slot
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/sysfs.c:acpi_sysfs_add_hotplug_profile
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:swnode_register
  - drivers/md/dm-sysfs.c:dm_sysfs_init
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
**Symbols:**

```
ffffffff81ac91b0-ffffffff81ac91c4: kobject_init_and_add.cold (STB_LOCAL)
ffffffff81ac8ed0-ffffffff81ac8f67: kobject_init_and_add (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobj_type *ktype</code> ➡️ <code>const struct kobj_type *ktype</code>
</li>
</ul>
</details>
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
