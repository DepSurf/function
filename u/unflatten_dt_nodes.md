# Function: <code>unflatten_dt_nodes</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int unflatten_dt_nodes(const void *blob, void *mem, struct device_node *dad, struct device_node **nodepp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff800010b71af0)
Location: drivers/of/fdt.c:287
Inline: False
Direct callers:
  - drivers/of/fdt.c:__unflatten_device_tree
  - drivers/of/fdt.c:__unflatten_device_tree
```
**Symbols:**

```
ffff800010b71af0-ffff800010b71f8c: unflatten_dt_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unflatten_dt_nodes(const void *blob, void *mem, struct device_node *dad, struct device_node **nodepp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0c54040)
Location: drivers/of/fdt.c:287
Inline: False
Direct callers:
  - drivers/of/fdt.c:__unflatten_device_tree
  - drivers/of/fdt.c:__unflatten_device_tree
```
**Symbols:**

```
c0c54040-c0c545a0: unflatten_dt_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unflatten_dt_nodes(const void *blob, void *mem, struct device_node *dad, struct device_node **nodepp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c000000000c4d8b0)
Location: drivers/of/fdt.c:287
Inline: False
Direct callers:
  - drivers/of/fdt.c:__unflatten_device_tree
  - drivers/of/fdt.c:__unflatten_device_tree
```
**Symbols:**

```
c000000000c4d8b0-c000000000c4e3e8: unflatten_dt_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unflatten_dt_nodes(const void *blob, void *mem, struct device_node *dad, struct device_node **nodepp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe0007257cc)
Location: drivers/of/fdt.c:287
Inline: False
Direct callers:
  - drivers/of/fdt.c:__unflatten_device_tree
  - drivers/of/fdt.c:__unflatten_device_tree
```
**Symbols:**

```
ffffffe0007257cc-ffffffe000725c4c: unflatten_dt_nodes (STB_LOCAL)
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
