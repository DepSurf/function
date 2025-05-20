# Function: <code>sysfs_remove_file</code>

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
In kernel/module.c (ffffffff81107659)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - kernel/module.c:free_module
```
```
In fs/sysfs/file.c (ffffffff8128c6ce)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8144c648)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
```
```
In drivers/xen/sys-hypervisor.c (ffffffff820afc08)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_exit
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_exit
```
```
In drivers/iommu/iommu.c (ffffffff8152a280)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff815464ff)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
```
In drivers/base/bus.c (ffffffff81549847)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff8154c85b)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_remove_file
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b15eb)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
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
In kernel/module.c (ffffffff8110e22d)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
```
```
In fs/sysfs/file.c (ffffffff812b9d5e)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8149900f)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81fd1966)
Location: include/linux/sysfs.h:497
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8157d640)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff81598b68)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff8159b497)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff8159e64b)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_remove_file
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8171288c)
Location: include/linux/sysfs.h:497
Inline: True
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
In kernel/module.c (ffffffff81115c0d)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
```
```
In fs/sysfs/file.c (ffffffff812cf48e)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814babff)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8200f301)
Location: include/linux/sysfs.h:497
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff815a9b80)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff815c7619)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff815c99f7)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff815ccbfb)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_remove_file
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8174390c)
Location: include/linux/sysfs.h:497
Inline: True
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
In kernel/module.c (ffffffff81115624)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff812dcbce)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814c53eb)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/xen/sys-hypervisor.c (ffffffff820f0d8d)
Location: include/linux/sysfs.h:497
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff815bf960)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff815dc2c1)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff815de74e)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff815e187b)
Location: include/linux/sysfs.h:497
Inline: True
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff8175f252)
Location: include/linux/sysfs.h:497
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81761f8c)
Location: include/linux/sysfs.h:497
Inline: True
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
In kernel/module.c (ffffffff81120bd4)
Location: include/linux/sysfs.h:504
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff813014de)
Location: include/linux/sysfs.h:504
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8150597b)
Location: include/linux/sysfs.h:504
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/xen/sys-hypervisor.c (ffffffff826fa597)
Location: include/linux/sysfs.h:504
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81625d20)
Location: include/linux/sysfs.h:504
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff81643255)
Location: include/linux/sysfs.h:504
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff8164576e)
Location: include/linux/sysfs.h:504
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff816489db)
Location: include/linux/sysfs.h:504
Inline: True
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff817d12e2)
Location: include/linux/sysfs.h:504
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d7f6c)
Location: include/linux/sysfs.h:504
Inline: True
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
In kernel/module.c (ffffffff8112e504)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff8132f21e)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8153689a)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_deregister
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8272489b)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81660c40)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff8167e363)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff81680bc7)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff81683f5a)
Location: include/linux/sysfs.h:516
Inline: True
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff8181a082)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818208bb)
Location: include/linux/sysfs.h:516
Inline: True
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
In kernel/module.c (ffffffff81139e04)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff813465de)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154dbec)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
```
In drivers/xen/sys-hypervisor.c (ffffffff828dca74)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff8167f2f0)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff8169dd73)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff816a0657)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff816a3c2a)
Location: include/linux/sysfs.h:516
Inline: True
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81845882)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184c76b)
Location: include/linux/sysfs.h:516
Inline: True
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
In kernel/module.c (ffffffff81145527)
Location: include/linux/sysfs.h:524
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff8136e8fe)
Location: include/linux/sysfs.h:524
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157da0b)
Location: include/linux/sysfs.h:524
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
```
In drivers/xen/sys-hypervisor.c (ffffffff828f735e)
Location: include/linux/sysfs.h:524
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff816b62e0)
Location: include/linux/sysfs.h:524
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff816d6160)
Location: include/linux/sysfs.h:524
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff816d9587)
Location: include/linux/sysfs.h:524
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff816dcb2a)
Location: include/linux/sysfs.h:524
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81798172)
Location: include/linux/sysfs.h:524
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81888642)
Location: include/linux/sysfs.h:524
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8188fce9)
Location: include/linux/sysfs.h:524
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
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
In kernel/module.c (ffffffff81151037)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff81386b7e)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159f46b)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
```
In drivers/xen/sys-hypervisor.c (ffffffff829002fd)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff816d8fe0)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff816fa19d)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff816fd587)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff81700bda)
Location: include/linux/sysfs.h:579
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817bbbaf)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff818ba5f2)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c1ee9)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
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
In kernel/module.c (ffffffff81161597)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff813d170e)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81647cfd)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/fan.c (ffffffff816df6c8)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/xen/sys-hypervisor.c (ffffffff82d176f9)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff8178d600)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff817b331e)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff817b7bcd)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff817baaaa)
Location: include/linux/sysfs.h:580
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff818846a7)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff8198b2d0)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81993b89)
Location: include/linux/sysfs.h:580
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
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
In kernel/module.c (ffffffff8115d3a7)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff813e330e)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8166ce7d)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_remove_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/fan.c (ffffffff816fd658)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/xen/sys-hypervisor.c (ffffffff830052e7)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff817b9110)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff817c7bfb)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
```
```
In drivers/base/bus.c (ffffffff817cc8e9)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff817cf6fa)
Location: include/linux/sysfs.h:602
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81892e67)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff8198eee0)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81996c29)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff830156a8)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_remove
  - drivers/cpufreq/intel_pstate.c:store_status
