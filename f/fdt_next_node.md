# Function: <code>fdt_next_node</code>

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
int fdt_next_node(const void *fdt, int offset, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffff80001143dae8)
Location: scripts/dtc/libfdt/fdt.c:197
Inline: False
Direct callers:
  - lib/fdt.c:fdt_next_subnode
  - lib/fdt.c:fdt_first_subnode
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_ro.c:fdt_find_max_phandle
  - lib/fdt_wip.c:fdt_node_end_offset_
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt.c:fdt_next_subnode
  - lib/fdt.c:fdt_first_subnode
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_ro.c:fdt_find_max_phandle
  - lib/fdt_wip.c:fdt_node_end_offset_
```
**Symbols:**

```
ffff800010d85440-ffff800010d85534: fdt_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_next_node(const void *fdt, int offset, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c0e80488)
Location: scripts/dtc/libfdt/fdt.c:197
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt.c:fdt_next_subnode
  - lib/fdt.c:fdt_first_subnode
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_ro.c:fdt_find_max_phandle
  - lib/fdt_wip.c:fdt_node_end_offset_
```
**Symbols:**

```
c0e80488-c0e8058c: fdt_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_next_node(const void *fdt, int offset, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c000000000ec4660)
Location: scripts/dtc/libfdt/fdt.c:197
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:unflatten_dt_nodes
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt.c:fdt_next_subnode
  - lib/fdt.c:fdt_first_subnode
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_ro.c:fdt_find_max_phandle
  - lib/fdt_ro.c:fdt_find_max_phandle
  - lib/fdt_wip.c:fdt_nop_node
```
**Symbols:**

```
c000000000ec4660-c000000000ec47c0: fdt_next_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_next_node(const void *fdt, int offset, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffffffe0008af59e)
Location: scripts/dtc/libfdt/fdt.c:197
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/fdt.c:fdt_next_subnode
  - lib/fdt.c:fdt_first_subnode
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_ro.c:fdt_find_max_phandle
  - lib/fdt_wip.c:fdt_nop_node
```
**Symbols:**

```
ffffffe0008af59e-ffffffe0008af66c: fdt_next_node (STB_GLOBAL)
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
