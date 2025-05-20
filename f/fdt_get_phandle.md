# Function: <code>fdt_get_phandle</code>

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
uint32_t fdt_get_phandle(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e698)
Location: scripts/dtc/libfdt/fdt_ro.c:486
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_find_max_phandle
  - drivers/of/fdt.c:of_get_flat_dt_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_find_max_phandle
```
**Symbols:**

```
ffff800010d86068-ffff800010d86120: fdt_get_phandle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
uint32_t fdt_get_phandle(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e81070)
Location: scripts/dtc/libfdt/fdt_ro.c:486
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_get_flat_dt_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_find_max_phandle
```
**Symbols:**

```
c0e81070-c0e81120: fdt_get_phandle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
uint32_t fdt_get_phandle(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec5780)
Location: scripts/dtc/libfdt/fdt_ro.c:486
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_get_flat_dt_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_find_max_phandle
```
**Symbols:**

```
c000000000ec5780-c000000000ec5850: fdt_get_phandle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
uint32_t fdt_get_phandle(const void *fdt, int nodeoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008b021c)
Location: scripts/dtc/libfdt/fdt_ro.c:486
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_get_flat_dt_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_find_max_phandle
```
**Symbols:**

```
ffffffe0008b021c-ffffffe0008b02c4: fdt_get_phandle (STB_GLOBAL)
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