```
```
In drivers/devfreq/devfreq.c (ffffffff819cf0c7)
Location: include/linux/sysfs.h:602
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
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
In kernel/module.c (ffffffff8115e497)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff813e9f4e)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8164f88f)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/fan.c (ffffffff816df3e8)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8320fd65)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff8179c320)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff817ab10b)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_links_driver_bound
```
```
In drivers/base/bus.c (ffffffff817b0259)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff817b310a)
Location: include/linux/sysfs.h:604
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81875977)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81973530)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197b9e9)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff832209d7)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
```
```
In drivers/devfreq/devfreq.c (ffffffff819b4227)
Location: include/linux/sysfs.h:604
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
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
In kernel/module.c (ffffffff811836d7)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff8143bcce)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff816c15eb)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/fan.c (ffffffff817579b6)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_remove
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
```
```
In drivers/xen/sys-hypervisor.c (ffffffff832f8d26)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81825010)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff8183445b)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
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
```
```
In drivers/base/bus.c (ffffffff81839479)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff8183c5fa)
Location: include/linux/sysfs.h:610
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81906487)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81a1c230)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a24d76)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8330a30e)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
```
```
In drivers/devfreq/devfreq.c (ffffffff81a62e07)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
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
In kernel/module/sysfs.c (ffffffff81192187)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - kernel/module/sysfs.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff814b711e)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff817e6e0a)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/fan_attr.c (ffffffff8188b547)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
```
```
In drivers/xen/sys-hypervisor.c (ffffffff834b164c)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81964e90)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff81975f21)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
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
```
```
In drivers/base/bus.c (ffffffff8197ba69)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff8197f02a)
Location: include/linux/sysfs.h:610
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5925d)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81b852c0)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8e519)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff834c3b58)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd42d7)
Location: include/linux/sysfs.h:610
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
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
In kernel/module/sysfs.c (ffffffff811cf897)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - kernel/module/sysfs.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff8154e41e)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8190bd9a)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/fan_attr.c (ffffffff819d2227)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
```
```
In drivers/xen/sys-hypervisor.c (ffffffff83eeb80a)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81ace2b0)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff81ae1fd1)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
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
```
```
In drivers/base/bus.c (ffffffff81ae8b59)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff81aec75a)
Location: include/linux/sysfs.h:626
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81be301e)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81d242b0)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2e0d9)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff83f03c03)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
```
```
In drivers/devfreq/devfreq.c (ffffffff81d8160e)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
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
In kernel/module/sysfs.c (ffffffff811e3a37)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - kernel/module/sysfs.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff815860de)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8194f41a)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/fan_attr.c (ffffffff81a1983e)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
```
```
In drivers/xen/sys-hypervisor.c (ffffffff837112b0)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81b1cc40)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff81b2fed0)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
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
```
```
In drivers/base/bus.c (ffffffff81b36e8c)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff81b3aa2a)
Location: include/linux/sysfs.h:626
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3af1e)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81d8d4cc)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d97350)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff83729c10)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
```
```
In drivers/devfreq/devfreq.c (ffffffff81def9ce)
Location: include/linux/sysfs.h:626
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
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
In kernel/module/sysfs.c (ffffffff811f9797)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - kernel/module/sysfs.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff815bebbe)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8199884a)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
  - drivers/pci/hotplug/pci_hotplug_core.c:fs_add_slot
