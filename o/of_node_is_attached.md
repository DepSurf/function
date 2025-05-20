# Function: <code>of_node_is_attached</code>

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
int of_node_is_attached(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffff800010b70238)
Location: drivers/of/kobj.c:14
Inline: True
Inline callers:
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
  - drivers/of/kobj.c:__of_add_property_sysfs
```
**Symbols:**

```
ffff800010b6fec8-ffff800010b6fefc: of_node_is_attached (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int of_node_is_attached(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c0c52b18)
Location: drivers/of/kobj.c:14
Inline: True
Inline callers:
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
  - drivers/of/kobj.c:__of_add_property_sysfs
```
**Symbols:**

```
c0c527d8-c0c527fc: of_node_is_attached (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int of_node_is_attached(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (c000000000c4b5e4)
Location: drivers/of/kobj.c:14
Inline: True
Inline callers:
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
  - drivers/of/kobj.c:__of_add_property_sysfs
```
**Symbols:**

```
c000000000c4b0b0-c000000000c4b0d8: of_node_is_attached (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int of_node_is_attached(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/kobj.c (ffffffe0007244a2)
Location: drivers/of/kobj.c:14
Inline: True
Inline callers:
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - drivers/of/kobj.c:__of_remove_property_sysfs
  - drivers/of/kobj.c:__of_add_property_sysfs
```
**Symbols:**

```
ffffffe0007241b0-ffffffe0007241de: of_node_is_attached (STB_GLOBAL)
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
