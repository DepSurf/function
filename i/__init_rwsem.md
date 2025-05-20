# Function: <code>__init_rwsem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810cba30)
Location: kernel/locking/rwsem-xadd.c:73
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/padata.c:padata_alloc
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:sget_userns
  - fs/inode.c:address_space_init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:led_classdev_register
```
**Symbols:**

```
ffffffff810cba30-ffffffff810cba64: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d04c0)
Location: kernel/locking/rwsem-xadd.c:73
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/padata.c:padata_alloc
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:sget_userns
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:led_classdev_register
```
**Symbols:**

```
ffffffff810d04c0-ffffffff810d04f4: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d6ec0)
Location: kernel/locking/rwsem-xadd.c:73
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/padata.c:padata_alloc
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:sget_userns
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:led_classdev_register
```
**Symbols:**

```
ffffffff810d6ec0-ffffffff810d6ef4: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d5f20)
Location: kernel/locking/rwsem-xadd.c:75
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/padata.c:padata_alloc_possible
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:sget_userns
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff810d5f20-ffffffff810d5f54: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810ddee0)
Location: kernel/locking/rwsem-xadd.c:76
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/padata.c:padata_alloc_possible
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff810ddee0-ffffffff810ddf14: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810e6550)
Location: kernel/locking/rwsem-xadd.c:76
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/padata.c:padata_alloc_possible
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff810e6550-ffffffff810e6584: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810f1ad0)
Location: kernel/locking/rwsem-xadd.c:76
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/padata.c:padata_alloc_possible
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff810f1ad0-ffffffff810f1b04: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f7a90)
Location: kernel/locking/rwsem.c:323
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hmm.c:hmm_mirror_register
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff810f7a90-ffffffff810f7ac4: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff811038c0)
Location: kernel/locking/rwsem.c:324
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/crypto/keyring.c:add_master_key
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff811038c0-ffffffff811038f4: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110e410)
Location: kernel/locking/rwsem.c:323
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/crypto/keyring.c:add_new_master_key
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - block/keyslot-manager.c:blk_ksm_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_create
```
**Symbols:**

```
ffffffff8110e410-ffffffff8110e444: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110b6d0)
Location: kernel/locking/rwsem.c:304
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_alloc_inode
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/keyslot-manager.c:blk_ksm_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_create
  - net/ipv4/nexthop.c:nexthop_net_init
```
**Symbols:**

```
ffffffff8110b6d0-ffffffff8110b704: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110d4f0)
Location: kernel/locking/rwsem.c:304
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_alloc_inode
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/keyslot-manager.c:blk_ksm_init_passthrough
  - block/keyslot-manager.c:blk_ksm_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/ipv4/nexthop.c:nexthop_net_init
```
**Symbols:**

```
ffffffff8110d4f0-ffffffff8110d524: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8112cd40)
Location: kernel/locking/rwsem.c:305
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/keyslot-manager.c:blk_ksm_init_passthrough
  - block/keyslot-manager.c:blk_ksm_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_init_device
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/ipv4/nexthop.c:nexthop_net_init
```
**Symbols:**

```
ffffffff8112cd40-ffffffff8112cd74: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8114dfe0)
Location: kernel/locking/rwsem.c:305
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:bdi_init
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_init_device
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/ipv4/nexthop.c:nexthop_net_init
```
**Symbols:**

```
ffffffff8114dfe0-ffffffff8114e01c: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8117cf30)
Location: kernel/locking/rwsem.c:313
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:bdi_init
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/ipv4/nexthop.c:nexthop_net_init
```
**Symbols:**

```
ffffffff8117cf30-ffffffff8117cf6c: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8118dbe0)
Location: kernel/locking/rwsem.c:310
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:bdi_init
  - mm/rmap.c:anon_vma_ctor
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/ipv4/nexthop.c:nexthop_net_init
```
**Symbols:**

```
ffffffff8118dbe0-ffffffff8118dc1c: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8119c590)
Location: kernel/locking/rwsem.c:310
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:vm_area_dup
  - kernel/fork.c:vm_area_alloc
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hugetlb.c:resv_map_alloc
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/dax.c:fuse_dax_inode_alloc
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_register
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/md/dm-table.c:dm_table_create
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/firmware/efi/efi.c:efisubsys_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/ipv4/nexthop.c:nexthop_net_init
```
**Symbols:**

```
ffffffff8119c590-ffffffff8119c5cc: __init_rwsem (STB_GLOBAL)
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
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010168e48)
Location: kernel/locking/rwsem.c:324
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/crypto/keyring.c:add_master_key
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffff800010168e48-ffff800010168e88: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c03b5220)
Location: kernel/locking/rwsem.c:324
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/crypto/keyring.c:add_master_key
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:led_classdev_register_ext
  - sound/core/init.c:snd_card_new
  - sound/soc/soc-jack.c:snd_soc_card_jack_new
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
c03b5220-c03b5258: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0000000001c0af0)
Location: kernel/locking/rwsem.c:324
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/crypto/keyring.c:add_master_key
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
c0000000001c0af0-c0000000001c0b20: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe00010a7d8)
Location: kernel/locking/rwsem.c:324
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - kernel/padata.c:padata_alloc_possible
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/crypto/keyring.c:add_master_key
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffe00010a7d8-ffffffe00010a80c: __init_rwsem (STB_GLOBAL)
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
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fcbd0)
Location: kernel/locking/rwsem.c:324
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/crypto/keyring.c:add_master_key
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff810fcbd0-ffffffff810fcc04: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ecde0)
Location: kernel/locking/rwsem.c:324
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/crypto/keyring.c:add_master_key
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff810ecde0-ffffffff810ece14: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f9d90)
Location: kernel/locking/rwsem.c:324
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/crypto/keyring.c:add_master_key
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff810f9d90-ffffffff810f9dc4: __init_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore *sem, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81104f00)
Location: kernel/locking/rwsem.c:324
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/qos.c:freq_constraints_init
  - kernel/power/qos.c:freq_constraints_init
  - kernel/time/posix-clock.c:posix_clock_register
  - kernel/user_namespace.c:create_user_ns
  - kernel/taskstats.c:taskstats_init_early
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/rmap.c:anon_vma_ctor
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
  - fs/inode.c:inode_init_always
  - fs/crypto/keyring.c:add_master_key
  - fs/configfs/dir.c:new_fragment
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/ext4/super.c:init_once
  - fs/fat/inode.c:fat_alloc_inode
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:ipc_init_ids
  - security/keys/key.c:key_alloc
  - block/genhd.c:__alloc_disk_node
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/video/backlight/backlight.c:backlight_class_init
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_register
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81104f00-ffffffff81104f34: __init_rwsem (STB_GLOBAL)
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
