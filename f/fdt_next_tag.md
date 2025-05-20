# Function: <code>fdt_next_tag</code>

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
uint32_t fdt_next_tag(const void *fdt, int startoffset, int *nextoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffff80001143d948)
Location: scripts/dtc/libfdt/fdt.c:126
Inline: False
Direct callers:
  - lib/fdt.c:fdt_next_node
  - lib/fdt.c:fdt_next_node
  - lib/fdt.c:fdt_check_prop_offset_
  - lib/fdt.c:fdt_check_node_offset_
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_ro.c:nextprop_
  - lib/fdt_rw.c:fdt_open_into
  - lib/fdt_sw.c:fdt_finish
  - lib/fdt_sw.c:fdt_finish
  - lib/fdt.c:fdt_next_node
  - lib/fdt.c:fdt_next_node
  - lib/fdt.c:fdt_check_prop_offset_
  - lib/fdt.c:fdt_check_node_offset_
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_ro.c:nextprop_
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
ffff800010d852a0-ffff800010d853bc: fdt_next_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
uint32_t fdt_next_tag(const void *fdt, int startoffset, int *nextoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c0e802c4)
Location: scripts/dtc/libfdt/fdt.c:126
Inline: False
Direct callers:
  - lib/fdt.c:fdt_next_node
  - lib/fdt.c:fdt_check_prop_offset_
  - lib/fdt.c:fdt_check_node_offset_
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_ro.c:nextprop_
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
c0e802c4-c0e803f8: fdt_next_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
uint32_t fdt_next_tag(const void *fdt, int startoffset, int *nextoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c000000000ec4390)
Location: scripts/dtc/libfdt/fdt.c:126
Inline: False
Direct callers:
  - lib/fdt.c:fdt_next_node
  - lib/fdt.c:fdt_next_node
  - lib/fdt.c:fdt_check_prop_offset_
  - lib/fdt.c:fdt_check_node_offset_
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_ro.c:nextprop_
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
c000000000ec4390-c000000000ec45a0: fdt_next_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
uint32_t fdt_next_tag(const void *fdt, int startoffset, int *nextoffset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffffffe0008af3e2)
Location: scripts/dtc/libfdt/fdt.c:126
Inline: False
Direct callers:
  - lib/fdt.c:fdt_next_node
  - lib/fdt.c:fdt_next_node
  - lib/fdt.c:fdt_check_prop_offset_
  - lib/fdt.c:fdt_check_node_offset_
  - lib/fdt_ro.c:fdt_check_full
  - lib/fdt_ro.c:nextprop_
  - lib/fdt_rw.c:fdt_open_into
```
**Symbols:**

```
ffffffe0008af3e2-ffffffe0008af52a: fdt_next_tag (STB_GLOBAL)
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
