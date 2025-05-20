# Function: <code>sysfs_remove_file_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8128c690)
Location: fs/sysfs/file.c:410
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:free_module
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_exit
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/driver.c:driver_remove_file
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:__class_register
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
```
**Symbols:**

```
ffffffff8128c690-ffffffff8128c6a7: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812b9d5e)
Location: fs/sysfs/file.c:416
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/driver.c:driver_remove_file
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff812b9d20-ffffffff812b9d37: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812cf48e)
Location: fs/sysfs/file.c:416
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/driver.c:driver_remove_file
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff812cf450-ffffffff812cf467: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812dcbce)
Location: fs/sysfs/file.c:418
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
**Symbols:**

```
ffffffff812dcb90-ffffffff812dcba7: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813014de)
Location: fs/sysfs/file.c:418
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
**Symbols:**

```
ffffffff813014a0-ffffffff813014b7: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8132f21e)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
**Symbols:**

```
ffffffff8132f1e0-ffffffff8132f1f7: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813465de)
Location: fs/sysfs/file.c:465
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
**Symbols:**

```
ffffffff813465a0-ffffffff813465b7: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136e8fe)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff8136e8c0-ffffffff8136e8d7: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81386b7e)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff81386b40-ffffffff81386b57: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813d170e)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff813d16d0-ffffffff813d16e7: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e330e)
Location: fs/sysfs/file.c:465
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff813e32d0-ffffffff813e32e7: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e9f4e)
Location: fs/sysfs/file.c:476
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff813e9f10-ffffffff813e9f27: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8143bcce)
Location: fs/sysfs/file.c:476
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff8143bc90-ffffffff8143bca7: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b711e)
Location: fs/sysfs/file.c:486
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module/sysfs.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff814b70d0-ffffffff814b70f3: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154e41e)
Location: fs/sysfs/file.c:486
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module/sysfs.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff8154e3c0-ffffffff8154e3e3: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815860de)
Location: fs/sysfs/file.c:486
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module/sysfs.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff81586080-ffffffff815860a3: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815bebbe)
Location: fs/sysfs/file.c:499
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module/sysfs.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff815beb60-ffffffff815beb83: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffff8000104567e8)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_remove
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffff800010456770-ffff8000104567b4: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c0618840)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
c06187f4-c0618818: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c000000000570720)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
c0000000005706a0-c0000000005706dc: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffe0002e7f82)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
**Symbols:**

```
ffffffe0002e7f22-ffffffe0002e7f5e: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137f15e)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff8137f120-ffffffff8137f137: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136fbee)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff8136fbb0-ffffffff8136fbc7: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137cc2e)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff8137cbf0-ffffffff8137cc07: sysfs_remove_file_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_file_ns(struct kobject *kobj, const struct attribute *attr, const void *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8139070e)
Location: fs/sysfs/file.c:464
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
Direct callers:
  - kernel/module.c:module_remove_modinfo_attrs
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/iommu/iommu.c:iommu_group_set_name
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_remove_file
  - drivers/base/class.c:class_remove_file_ns
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff813906d0-ffffffff813906e7: sysfs_remove_file_ns (STB_GLOBAL)
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
