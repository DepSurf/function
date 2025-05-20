# Function: <code>fdt_node_check_compatible</code>

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
int fdt_node_check_compatible(const void *fdt, int nodeoffset, const char *compatible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143f290)
Location: scripts/dtc/libfdt/fdt_ro.c:798
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
```
**Symbols:**

```
ffff800010d86d08-ffff800010d86d7c: fdt_node_check_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_node_check_compatible(const void *fdt, int nodeoffset, const char *compatible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e81c3c)
Location: scripts/dtc/libfdt/fdt_ro.c:798
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
```
**Symbols:**

```
c0e81c3c-c0e81cb8: fdt_node_check_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_node_check_compatible(const void *fdt, int nodeoffset, const char *compatible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec68e0)
Location: scripts/dtc/libfdt/fdt_ro.c:798
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
```
**Symbols:**

```
c000000000ec68e0-c000000000ec6970: fdt_node_check_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_node_check_compatible(const void *fdt, int nodeoffset, const char *compatible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008b0af6)
Location: scripts/dtc/libfdt/fdt_ro.c:798
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/fdt_ro.c:fdt_node_offset_by_compatible
```
**Symbols:**

```
ffffffe0008b0af6-ffffffe0008b0b44: fdt_node_check_compatible (STB_GLOBAL)
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
