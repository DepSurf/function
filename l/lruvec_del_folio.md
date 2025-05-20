# Function: <code>lruvec_del_folio</code>

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
In mm/swap.c (ffffffff8130557b)
Location: include/linux/mm_inline.h:132
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__folio_activate
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8130f4b2)
Location: include/linux/mm_inline.h:132
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/compaction.c (ffffffff81330c10)
Location: include/linux/mm_inline.h:132
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8134acb6)
Location: include/linux/mm_inline.h:132
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
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
In mm/swap.c (ffffffff8136f6e6)
Location: include/linux/mm_inline.h:347
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8137e78b)
Location: include/linux/mm_inline.h:347
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/compaction.c (ffffffff813a7a73)
Location: include/linux/mm_inline.h:347
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c38ab)
Location: include/linux/mm_inline.h:347
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
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
In mm/swap.c (ffffffff813a1806)
Location: include/linux/mm_inline.h:341
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813afe72)
Location: include/linux/mm_inline.h:341
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/compaction.c (ffffffff813dafe3)
Location: include/linux/mm_inline.h:341
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813f8b93)
Location: include/linux/mm_inline.h:341
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
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
In mm/swap.c (ffffffff813cb487)
Location: include/linux/mm_inline.h:347
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813d935f)
Location: include/linux/mm_inline.h:347
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/compaction.c (ffffffff81405169)
Location: include/linux/mm_inline.h:347
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81424750)
Location: include/linux/mm_inline.h:347
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
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
