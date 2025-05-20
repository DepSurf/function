# Function: <code>pud_alloc_track</code>

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
In mm/memory.c (ffffffff8129331a)
Location: include/linux/mm.h:2132
Inline: True
Inline callers:
  - mm/memory.c:apply_to_p4d_range
```
```
In mm/vmalloc.c (ffffffff812a8031)
Location: include/linux/mm.h:2132
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_p4d_range
```
```
In lib/ioremap.c (ffffffff815e9920)
Location: include/linux/mm.h:2132
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
In mm/memory.c (ffffffff8129dc96)
Location: mm/pgalloc-track.h:19
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
```
```
In mm/vmalloc.c (ffffffff812b3101)
Location: mm/pgalloc-track.h:19
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b8411)
Location: mm/pgalloc-track.h:19
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
In mm/memory.c (ffffffff812a3399)
Location: mm/pgalloc-track.h:19
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/vmalloc.c (ffffffff812b7bc9)
Location: mm/pgalloc-track.h:19
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
In mm/memory.c (ffffffff812e4671)
Location: mm/pgalloc-track.h:19
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/vmalloc.c (ffffffff812fa2f9)
Location: mm/pgalloc-track.h:19
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
In mm/memory.c (ffffffff81345f52)
Location: mm/pgalloc-track.h:19
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/vmalloc.c (ffffffff8136160f)
Location: mm/pgalloc-track.h:19
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
In mm/memory.c (ffffffff813be325)
Location: mm/pgalloc-track.h:19
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/vmalloc.c (ffffffff813dcf9c)
Location: mm/pgalloc-track.h:19
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
In mm/memory.c (ffffffff813f2f85)
Location: mm/pgalloc-track.h:19
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/vmalloc.c (ffffffff814117ec)
Location: mm/pgalloc-track.h:19
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
In mm/memory.c (ffffffff8141dc75)
Location: mm/pgalloc-track.h:19
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/vmalloc.c (ffffffff8143dff9)
Location: mm/pgalloc-track.h:19
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
