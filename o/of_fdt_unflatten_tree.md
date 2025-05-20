# Function: <code>of_fdt_unflatten_tree</code>

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
void *of_fdt_unflatten_tree(const long unsigned int *blob, struct device_node *dad, struct device_node **mynodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff800010b72298)
Location: drivers/of/fdt.c:448
Inline: False
Direct callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
ffff800010b72298-ffff800010b7230c: of_fdt_unflatten_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *of_fdt_unflatten_tree(const long unsigned int *blob, struct device_node *dad, struct device_node **mynodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0c54870)
Location: drivers/of/fdt.c:448
Inline: False
Direct callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
c0c54870-c0c548dc: of_fdt_unflatten_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *of_fdt_unflatten_tree(const long unsigned int *blob, struct device_node *dad, struct device_node **mynodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c000000000c4e7d0)
Location: drivers/of/fdt.c:448
Inline: False
Direct callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
c000000000c4e7d0-c000000000c4e85c: of_fdt_unflatten_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *of_fdt_unflatten_tree(const long unsigned int *blob, struct device_node *dad, struct device_node **mynodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe000725f88)
Location: drivers/of/fdt.c:448
Inline: False
Direct callers:
  - drivers/of/overlay.c:of_overlay_fdt_apply
```
**Symbols:**

```
ffffffe000725f88-ffffffe000725ff0: of_fdt_unflatten_tree (STB_GLOBAL)
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
