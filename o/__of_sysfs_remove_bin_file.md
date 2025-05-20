# Function: <code>__of_sysfs_remove_bin_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __of_sysfs_remove_bin_file(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffff800010b70250)
Location: drivers/of/kobj.c:87
Inline: True
Inline callers:
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_update_property_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
```
**Symbols:**

```
ffff800010b6ffe8-ffff800010b70024: __of_sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __of_sysfs_remove_bin_file(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c0c52b30)
Location: drivers/of/kobj.c:87
Inline: True
Inline callers:
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_update_property_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
```
**Symbols:**

```
c0c528fc-c0c5292c: __of_sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __of_sysfs_remove_bin_file(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c000000000c4b610)
Location: drivers/of/kobj.c:87
Inline: True
Inline callers:
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_update_property_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
```
**Symbols:**

```
c000000000c4b2b0-c000000000c4b304: __of_sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __of_sysfs_remove_bin_file(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffffffe0007244b0)
Location: drivers/of/kobj.c:87
Inline: True
Inline callers:
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_update_property_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
```
**Symbols:**

```
ffffffe0007242a6-ffffffe0007242e6: __of_sysfs_remove_bin_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
