# Function: <code>fdt_mem_rsv_</code>

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
In lib/fdt_ro.c (0)
Location: scripts/dtc/libfdt/libfdt_internal.h:36
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_mem_rsv
  - lib/fdt_ro.c:fdt_mem_rsv
```
```
In lib/fdt_rw.c (ffff80001143fa60)
Location: scripts/dtc/libfdt/libfdt_internal.h:36
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
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
In lib/fdt_ro.c (c0e80774)
Location: scripts/dtc/libfdt/libfdt_internal.h:36
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_mem_rsv
```
```
In lib/fdt_rw.c (c0e82388)
Location: scripts/dtc/libfdt/libfdt_internal.h:36
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
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
In lib/fdt_ro.c (c000000000ec4a84)
Location: scripts/dtc/libfdt/libfdt_internal.h:36
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_mem_rsv
```
```
In lib/fdt_rw.c (c000000000ec74a0)
Location: scripts/dtc/libfdt/libfdt_internal.h:36
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
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
In lib/fdt_ro.c (ffffffe0008af826)
Location: scripts/dtc/libfdt/libfdt_internal.h:36
Inline: True
Inline callers:
  - lib/fdt_ro.c:fdt_mem_rsv
```
```
In lib/fdt_rw.c (ffffffe0008b16ae)
Location: scripts/dtc/libfdt/libfdt_internal.h:36
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_del_mem_rsv
  - lib/fdt_rw.c:fdt_add_mem_rsv
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
