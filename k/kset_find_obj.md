# Function: <code>kset_find_obj</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813ebf20)
Location: lib/kobject.c:847
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - drivers/pci/slot.c:make_slot_name
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff813ebf20-ffffffff813ebfb7: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431b00)
Location: lib/kobject.c:847
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff81431b00-ffffffff81431b97: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144dd70)
Location: lib/kobject.c:847
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff8144dd70-ffffffff8144de07: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818edff0)
Location: lib/kobject.c:850
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff818edff0-ffffffff818ee07c: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974220)
Location: lib/kobject.c:850
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff81974220-ffffffff819742d6: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0b10)
Location: lib/kobject.c:863
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff819d0b10-ffffffff819d0bc6: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a09db0)
Location: lib/kobject.c:863
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff81a09db0-ffffffff81a09e66: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79620)
Location: lib/kobject.c:894
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff81a79620-ffffffff81a796b5: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab0980)
Location: lib/kobject.c:894
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff81ab0980-ffffffff81ab0a15: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eabe0)
Location: lib/kobject.c:911
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_init
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/driver.c:driver_register
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff815eabe0-ffffffff815eac52: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f500)
Location: lib/kobject.c:908
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_init
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/driver.c:driver_register
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff8160f500-ffffffff8160f572: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2c40)
Location: lib/kobject.c:908
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/driver.c:driver_register
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff815f2c40-ffffffff815f2cb2: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8165fe20)
Location: lib/kobject.c:908
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/driver.c:driver_register
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff8165fe20-ffffffff8165fe92: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff817798b0)
Location: lib/kobject.c:876
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module/sysfs.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/driver.c:driver_register
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff817798b0-ffffffff81779926: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022860)
Location: lib/kobject.c:891
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module/sysfs.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/driver.c:driver_register
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff82022860-ffffffff820228d6: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a28d0)
Location: lib/kobject.c:892
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module/sysfs.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/bus.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff820a28d0-ffffffff820a2946: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217a950)
Location: lib/kobject.c:904
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module/sysfs.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/bus.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff8217a950-ffffffff8217a9c6: kset_find_obj (STB_GLOBAL)
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
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8a958)
Location: lib/kobject.c:894
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffff800010d8a958-ffff800010d8aa48: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e852f8)
Location: lib/kobject.c:894
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
c0e852f8-c0e85390: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecbc90)
Location: lib/kobject.c:894
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-elog.c:elog_event
  - arch/powerpc/platforms/powernv/opal-dump.c:process_dump
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/iommu/iommu.c:iommu_group_get_by_id
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
c000000000ecbc90-c000000000ecbf78: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b3f0e)
Location: lib/kobject.c:894
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffe0008b3f0e-ffffffe0008b3fc8: kset_find_obj (STB_GLOBAL)
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
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4f7d0)
Location: lib/kobject.c:894
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff81a4f7d0-ffffffff81a4f865: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0c8d0)
Location: lib/kobject.c:894
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff81a0c8d0-ffffffff81a0c965: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abbbc0)
Location: lib/kobject.c:894
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff81abbbc0-ffffffff81abbc55: kset_find_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kobject *kset_find_obj(struct kset *kset, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac8000)
Location: lib/kobject.c:894
Inline: False
Direct callers:
  - kernel/params.c:locate_module_kobject
  - kernel/module.c:mod_sysfs_setup
  - drivers/pci/slot.c:pci_hp_create_module_link
  - drivers/pci/slot.c:make_slot_name
  - drivers/base/driver.c:driver_find
  - drivers/base/module.c:module_add_driver
```
**Symbols:**

```
ffffffff81ac8000-ffffffff81ac8093: kset_find_obj (STB_GLOBAL)
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
