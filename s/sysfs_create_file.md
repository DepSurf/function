# Function: <code>sysfs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81f7c957)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In kernel/module.c (ffffffff8110967f)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In fs/sysfs/file.c (ffffffff8128ca89)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff813b3413)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In lib/kobject.c (ffffffff813ec1b8)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8144c53a)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/acpi/sysfs.c (ffffffff81fa26cf)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81fa52f5)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8152a2c3)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff81546498)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff815497dd)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff8154c82b)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b0eeb)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/firmware/edd.c (ffffffff81fb5d9b)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81fa5713)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In kernel/module.c (ffffffff81111525)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In fs/sysfs/file.c (ffffffff812ba11a)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff813f7113)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In lib/kobject.c (ffffffff81432501)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81498c4e)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/acpi/sysfs.c (ffffffff81fce654)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81fd187e)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8157d683)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff81598108)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff8159b42d)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff8159e61b)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81713c73)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/firmware/edd.c (ffffffff81fe32a6)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81fe1218)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In kernel/module.c (ffffffff81118d8d)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In fs/sysfs/file.c (ffffffff812cf84a)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff81410b23)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In lib/kobject.c (ffffffff8144e771)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814ba83e)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/acpi/sysfs.c (ffffffff8200ba15)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8200f219)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff815a9bc3)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff815c5cd8)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff815c998d)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff815ccbcb)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81745a3a)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8201f499)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In drivers/firmware/edd.c (ffffffff82021075)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff820c203a)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In kernel/module.c (ffffffff8111a251)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In fs/sysfs/file.c (ffffffff812dcf6a)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff8141e56e)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814c5055)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/acpi/sysfs.c (ffffffff820ed1a7)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff820f0c86)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff815bf9a5)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff815dab08)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff815de6e0)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff815e171b)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff8175f440)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8176414b)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff82101e21)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In drivers/firmware/edd.c (ffffffff82103bfe)
Location: include/linux/sysfs.h:491
Inline: True
```
```
In lib/kobject.c (ffffffff818ee9f1)
Location: include/linux/sysfs.h:491
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff826ca186)
Location: include/linux/sysfs.h:498
Inline: True
```
```
In kernel/module.c (ffffffff811258c4)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In fs/sysfs/file.c (ffffffff8130189a)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff81448d11)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815055e5)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/acpi/sysfs.c (ffffffff826f6106)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff826fa490)
Location: include/linux/sysfs.h:498
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81625d65)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff81641ab8)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff81645700)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff8164887b)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff817d14d0)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817da144)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8270b471)
Location: include/linux/sysfs.h:498
Inline: True
```
```
In drivers/firmware/edd.c (ffffffff8270d2df)
Location: include/linux/sysfs.h:498
Inline: True
```
```
In lib/kobject.c (ffffffff81974cb1)
Location: include/linux/sysfs.h:498
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff826f44b0)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff811307e7)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffff8132f64a)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff8147d021)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81536519)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/acpi/sysfs.c (ffffffff82720128)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff827247a5)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81660c83)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff8167d6c4)
Location: include/linux/sysfs.h:510
Inline: True
```
```
In drivers/base/bus.c (ffffffff81680b5d)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff81683e2a)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff8181a26f)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81822c41)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8273574f)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/edd.c (ffffffff8273755d)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In lib/kobject.c (ffffffff819d1285)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828ab29d)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff8113c09f)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffff813469ea)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff8149a9f7)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154ddba)
Location: include/linux/sysfs.h:510
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff828d80be)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff828dc97e)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff8167f333)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff8169d0b4)
Location: include/linux/sysfs.h:510
Inline: True
```
```
In drivers/base/bus.c (ffffffff816a05ed)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff816a3afa)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81845a6f)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184eb12)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828ef67b)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/edd.c (ffffffff828f1489)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In lib/kobject.c (ffffffff81a0a7e5)
Location: include/linux/sysfs.h:510
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828c3a7e)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff811476ac)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffff8136ecf7)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff814c8ac9)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157dbda)
Location: include/linux/sysfs.h:518
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff828f1f76)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff828f7263)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff816b6323)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff816d54f5)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff816d951f)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff816dc9ea)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff8179899d)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff8188882b)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81891cf0)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8290ac66)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/edd.c (ffffffff8290cac7)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In lib/kobject.c (ffffffff81a7a159)
Location: include/linux/sysfs.h:518
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_sysfs.c (ffffffff828c9c06)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
```
```
In kernel/params.c (ffffffff828cc051)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff811534cc)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffff81386ff7)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff814e1be9)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159f63a)
Location: include/linux/sysfs.h:573
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff828fb16b)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff82900202)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff816d9023)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff816f92a5)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff816fd51f)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff81700a8a)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff817bc32d)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff818ba7db)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c3d0f)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff829145f9)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/edd.c (ffffffff8291649a)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In lib/kobject.c (ffffffff81ab14b9)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_sysfs.c (ffffffff82cec557)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
```
```
In kernel/params.c (ffffffff82cee14e)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff8116481e)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - kernel/module.c:module_add_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff813d1cd7)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff815407b6)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In lib/kobject.c (ffffffff815eb035)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - lib/kobject.c:create_dir
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81647f67)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/sysfs.c (ffffffff82d11fc0)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/acpi/fan.c (ffffffff816dfda8)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/xen/sys-hypervisor.c (ffffffff82d175fe)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff8178d643)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff817b2175)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff817b7eae)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff817ba9da)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff8188571b)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff8198b120)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819934d5)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff82d2700a)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
```
```
In drivers/firmware/edd.c (ffffffff82d288e7)
Location: include/linux/sysfs.h:574
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff82fda7a3)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff81160b4e)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - kernel/module.c:module_add_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff813e3a37)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff8155cf59)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In lib/kobject.c (ffffffff8160f955)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - lib/kobject.c:create_dir
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8166d0e7)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/sysfs.c (ffffffff82fffa93)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/acpi/fan.c (ffffffff816fdd38)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/xen/sys-hypervisor.c (ffffffff830051ec)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff817b9153)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff817c6a45)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff817ccbc7)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff817cf62a)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff81893fd6)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff8198ed30)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81996691)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a1a5f)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
```
```
In drivers/firmware/edd.c (ffffffff83016fff)
Location: include/linux/sysfs.h:596
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In drivers/devfreq/devfreq.c (ffffffff819cef2b)
Location: include/linux/sysfs.h:596
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff831e5125)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff81161aa5)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffff813ea647)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff815657e9)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In lib/kobject.c (ffffffff815f3095)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - lib/kobject.c:create_dir
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8164f427)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/sysfs.c (ffffffff8320aaca)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/acpi/fan.c (ffffffff816df9a8)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8320fc6a)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff8179c363)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff817a9f05)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff817b053a)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff817b303a)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff81875d65)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81973475)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197b461)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81986a3f)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
```
```
In drivers/firmware/edd.c (ffffffff81c1d99f)
Location: include/linux/sysfs.h:598
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_device_register
```
```
In drivers/devfreq/devfreq.c (ffffffff819b408b)
Location: include/linux/sysfs.h:598
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff832c8fa5)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff81186c70)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffff8143c3c7)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff815c9bd9)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In lib/kobject.c (ffffffff81660265)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - lib/kobject.c:create_dir
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff816c1167)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/sysfs.c (ffffffff832f2fef)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/acpi/fan.c (ffffffff81757828)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/xen/sys-hypervisor.c (ffffffff832f8c2b)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81825053)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff81833085)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff8183975a)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff8183c52a)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff819068e3)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81a1c175)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a243fe)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a30e8f)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
```
```
In drivers/firmware/edd.c (ffffffff81d2eded)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_device_register
```
```
In drivers/devfreq/devfreq.c (ffffffff81a62c6b)
Location: include/linux/sysfs.h:604
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8347c121)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module/sysfs.c (ffffffff811925ad)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - kernel/module/sysfs.c:module_add_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff814b78ac)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff81674f44)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff817e6945)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/sysfs.c (ffffffff834ab0c7)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/acpi/fan_attr.c (ffffffff8188b4bf)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
```
```
In drivers/xen/sys-hypervisor.c (ffffffff834b1556)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81964ed3)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff819749e3)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff8197bd76)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff8197ef3a)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff81a59797)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81b851e5)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8db27)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9cf7b)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
```
```
In drivers/firmware/edd.c (ffffffff81efb26a)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_device_register
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd40f7)
Location: include/linux/sysfs.h:604
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff83ea73aa)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module/sysfs.c (ffffffff811cff0d)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - kernel/module/sysfs.c:module_add_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff8154ed2c)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff81730cf3)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8190b895)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/sysfs.c (ffffffff83ee33e0)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/acpi/fan_attr.c (ffffffff819d218f)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
```
```
In drivers/xen/sys-hypervisor.c (ffffffff83eeb7aa)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81ace2f3)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff81ae0113)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff81ae8e86)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff81aec63a)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff81be35d2)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81d240e2)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2d4b7)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3ec0b)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
```
```
In drivers/firmware/edd.c (ffffffff83f05c93)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In drivers/devfreq/devfreq.c (ffffffff81d802b7)
Location: include/linux/sysfs.h:620
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff836cbd0a)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module/decompress.c (ffffffff836d2b65)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - kernel/module/decompress.c:module_decompress_sysfs_init
```
```
In kernel/module/sysfs.c (ffffffff811e40c7)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - kernel/module/sysfs.c:module_add_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff815869fc)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff8176cf53)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8194ef15)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/sysfs.c (ffffffff83708df0)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/acpi/fan_attr.c (ffffffff81a1978a)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
```
```
In drivers/xen/sys-hypervisor.c (ffffffff83711244)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81b1cc83)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff81b2e333)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff81b3715f)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff81b3a82a)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3b4ec)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81d8d302)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d96739)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81da978b)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
```
```
In drivers/firmware/edd.c (ffffffff8372bc89)
Location: include/linux/sysfs.h:620
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In drivers/devfreq/devfreq.c (ffffffff81dee647)
Location: include/linux/sysfs.h:620
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff838fd0fa)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module/decompress.c (ffffffff83904925)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - kernel/module/decompress.c:module_decompress_sysfs_init
```
```
In kernel/module/sysfs.c (ffffffff811f9e17)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - kernel/module/sysfs.c:module_add_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff815bf55c)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff817af180)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81998345)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/sysfs.c (ffffffff8393c1c0)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/acpi/fan_attr.c (ffffffff81a64a5a)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
```
```
In drivers/xen/sys-hypervisor.c (ffffffff83944bd4)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81b731a3)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff81b85b33)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff81b8ebde)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff81b922ea)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf08ea)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81e44bb2)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4e399)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e6162b)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
```
```
In drivers/firmware/edd.c (ffffffff8395fc78)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea4af7)
Location: include/linux/sysfs.h:622
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffff8000114438d0)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffff8000101c1d98)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffff800010456d4c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffff8000105dedb0)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffff800010707b98)
Location: include/linux/sysfs.h:573
Inline: True
```
```
In drivers/acpi/sysfs.c (ffff80001147e0e8)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/soc/xilinx/zynqmp_power.c (ffff80001082039c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_probe
```
```
In drivers/xen/sys-hypervisor.c (ffff800011492134)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffff8000108c4800)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffff8000108e3460)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffff8000108e80f8)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffff8000108ebed0)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffff8000109d5314)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffff800010b12da0)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b21960)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In lib/kobject.c (ffff800010d8af80)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (c151d7a4)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (c04099b0)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (c0618d58)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (c078bcbc)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/iommu/iommu.c (c09bbc7c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (c09d1ed8)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (c09d656c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (c09d9f28)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (c0abce38)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (c0bf0d44)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (c0bfc07c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In lib/kobject.c (c0e85b78)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/cacheinfo.c (c00000000002ae28)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
```
```
In arch/powerpc/kernel/fadump.c (c000000001350388)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:setup_fadump
  - arch/powerpc/kernel/fadump.c:setup_fadump
  - arch/powerpc/kernel/fadump.c:setup_fadump
```
```
In arch/powerpc/kernel/secvar-sysfs.c (c000000000085c04)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
```
```
In arch/powerpc/platforms/powernv/opal-sysparam.c (c00000000135d4f4)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init
```
```
In arch/powerpc/platforms/powernv/opal-psr.c (c00000000135e5a8)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-psr.c:opal_psr_init
```
```
In arch/powerpc/platforms/pseries/power.c (c0000000013630ec)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/power.c:__machine_initcall_pseries_apo_pm_init
```
```
In arch/powerpc/platforms/pseries/dlpar.c (c0000000013631e4)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dlpar.c:__machine_initcall_pseries_dlpar_sysfs_init
```
```
In arch/powerpc/platforms/pseries/mobility.c (c00000000136327c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/mobility.c:__machine_initcall_pseries_mobility_sysfs_init
  - arch/powerpc/platforms/pseries/mobility.c:__machine_initcall_pseries_mobility_sysfs_init
```
```
In kernel/params.c (c000000001367a60)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (c000000000228e64)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (c000000000570f54)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (c000000000770cf0)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (c00000000088030c)
Location: include/linux/sysfs.h:573
Inline: True
```
```
In drivers/iommu/iommu.c (c00000000096a6a4)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (c000000000978430)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (c00000000097e3b0)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (c000000000983804)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (c000000000a95f9c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (c000000000c074f0)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (c000000000c159f8)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In lib/kobject.c (c000000000eccdc0)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffe000005a20)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffe000143ab2)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffe0002e83b4)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffe0004218c8)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d5556)
Location: include/linux/sysfs.h:573
Inline: True
```
```
In drivers/base/core.c (ffffffe00057881e)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffe00057c426)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffe00057f520)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffe00062153c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffe0006ff87e)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In lib/kobject.c (ffffffe0008b48e2)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828b4e44)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff8114baec)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffff8137f5d7)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff814da1c9)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81592e4a)
Location: include/linux/sysfs.h:573
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff828e3dff)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff828e7a1f)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff8169ea73)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff816bea95)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff816c2d0f)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff816c627a)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff81780dfd)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff8186065b)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8186842f)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828f9d33)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/edd.c (ffffffff828fb9ee)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In lib/kobject.c (ffffffff81a50309)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828acfc5)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff8113ed9c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffff81370067)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff814cab79)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81581fda)
Location: include/linux/sysfs.h:573
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff828dbea6)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff8167c463)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff81699d45)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff8169dfbf)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff816a14da)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff81760b85)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81827c2b)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818310df)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828f1f12)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/edd.c (ffffffff828f328a)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In lib/kobject.c (ffffffff81a0d409)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff828c7d43)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff8114999c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffff8137d0a7)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff814d6259)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159338a)
Location: include/linux/sysfs.h:573
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff828f6d67)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff828fb525)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff816ccce3)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff816ecf65)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff816f11df)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff816f474a)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff817b11ad)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff818afc8b)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b91bf)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8290ec45)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/edd.c (ffffffff82910acf)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In lib/kobject.c (ffffffff81abc6f9)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_sysfs.c (ffffffff828cac43)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
```
```
In kernel/params.c (ffffffff828cd09a)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
```
```
In kernel/module.c (ffffffff8115665c)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
```
In fs/sysfs/file.c (ffffffff81390b87)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_create_files
```
```
In block/elevator.c (ffffffff814eee59)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - block/elevator.c:elv_register_queue
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815ad80a)
Location: include/linux/sysfs.h:573
Inline: True
```
```
In drivers/acpi/sysfs.c (ffffffff828fc1bf)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
```
In drivers/xen/sys-hypervisor.c (ffffffff82901256)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff816e71c3)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/core.c (ffffffff817077a5)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_file
```
```
In drivers/base/bus.c (ffffffff8170ba1f)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_create_file
```
```
In drivers/base/driver.c (ffffffff8170efda)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_create_file
```
```
In drivers/net/phy/phy_device.c (ffffffff817cb13d)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff818cbf1b)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d549f)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8291565b)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/firmware/edd.c (ffffffff829174fc)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In lib/kobject.c (ffffffff81ac8b77)
Location: include/linux/sysfs.h:573
Inline: True
Inline callers:
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
</ul>

## Differences
