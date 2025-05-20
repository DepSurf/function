# Function: <code>kset_create_and_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813ec550)
Location: lib/kobject.c:936
Inline: False
Direct callers:
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:slab_sysfs_init
  - drivers/pci/slot.c:pci_slot_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/class.c:classes_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff813ec550-ffffffff813ec5e1: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81432820)
Location: lib/kobject.c:937
Inline: False
Direct callers:
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81432820-ffffffff814328a9: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144ea90)
Location: lib/kobject.c:937
Inline: False
Direct callers:
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff8144ea90-ffffffff8144eb19: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818eecb0)
Location: lib/kobject.c:940
Inline: False
Direct callers:
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff818eecb0-ffffffff818eed35: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974f70)
Location: lib/kobject.c:940
Inline: False
Direct callers:
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81974f70-ffffffff81974ff5: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d14a0)
Location: lib/kobject.c:960
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff819d14a0-ffffffff819d152f: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0aa60)
Location: lib/kobject.c:960
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81a0aa60-ffffffff81a0aaef: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a7a410)
Location: lib/kobject.c:991
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81a7a410-ffffffff81a7a4a4: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab1770)
Location: lib/kobject.c:991
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81ab1770-ffffffff81ab1804: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eb770)
Location: lib/kobject.c:1008
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff815eb770-ffffffff815eb85b: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81610090)
Location: lib/kobject.c:1005
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81610090-ffffffff8161017b: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f37d0)
Location: lib/kobject.c:1005
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff815f37d0-ffffffff815f38bb: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff816609a0)
Location: lib/kobject.c:1005
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff816609a0-ffffffff81660a8b: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8177a4e0)
Location: lib/kobject.c:973
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff8177a4e0-ffffffff8177a5c9: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82023610)
Location: lib/kobject.c:988
Inline: False
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff82023610-ffffffff820236a7: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a3680)
Location: lib/kobject.c:989
Inline: False
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff820a3680-ffffffff820a3717: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217b700)
Location: lib/kobject.c:1001
Inline: False
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff8217b700-ffffffff8217b7c6: kset_create_and_add (STB_GLOBAL)
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
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8b608)
Location: lib/kobject.c:991
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/of/base.c:of_core_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffff800010d8b608-ffff800010d8b6ac: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e85f48)
Location: lib/kobject.c:991
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/of/base.c:of_core_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
c0e85f48-c0e85fec: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecd240)
Location: lib/kobject.c:991
Inline: False
Direct callers:
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/platforms/powernv/opal-elog.c:opal_elog_init
  - arch/powerpc/platforms/powernv/opal-dump.c:opal_platform_dump_init
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/of/base.c:of_core_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
c000000000ecd240-c000000000ecd334: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b4ba8)
Location: lib/kobject.c:991
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/of/base.c:of_core_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffe0008b4ba8-ffffffe0008b4c34: kset_create_and_add (STB_GLOBAL)
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
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a505c0)
Location: lib/kobject.c:991
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81a505c0-ffffffff81a50654: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0d6c0)
Location: lib/kobject.c:991
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/hv/vmbus_drv.c:vmbus_device_register
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81a0d6c0-ffffffff81a0d754: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abc9b0)
Location: lib/kobject.c:991
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81abc9b0-ffffffff81abca44: kset_create_and_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kset *kset_create_and_add(const char *name, const struct kset_uevent_ops *uevent_ops, struct kobject *parent_kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac8e30)
Location: lib/kobject.c:991
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - mm/slub.c:slab_sysfs_init
  - mm/slub.c:sysfs_slab_add
  - drivers/pci/slot.c:pci_slot_init
  - drivers/iommu/iommu.c:iommu_init
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:buses_init
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:classes_init
  - drivers/base/swnode.c:software_node_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
```
**Symbols:**

```
ffffffff81ac8e30-ffffffff81ac8ec4: kset_create_and_add (STB_GLOBAL)
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
