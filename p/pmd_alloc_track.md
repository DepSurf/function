# Function: <code>pmd_alloc_track</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812933af)
Location: include/linux/mm.h:2151
Inline: True
Inline callers:
  - mm/memory.c:apply_to_p4d_range
```
```
In mm/vmalloc.c (ffffffff812a80a1)
Location: include/linux/mm.h:2151
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_p4d_range
```
```
In lib/ioremap.c (ffffffff815e9a70)
Location: include/linux/mm.h:2151
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129dd24)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
```
```
In mm/vmalloc.c (ffffffff812b3171)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b853f)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a3269)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/vmalloc.c (ffffffff812b7c75)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e4543)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/vmalloc.c (ffffffff812fa3a5)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81345df9)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/vmalloc.c (ffffffff8136168e)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813be1ad)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/vmalloc.c (ffffffff813dd025)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2dfd)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/vmalloc.c (ffffffff8141188a)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141daed)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/vmalloc.c (ffffffff8143e084)
Location: mm/pgalloc-track.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
