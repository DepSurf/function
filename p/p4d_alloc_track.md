# Function: <code>p4d_alloc_track</code>

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
In mm/memory.c (ffffffff81293270)
Location: include/linux/mm.h:2118
Inline: True
Inline callers:
  - mm/memory.c:apply_to_p4d_range
```
```
In mm/vmalloc.c (ffffffff812a7f65)
Location: include/linux/mm.h:2118
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_p4d_range
```
```
In lib/ioremap.c (ffffffff815e9d35)
Location: include/linux/mm.h:2118
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In mm/memory.c (ffffffff8129dbda)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
```
```
In mm/vmalloc.c (ffffffff812b303e)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b8282)
Location: mm/pgalloc-track.h:6
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
In mm/memory.c (ffffffff812a3693)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
```
```
In mm/vmalloc.c (ffffffff812b85c8)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
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
In mm/memory.c (ffffffff812e4968)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
```
```
In mm/vmalloc.c (ffffffff812fad41)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
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
In mm/memory.c (ffffffff81346260)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
```
```
In mm/vmalloc.c (ffffffff81362245)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
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
In mm/memory.c (ffffffff813be618)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
```
```
In mm/vmalloc.c (ffffffff813ddbe5)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
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
In mm/memory.c (ffffffff813f326f)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
```
```
In mm/vmalloc.c (ffffffff81412445)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
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
In mm/memory.c (ffffffff8141df5f)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
```
```
In mm/vmalloc.c (ffffffff8143eca5)
Location: mm/pgalloc-track.h:6
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
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
