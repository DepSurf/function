# Function: <code>sysfs_remove_link_from_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8128d2d0)
Location: fs/sysfs/group.c:356
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
```
**Symbols:**

```
ffffffff8128d2d0-ffffffff8128d30c: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812ba950)
Location: fs/sysfs/group.c:356
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
```
**Symbols:**

```
ffffffff812ba950-ffffffff812ba98c: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812d0080)
Location: fs/sysfs/group.c:356
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
```
**Symbols:**

```
ffffffff812d0080-ffffffff812d00bc: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812dd750)
Location: fs/sysfs/group.c:356
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
```
**Symbols:**

```
ffffffff812dd750-ffffffff812dd78c: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81302080)
Location: fs/sysfs/group.c:356
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
```
**Symbols:**

```
ffffffff81302080-ffffffff813020bc: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81330050)
Location: fs/sysfs/group.c:365
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
```
**Symbols:**

```
ffffffff81330050-ffffffff8133008c: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813473f0)
Location: fs/sysfs/group.c:380
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
```
**Symbols:**

```
ffffffff813473f0-ffffffff8134742c: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8136f7f0)
Location: fs/sysfs/group.c:404
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff8136f7f0-ffffffff8136f82e: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81387b50)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff81387b50-ffffffff81387b8e: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d2d30)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff813d2d30-ffffffff813d2d6e: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e4a90)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff813e4a90-ffffffff813e4ace: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813eb690)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff813eb690-ffffffff813eb6ce: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143d420)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff8143d420-ffffffff8143d45e: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b8d70)
Location: fs/sysfs/group.c:404
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff814b8d70-ffffffff814b8db8: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81550450)
Location: fs/sysfs/group.c:404
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff81550450-ffffffff81550498: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81588140)
Location: fs/sysfs/group.c:408
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff81588140-ffffffff81588188: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c0d00)
Location: fs/sysfs/group.c:408
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff815c0d00-ffffffff815c0d48: sysfs_remove_link_from_group (STB_GLOBAL)
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
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffff800010457cb8)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffff800010457cb8-ffff800010457d18: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c0619f44)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
```
**Symbols:**

```
c0619f44-c0619f88: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c000000000572290)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
c000000000572290-c000000000572304: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffe0002e8f56)
Location: fs/sysfs/group.c:405
Inline: False
```
**Symbols:**

```
ffffffe0002e8f56-ffffffe0002e8fac: sysfs_remove_link_from_group (STB_GLOBAL)
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
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81380130)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff81380130-ffffffff8138016e: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81370bc0)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff81370bc0-ffffffff81370bfe: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8137dc00)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff8137dc00-ffffffff8137dc3e: sysfs_remove_link_from_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sysfs_remove_link_from_group(struct kobject *kobj, const char *group_name, const char *link_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81391700)
Location: fs/sysfs/group.c:405
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_hide_list
  - drivers/iommu/iommu-sysfs.c:iommu_device_unlink
  - drivers/iommu/iommu-sysfs.c:iommu_device_link
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff81391700-ffffffff8139173e: sysfs_remove_link_from_group (STB_GLOBAL)
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
