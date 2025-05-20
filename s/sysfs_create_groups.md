# Function: <code>sysfs_create_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8128d970)
Location: fs/sysfs/group.c:173
Inline: False
Direct callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
```
**Symbols:**

```
ffffffff8128d970-ffffffff8128d9ed: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812bafd0)
Location: fs/sysfs/group.c:173
Inline: False
Direct callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
```
**Symbols:**

```
ffffffff812bafd0-ffffffff812bb04e: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812d0700)
Location: fs/sysfs/group.c:173
Inline: False
Direct callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff812d0700-ffffffff812d077e: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812ddd80)
Location: fs/sysfs/group.c:173
Inline: True
Direct callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff812ddd80-ffffffff812dde2c: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813026c0)
Location: fs/sysfs/group.c:173
Inline: True
Direct callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
```
**Symbols:**

```
ffffffff813026c0-ffffffff8130276c: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81330560)
Location: fs/sysfs/group.c:177
Inline: True
Direct callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff81330560-ffffffff813305ff: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81347980)
Location: fs/sysfs/group.c:191
Inline: True
Direct callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff81347980-ffffffff81347a1f: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8136fe10)
Location: fs/sysfs/group.c:211
Inline: False
Direct callers:
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8136fe10-ffffffff8136fe2d: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81388180)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81388180-ffffffff8138819d: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d3120)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - lib/kobject.c:create_dir
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff813d3120-ffffffff813d313d: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e4e80)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - lib/kobject.c:create_dir
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff813e4e80-ffffffff813e4e9d: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813eba80)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - lib/kobject.c:create_dir
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff813eba80-ffffffff813eba9d: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143d810)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - kernel/irq/msi.c:msi_populate_sysfs
  - lib/kobject.c:create_dir
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff8143d810-ffffffff8143d82d: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b8b80)
Location: fs/sysfs/group.c:211
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - lib/kobject.c:kobject_add_internal
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff814b8b80-ffffffff814b8b9f: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81550220)
Location: fs/sysfs/group.c:211
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/dax/bus.c:alloc_dax_region
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81550220-ffffffff8155023f: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81587f20)
Location: fs/sysfs/group.c:215
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:class_register
  - drivers/dax/bus.c:alloc_dax_region
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81587f20-ffffffff81587f3f: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c0ae0)
Location: fs/sysfs/group.c:215
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:class_register
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff815c0ae0-ffffffff815c0aff: sysfs_create_groups (STB_GLOBAL)
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
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffff8000104583c0)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffff8000104583c0-ffff80001045840c: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c061a498)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c061a498-c061a4c8: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c000000000572dd0)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c000000000572dd0-c000000000572df8: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffe0002e9502)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffe0002e9502-ffffffe0002e9546: sysfs_create_groups (STB_GLOBAL)
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
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81380760)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81380760-ffffffff8138077d: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813711f0)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff813711f0-ffffffff8137120d: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8137e230)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8137e230-ffffffff8137e24d: sysfs_create_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_create_groups(struct kobject *kobj, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81391e30)
Location: fs/sysfs/group.c:212
Inline: False
Direct callers:
  - kernel/power/main.c:pm_init
  - drivers/pci/msi.c:populate_msi_sysfs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:devm_device_add_groups
  - drivers/base/bus.c:bus_register
  - drivers/base/driver.c:driver_register
  - drivers/base/class.c:__class_register
  - drivers/base/class.c:__class_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81391e30-ffffffff81391e4d: sysfs_create_groups (STB_GLOBAL)
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
