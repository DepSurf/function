# Function: <code>sysfs_remove_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8128d9f0)
Location: fs/sysfs/group.c:261
Inline: False
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_unregister
```
**Symbols:**

```
ffffffff8128d9f0-ffffffff8128da32: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812bb050)
Location: fs/sysfs/group.c:261
Inline: False
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_unregister
```
**Symbols:**

```
ffffffff812bb050-ffffffff812bb092: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812d0780)
Location: fs/sysfs/group.c:261
Inline: False
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
```
**Symbols:**

```
ffffffff812d0780-ffffffff812d07c2: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812dde30)
Location: fs/sysfs/group.c:261
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
```
**Symbols:**

```
ffffffff812dde30-ffffffff812dde73: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81302770)
Location: fs/sysfs/group.c:261
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
```
**Symbols:**

```
ffffffff81302770-ffffffff813027b3: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81330600)
Location: fs/sysfs/group.c:265
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81330600-ffffffff81330642: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81347930)
Location: fs/sysfs/group.c:280
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81347930-ffffffff81347972: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8136fd20)
Location: fs/sysfs/group.c:304
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff8136fd20-ffffffff8136fd62: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81388090)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff81388090-ffffffff813880d2: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d3030)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - lib/kobject.c:__kobject_del
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff813d3030-ffffffff813d3072: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e4d90)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - lib/kobject.c:__kobject_del
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff813e4d90-ffffffff813e4dd2: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813eb990)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - lib/kobject.c:__kobject_del
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff813eb990-ffffffff813eb9d2: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143d720)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - kernel/irq/msi.c:msi_destroy_sysfs
  - lib/kobject.c:__kobject_del
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff8143d720-ffffffff8143d762: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b9190)
Location: fs/sysfs/group.c:304
Inline: True
Direct callers:
  - lib/kobject.c:__kobject_del
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff814b9190-ffffffff814b91e6: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815508c0)
Location: fs/sysfs/group.c:304
Inline: True
Direct callers:
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:alloc_dax_region
  - lib/kobject.c:__kobject_del
```
**Symbols:**

```
ffffffff815508c0-ffffffff81550916: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815885b0)
Location: fs/sysfs/group.c:308
Inline: True
Direct callers:
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - lib/kobject.c:__kobject_del
```
**Symbols:**

```
ffffffff815885b0-ffffffff81588606: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c1170)
Location: fs/sysfs/group.c:308
Inline: True
Direct callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove
  - lib/kobject.c:__kobject_del
```
**Symbols:**

```
ffffffff815c1170-ffffffff815c11c6: sysfs_remove_groups (STB_GLOBAL)
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
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffff8000104582a8)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_remove
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffff8000104582a8-ffff8000104582fc: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c061a3c4)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
c061a3c4-c061a408: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c000000000572c20)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
c000000000572c20-c000000000572cac: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffe0002e941e)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffe0002e941e-ffffffe0002e946a: sysfs_remove_groups (STB_GLOBAL)
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
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81380670)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff81380670-ffffffff813806b2: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81371100)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff81371100-ffffffff81371142: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8137e140)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff8137e140-ffffffff8137e182: sysfs_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sysfs_remove_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81391d40)
Location: fs/sysfs/group.c:305
Inline: True
Direct callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/video/fbdev/efifb.c:efifb_remove
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:devm_attr_groups_remove
  - drivers/base/bus.c:bus_unregister
  - drivers/base/class.c:class_unregister
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff81391d40-ffffffff81391d82: sysfs_remove_groups (STB_GLOBAL)
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
