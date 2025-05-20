# Function: <code>folio_test_reclaim</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f01c5)
Location: include/linux/page-flags.h:544
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff812fc66a)
Location: include/linux/page-flags.h:544
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/vmscan.c (ffffffff8130e3b5)
Location: include/linux/page-flags.h:544
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/filemap.c (ffffffff8135b565)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff8136698a)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/swap.c (ffffffff8136dbd1)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff81381133)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/mlock.c (ffffffff813c25b0)
Location: include/linux/page-flags.h:523
Inline: True
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
In mm/filemap.c (ffffffff8138d3c5)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff81398ffa)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/swap.c (ffffffff8139fe0c)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813b24e5)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/mlock.c (ffffffff813f6efe)
Location: include/linux/page-flags.h:516
Inline: True
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
In mm/filemap.c (ffffffff813b6f55)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff813c2dfa)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/swap.c (ffffffff813c9a6f)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813dba93)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/mlock.c (ffffffff814230dc)
Location: include/linux/page-flags.h:518
Inline: True
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