```
```
In drivers/acpi/fan_attr.c (ffffffff81a64b0e)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_delete_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
  - drivers/acpi/fan_attr.c:acpi_fan_create_attributes
```
```
In drivers/xen/sys-hypervisor.c (ffffffff83944c40)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff81b73160)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff81b876d0)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
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
```
```
In drivers/base/bus.c (ffffffff81b8e8ac)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
```
```
In drivers/base/driver.c (ffffffff81b924ea)
Location: include/linux/sysfs.h:628
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81cefb43)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81e44d7c)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4efd0)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8395dbdd)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:store_status
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea5f8e)
Location: include/linux/sysfs.h:628
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
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
In kernel/module.c (ffff8000101bff10)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffff8000104567e8)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffff800010707990)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
```
In drivers/soc/xilinx/zynqmp_power.c (ffff8000108201f8)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_remove
```
```
In drivers/xen/sys-hypervisor.c (ffff8000114921d0)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffff8000108c47c4)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffff8000108e498c)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffff8000108e8170)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffff8000108ec078)
Location: include/linux/sysfs.h:579
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffff8000109d4a00)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffff800010b12b68)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1fbf8)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
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
In kernel/module.c (c0407650)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (c0618840)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/iommu/iommu.c (c09bbc40)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (c09d33ac)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (c09d65cc)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (c09da0b0)
Location: include/linux/sysfs.h:579
Inline: True
```
```
In drivers/net/phy/phy_device.c (c0abc624)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (c0bf0b44)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (c0bfad4c)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
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
In kernel/module.c (c000000000225ae0)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (c000000000570720)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (c00000000088000c)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
```
In drivers/iommu/iommu.c (c00000000096a658)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (c000000000979e10)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (c00000000097e460)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (c000000000983a64)
Location: include/linux/sysfs.h:579
Inline: True
```
```
In drivers/net/phy/phy_device.c (c000000000a95340)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (c000000000c071c0)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (c000000000c13fe8)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
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
In kernel/module.c (ffffffe00014232c)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffe0002e7f82)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d5388)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
```
In drivers/base/core.c (ffffffe000579800)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffe00057c490)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffe00057f686)
Location: include/linux/sysfs.h:579
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffe000620d0a)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffe0006ff68c)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
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
In kernel/module.c (ffffffff81149657)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff8137f15e)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81592c7b)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
```
In drivers/xen/sys-hypervisor.c (ffffffff828e7b1a)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff8169ea30)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff816bf98d)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff816c2d77)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff816c63ca)
Location: include/linux/sysfs.h:579
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff8178067f)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81860472)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81866609)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
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
In kernel/module.c (ffffffff8113c907)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff8136fbee)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81581e0b)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
```
In drivers/iommu/iommu.c (ffffffff8167c420)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff8169ac3d)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff8169e027)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff816a162a)
Location: include/linux/sysfs.h:579
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81760417)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff81827a42)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182f2b9)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
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
In kernel/module.c (ffffffff81147507)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff8137cc2e)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815931bb)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
```
In drivers/xen/sys-hypervisor.c (ffffffff828fb620)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff816ccca0)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff816ede5d)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff816f1247)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff816f489a)
Location: include/linux/sysfs.h:579
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817b0a2f)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff818afaa2)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b7399)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
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
In kernel/module.c (ffffffff81154117)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - kernel/module.c:module_remove_modinfo_attrs
```
```
In fs/sysfs/file.c (ffffffff8139070e)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
```
```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815ad63b)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
  - drivers/pci/hotplug/pci_hotplug_core.c:pci_hp_del
```
```
In drivers/xen/sys-hypervisor.c (ffffffff82901351)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
  - drivers/xen/sys-hypervisor.c:hyper_sysfs_init
```
```
In drivers/iommu/iommu.c (ffffffff816e7180)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_set_name
```
```
In drivers/base/core.c (ffffffff8170869d)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
```
```
In drivers/base/bus.c (ffffffff8170ba87)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_remove_file
```
```
In drivers/base/driver.c (ffffffff8170f12a)
Location: include/linux/sysfs.h:579
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817ca9bf)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_detach
```
```
In drivers/edac/edac_device_sysfs.c (ffffffff818cbd32)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_remove_main_sysfs_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d3f89)
Location: include/linux/sysfs.h:579
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
</details>
</li>
</ul>

## Differences
