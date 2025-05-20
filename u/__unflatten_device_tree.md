# Function: <code>__unflatten_device_tree</code>

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
void *__unflatten_device_tree(const void *blob, struct device_node *dad, struct device_node **mynodes, void * (*dt_alloc)(u64, u64), bool detached);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff800010b71fc0)
Location: drivers/of/fdt.c:367
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_device_tree
  - drivers/of/fdt.c:of_fdt_unflatten_tree
```
**Symbols:**

```
ffff800010b71fc0-ffff800010b72298: __unflatten_device_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__unflatten_device_tree(const void *blob, struct device_node *dad, struct device_node **mynodes, void * (*dt_alloc)(u64, u64), bool detached);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0c545c0)
Location: drivers/of/fdt.c:367
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_device_tree
  - drivers/of/fdt.c:of_fdt_unflatten_tree
```
**Symbols:**

```
c0c545c0-c0c54870: __unflatten_device_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__unflatten_device_tree(const void *blob, struct device_node *dad, struct device_node **mynodes, void * (*dt_alloc)(u64, u64), bool detached);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c000000000c4e430)
Location: drivers/of/fdt.c:367
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_device_tree
  - drivers/of/fdt.c:of_fdt_unflatten_tree
```
**Symbols:**

```
c000000000c4e430-c000000000c4e7cc: __unflatten_device_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__unflatten_device_tree(const void *blob, struct device_node *dad, struct device_node **mynodes, void * (*dt_alloc)(u64, u64), bool detached);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe000725c7c)
Location: drivers/of/fdt.c:367
Inline: False
Direct callers:
  - drivers/of/fdt.c:unflatten_device_tree
  - drivers/of/fdt.c:of_fdt_unflatten_tree
```
**Symbols:**

```
ffffffe000725c7c-ffffffe000725f88: __unflatten_device_tree (STB_GLOBAL)
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
