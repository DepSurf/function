# Function: <code>sysfs_create_file_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8128ca30)
Location: fs/sysfs/file.c:321
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:__class_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/firmware/edd.c:edd_init
```
**Symbols:**

```
ffffffff8128ca30-ffffffff8128ca5e: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812ba0c0)
Location: fs/sysfs/file.c:327
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:__class_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/firmware/edd.c:edd_init
```
**Symbols:**

```
ffffffff812ba0c0-ffffffff812ba0ee: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812cf7f0)
Location: fs/sysfs/file.c:327
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - lib/kobject.c:kobject_add_internal
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:__class_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/firmware/edd.c:edd_init
```
**Symbols:**

```
ffffffff812cf7f0-ffffffff812cf81e: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812dcf10)
Location: fs/sysfs/file.c:329
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff812dcf10-ffffffff812dcf3e: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81301840)
Location: fs/sysfs/file.c:329
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81301840-ffffffff8130186e: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8132f590)
Location: fs/sysfs/file.c:322
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/edd.c:edd_init
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8132f590-ffffffff8132f617: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81346930)
Location: fs/sysfs/file.c:322
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/edd.c:edd_init
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81346930-ffffffff813469bf: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/file.c (0)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/edd.c:edd_init
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8136ef1b-ffffffff8136ef33: sysfs_create_file_ns.cold (STB_LOCAL)
ffffffff8136ec30-ffffffff8136ecc2: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81386f40)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/edd.c:edd_init
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81386f40-ffffffff81386fcf: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813d1c20)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:module_add_modinfo_attrs
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - lib/kobject.c:create_dir
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/edd.c:edd_init
```
**Symbols:**

```
ffffffff813d1c20-ffffffff813d1caf: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e3980)
Location: fs/sysfs/file.c:322
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:module_add_modinfo_attrs
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - lib/kobject.c:create_dir
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_block
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev_interface
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/edd.c:edd_init
```
**Symbols:**

```
ffffffff813e3980-ffffffff813e3a0f: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813ea590)
Location: fs/sysfs/file.c:333
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - lib/kobject.c:create_dir
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/edd.c:edd_device_register
```
**Symbols:**

```
ffffffff813ea590-ffffffff813ea61f: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8143c310)
Location: fs/sysfs/file.c:333
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - lib/kobject.c:create_dir
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/edd.c:edd_device_register
```
**Symbols:**

```
ffffffff8143c310-ffffffff8143c39f: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b77d0)
Location: fs/sysfs/file.c:345
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module/sysfs.c:module_add_modinfo_attrs
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/edd.c:edd_device_register
```
**Symbols:**

```
ffffffff814b77d0-ffffffff814b787c: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154ec40)
Location: fs/sysfs/file.c:345
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:locate_module_kobject
  - kernel/module/sysfs.c:module_add_modinfo_attrs
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/edd.c:edd_init
```
**Symbols:**

```
ffffffff8154ec40-ffffffff8154ecec: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81586910)
Location: fs/sysfs/file.c:345
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:locate_module_kobject
  - kernel/module/decompress.c:module_decompress_sysfs_init
  - kernel/module/sysfs.c:module_add_modinfo_attrs
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/edd.c:edd_init
```
**Symbols:**

```
ffffffff81586910-ffffffff815869bc: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815bf470)
Location: fs/sysfs/file.c:358
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin_init
  - kernel/params.c:locate_module_kobject
  - kernel/module/decompress.c:module_decompress_sysfs_init
  - kernel/module/sysfs.c:module_add_modinfo_attrs
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_enable_boost_support
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/firmware/edd.c:edd_init
```
**Symbols:**

```
ffffffff815bf470-ffffffff815bf51c: sysfs_create_file_ns (STB_GLOBAL)
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
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffff800010456c70)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_probe
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffff800010456c70-ffff800010456d18: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c0618c4c)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c0618c4c-c0618d1c: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c000000000570e00)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
  - arch/powerpc/kernel/fadump.c:setup_fadump
  - arch/powerpc/kernel/fadump.c:setup_fadump
  - arch/powerpc/kernel/fadump.c:setup_fadump
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init
  - arch/powerpc/platforms/powernv/opal-psr.c:opal_psr_init
  - arch/powerpc/platforms/pseries/power.c:__machine_initcall_pseries_apo_pm_init
  - arch/powerpc/platforms/pseries/dlpar.c:__machine_initcall_pseries_dlpar_sysfs_init
  - arch/powerpc/platforms/pseries/mobility.c:__machine_initcall_pseries_mobility_sysfs_init
  - arch/powerpc/platforms/pseries/mobility.c:__machine_initcall_pseries_mobility_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c000000000570e00-c000000000570ef4: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffe0002e8314)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffe0002e8314-ffffffe0002e838a: sysfs_create_file_ns (STB_GLOBAL)
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
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137f520)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/edd.c:edd_init
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8137f520-ffffffff8137f5af: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136ffb0)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/edd.c:edd_init
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8136ffb0-ffffffff8137003f: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137cff0)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/edd.c:edd_init
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8137cff0-ffffffff8137d07f: sysfs_create_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_create_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81390ad0)
Location: fs/sysfs/file.c:321
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - fs/sysfs/file.c:sysfs_create_files
  - block/elevator.c:elv_register_queue
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/core.c:device_create_file
  - drivers/base/bus.c:bus_create_file
  - drivers/base/driver.c:driver_create_file
  - drivers/base/class.c:class_create_file_ns
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/firmware/edd.c:edd_init
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81390ad0-ffffffff81390b5f: sysfs_create_file_ns (STB_GLOBAL)
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
