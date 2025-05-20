# Function: <code>fdt_set_off_dt_struct</code>

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
In lib/fdt_rw.c (ffff80001143f758)
Location: scripts/dtc/libfdt/libfdt.h:255
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
```
```
In lib/fdt_sw.c (ffff8000114404ac)
Location: scripts/dtc/libfdt/libfdt.h:255
Inline: True
Inline callers:
  - lib/fdt_sw.c:fdt_create_with_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c0e820bc)
Location: scripts/dtc/libfdt/libfdt.h:255
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (c000000000ec6f98)
Location: scripts/dtc/libfdt/libfdt.h:255
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/fdt_rw.c (ffffffe0008b10a4)
Location: scripts/dtc/libfdt/libfdt.h:255
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_packblocks_
  - lib/fdt_rw.c:fdt_splice_mem_rsv_
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
