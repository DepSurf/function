# Function: <code>kobject_create_and_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813ec470)
Location: lib/kobject.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - mm/mm_init.c:mm_sysfs_init
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_init
  - fs/namespace.c:mnt_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:add_disk
  - block/genhd.c:add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff813ec470-ffffffff813ec4d4: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81432750)
Location: lib/kobject.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - mm/mm_init.c:mm_sysfs_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - fs/namespace.c:mnt_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff81432750-ffffffff814327b0: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144e9c0)
Location: lib/kobject.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - mm/mm_init.c:mm_sysfs_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - fs/namespace.c:mnt_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff8144e9c0-ffffffff8144ea20: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818eebe0)
Location: lib/kobject.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - mm/mm_init.c:mm_sysfs_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - fs/namespace.c:mnt_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff818eebe0-ffffffff818eec40: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974ea0)
Location: lib/kobject.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - fs/namespace.c:mnt_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff81974ea0-ffffffff81974f00: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:760
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff819d184a-ffffffff819d186e: kobject_create_and_add.cold.16 (STB_LOCAL)
ffffffff819d15e0-ffffffff819d1623: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:760
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff81a0ad96-ffffffff81a0adba: kobject_create_and_add.cold.15 (STB_LOCAL)
ffffffff81a0a9a0-ffffffff81a0a9e3: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:791
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff81a7a768-ffffffff81a7a78d: kobject_create_and_add.cold (STB_LOCAL)
ffffffff81a7a350-ffffffff81a7a395: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:791
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff81ab1ac8-ffffffff81ab1aed: kobject_create_and_add.cold (STB_LOCAL)
ffffffff81ab16b0-ffffffff81ab16f5: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:808
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_register_node
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff815ebdcb-ffffffff815ebe09: kobject_create_and_add.cold (STB_LOCAL)
ffffffff815eb910-ffffffff815eb9a2: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:805
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_node
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff81bf4b52-ffffffff81bf4b90: kobject_create_and_add.cold (STB_LOCAL)
ffffffff81610230-ffffffff816102c2: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:805
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff81be6a5b-ffffffff81be6a99: kobject_create_and_add.cold (STB_LOCAL)
ffffffff815f3970-ffffffff815f3a02: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:805
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/mempolicy.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff81cdf348-ffffffff81cdf386: kobject_create_and_add.cold (STB_LOCAL)
ffffffff81660b40-ffffffff81660bd2: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:773
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/migrate.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff81ea5b1c-ffffffff81ea5b59: kobject_create_and_add.cold (STB_LOCAL)
ffffffff8177a6b0-ffffffff8177a746: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820237d0)
Location: lib/kobject.c:781
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/memory-tiers.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff820237d0-ffffffff8202387a: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a3840)
Location: lib/kobject.c:782
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/memory-tiers.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff820a3840-ffffffff820a38ea: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217b8f0)
Location: lib/kobject.c:789
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/ksysfs.c:create_setup_data_nodes
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/ksysfs.c:ksysfs_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:add_notes_attrs
  - kernel/bpf/sysfs_btf.c:btf_vmlinux_init
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/memory-tiers.c:numa_init_sysfs
  - mm/huge_memory.c:hugepage_init_sysfs
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpi_fpdt.c:acpi_init_fpdt
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff8217b8f0-ffffffff8217b9c9: kobject_create_and_add (STB_GLOBAL)
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
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8b8c0)
Location: lib/kobject.c:791
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffff800010d8b8c0-ffff800010d8b93c: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e85e60)
Location: lib/kobject.c:791
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
c0e85e60-c0e85ecc: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecd0d0)
Location: lib/kobject.c:791
Inline: False
Direct callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init
  - arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init
  - arch/powerpc/platforms/powernv/opal-psr.c:opal_psr_init
  - arch/powerpc/platforms/powernv/opal-sensor-groups.c:opal_sensor_groups_init
  - arch/powerpc/platforms/powernv/ultravisor.c:__machine_initcall_powernv_uv_init
  - arch/powerpc/platforms/pseries/mobility.c:__machine_initcall_pseries_mobility_sysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
```
**Symbols:**

```
c000000000ecd0d0-c000000000ecd16c: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b4ad8)
Location: lib/kobject.c:791
Inline: False
Direct callers:
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffe0008b4ad8-ffffffe0008b4b44: kobject_create_and_add (STB_GLOBAL)
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
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:791
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff81a50918-ffffffff81a5093d: kobject_create_and_add.cold (STB_LOCAL)
ffffffff81a50500-ffffffff81a50545: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:791
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff81a0da18-ffffffff81a0da3d: kobject_create_and_add.cold (STB_LOCAL)
ffffffff81a0d600-ffffffff81a0d645: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:791
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff81abcd08-ffffffff81abcd2d: kobject_create_and_add.cold (STB_LOCAL)
ffffffff81abc8f0-ffffffff81abc935: kobject_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct kobject *kobject_create_and_add(const char *name, struct kobject *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:791
Inline: False
Direct callers:
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - kernel/ksysfs.c:ksysfs_init
  - kernel/power/main.c:pm_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_init
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
  - mm/mm_init.c:mm_sysfs_init
  - mm/swap_state.c:swap_init_sysfs
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_register_node
  - mm/hugetlb.c:hugetlb_sysfs_add_hstate
  - mm/huge_memory.c:hugepage_init
  - fs/namespace.c:mnt_init
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/inode.c:fuse_init
  - block/genhd.c:genhd_device_init
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/bgrt.c:bgrt_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/sfi/sfi_core.c:sfi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/core.c:devices_init
  - drivers/base/class.c:class_compat_register
  - drivers/base/firmware.c:firmware_init
  - drivers/base/module.c:module_add_driver
  - drivers/base/hypervisor.c:hypervisor_init
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff81ac918b-ffffffff81ac91b0: kobject_create_and_add.cold (STB_LOCAL)
ffffffff81ac8d70-ffffffff81ac8db5: kobject_create_and_add (STB_GLOBAL)
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
