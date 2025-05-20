# Function: <code>fdt_get_property_w</code>

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
In lib/fdt_rw.c (ffff80001143fe7c)
Location: scripts/dtc/libfdt/libfdt.h:689
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
```
```
In lib/fdt_wip.c (ffff800011440bc8)
Location: scripts/dtc/libfdt/libfdt.h:689
Inline: True
Inline callers:
  - lib/fdt_wip.c:fdt_nop_property
  - lib/fdt_wip.c:fdt_nop_property
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
In lib/fdt_rw.c (c0e827c8)
Location: scripts/dtc/libfdt/libfdt.h:689
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
```
```
In lib/fdt_wip.c (c0e82d70)
Location: scripts/dtc/libfdt/libfdt.h:689
Inline: True
Inline callers:
  - lib/fdt_wip.c:fdt_nop_property
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
In lib/fdt_rw.c (c000000000ec7ac0)
Location: scripts/dtc/libfdt/libfdt.h:689
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
```
```
In lib/fdt_wip.c (c000000000ec8394)
Location: scripts/dtc/libfdt/libfdt.h:689
Inline: True
Inline callers:
  - lib/fdt_wip.c:fdt_nop_property
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
In lib/fdt_rw.c (ffffffe0008b1a2a)
Location: scripts/dtc/libfdt/libfdt.h:689
Inline: True
Inline callers:
  - lib/fdt_rw.c:fdt_delprop
  - lib/fdt_rw.c:fdt_appendprop
```
```
In lib/fdt_wip.c (ffffffe0008b208a)
Location: scripts/dtc/libfdt/libfdt.h:689
Inline: True
Inline callers:
  - lib/fdt_wip.c:fdt_nop_property
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
