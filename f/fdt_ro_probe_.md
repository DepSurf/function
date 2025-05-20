# Function: <code>fdt_ro_probe_</code>

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
int fdt_ro_probe_(const void *fdt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffff80001143d708)
Location: scripts/dtc/libfdt/fdt.c:18
Inline: True
Direct callers:
  - lib/fdt.c:fdt_move
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_supernode_atdepth_offset
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_subnode_offset_namelen
  - lib/fdt_ro.c:fdt_get_mem_rsv
  - lib/fdt_ro.c:fdt_get_string
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_rw_probe_
  - lib/fdt.c:fdt_move
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_supernode_atdepth_offset
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_subnode_offset_namelen
  - lib/fdt_ro.c:fdt_get_mem_rsv
  - lib/fdt_ro.c:fdt_get_string
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_rw_probe_
```
**Symbols:**

```
ffff800010d85060-ffff800010d850d4: fdt_ro_probe_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fdt_ro_probe_(const void *fdt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c0e8006c)
Location: scripts/dtc/libfdt/fdt.c:18
Inline: True
Direct callers:
  - lib/fdt.c:fdt_move
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_supernode_atdepth_offset
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_subnode_offset_namelen
  - lib/fdt_ro.c:fdt_get_mem_rsv
  - lib/fdt_ro.c:fdt_get_string
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_rw_probe_
```
**Symbols:**

```
c0e8006c-c0e800ec: fdt_ro_probe_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fdt_ro_probe_(const void *fdt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c000000000ec40c0)
Location: scripts/dtc/libfdt/fdt.c:18
Inline: True
Direct callers:
  - lib/fdt.c:fdt_move
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_supernode_atdepth_offset
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_subnode_offset_namelen
  - lib/fdt_ro.c:fdt_get_mem_rsv
  - lib/fdt_ro.c:fdt_get_string
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_rw_probe_
```
**Symbols:**

```
c000000000ec40c0-c000000000ec4138: fdt_ro_probe_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fdt_ro_probe_(const void *fdt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffffffe0008aefe6)
Location: scripts/dtc/libfdt/fdt.c:18
Inline: True
Direct callers:
  - lib/fdt.c:fdt_move
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - lib/fdt_ro.c:fdt_node_offset_by_phandle
  - lib/fdt_ro.c:fdt_node_offset_by_prop_value
  - lib/fdt_ro.c:fdt_supernode_atdepth_offset
  - lib/fdt_ro.c:fdt_get_path
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_subnode_offset_namelen
  - lib/fdt_ro.c:fdt_get_mem_rsv
  - lib/fdt_ro.c:fdt_get_string
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_rw.c:fdt_rw_probe_
```
**Symbols:**

```
ffffffe0008aefe6-ffffffe0008af0b8: fdt_ro_probe_ (STB_GLOBAL)
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
