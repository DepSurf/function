# Function: <code>folio_test_active</code>

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
In mm/filemap.c (ffffffff812f2934)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813032cb)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8130f4e5)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/compaction.c (ffffffff81330c36)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8134adec)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/slub.c (ffffffff813a8dfb)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff8135ad74)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff8136f711)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff8137e79e)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813a7a86)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c3a0f)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/slub.c (ffffffff81429ef8)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff8138c794)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813a1831)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:folio_deactivate
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813afe85)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813db00a)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813f8cc4)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/slub.c (ffffffff8145f2fb)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff813b62f4)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813cb4ba)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:folio_deactivate
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813d9372)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff81405191)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8142487f)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/slub.c (ffffffff8145a46b)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/madvise.c (ffffffff81461ccb)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
