# Function: <code>fdt_offset_ptr_</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffff80001143d930)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt.c:fdt_offset_ptr
  - lib/fdt.c:fdt_offset_ptr
```
```
In lib/fdt_ro.c (ffff80001143de94)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_get_name
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_get_name
```
```
In lib/fdt_rw.c (ffff800011440090)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_property_
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_property_
```
```
In lib/fdt_sw.c (ffff800011440a58)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt_sw.c:fdt_finish
  - lib/fdt_sw.c:fdt_grab_space_
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c0e802b4)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt.c:fdt_offset_ptr
```
```
In lib/fdt_ro.c (c0e80840)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_get_name
```
```
In lib/fdt_rw.c (c0e829ac)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_property_
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/fdt.c (c000000000ec4374)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt.c:fdt_offset_ptr
```
```
In lib/fdt_ro.c (c000000000ec4bbc)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_get_name
```
```
In lib/fdt_rw.c (c000000000ec7da8)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_property_
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/fdt.c (ffffffe0008af3cc)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt.c:fdt_offset_ptr
```
```
In lib/fdt_ro.c (ffffffe0008af8c4)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_get_property_by_offset_
  - lib/fdt_ro.c:fdt_get_name
```
```
In lib/fdt_rw.c (ffffffe0008b1bf6)
Location: scripts/dtc/libfdt/libfdt_internal.h:26
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_del_node
  - lib/fdt_rw.c:fdt_add_property_
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
