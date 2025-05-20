# Function: <code>fdt_node_end_offset_</code>

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
int fdt_node_end_offset_(void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (ffff800011440c20)
Location: scripts/dtc/libfdt/fdt_wip.c:73
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_wip.c:fdt_nop_node
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_wip.c:fdt_nop_node
```
**Symbols:**

```
ffff800010d87f70-ffff800010d87fe0: fdt_node_end_offset_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_node_end_offset_(void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (c0e82dcc)
Location: scripts/dtc/libfdt/fdt_wip.c:73
Inline: False
Direct callers:
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_wip.c:fdt_nop_node
```
**Symbols:**

```
c0e82dcc-c0e82e4c: fdt_node_end_offset_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fdt_node_end_offset_(void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (c000000000ec84fc)
Location: scripts/dtc/libfdt/fdt_wip.c:73
Inline: True
Inline callers:
  - lib/fdt_wip.c:fdt_nop_node
Direct callers:
  - lib/fdt_rw.c:fdt_del_node
```
**Symbols:**

```
c000000000ec8420-c000000000ec84c8: fdt_node_end_offset_ (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fdt_node_end_offset_(void *fdt, int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/fdt_wip.c (ffffffe0008b210a)
Location: scripts/dtc/libfdt/fdt_wip.c:73
Inline: True
Inline callers:
  - lib/fdt_wip.c:fdt_nop_node
Direct callers:
  - lib/fdt_rw.c:fdt_del_node
```
**Symbols:**

```
ffffffe0008b20ce-ffffffe0008b210a: fdt_node_end_offset_ (STB_GLOBAL)
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
