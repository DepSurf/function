# Function: <code>folio_mapping</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct address_space *folio_mapping(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d530)
Location: mm/util.c:795
Inline: True
Direct callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_mark_dirty
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_undo_range
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:folio_mkclean
  - mm/migrate.c:move_to_new_folio
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff8131d530-ffffffff8131d5ad: folio_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct address_space *folio_mapping(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813911e0)
Location: mm/util.c:741
Inline: True
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_mark_dirty
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/swap.c:lru_add_fn
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_undo_range
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:folio_mkclean
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:move_to_new_folio
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff813911e0-ffffffff81391252: folio_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct address_space *folio_mapping(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3ba0)
Location: mm/util.c:764
Inline: True
Direct callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_mark_dirty
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/swap.c:lru_add_fn
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_undo_range
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:folio_mkclean
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:move_to_new_folio
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff813c3ba0-ffffffff813c3c12: folio_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct address_space *folio_mapping(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ee750)
Location: mm/util.c:771
Inline: True
Direct callers:
  - mm/filemap.c:filemap_release_folio
  - mm/page-writeback.c:folio_wait_stable
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:folio_mark_dirty
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/swap.c:lru_add_fn
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_undo_range
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:folio_mkclean
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:move_to_new_folio
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_clean
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff813ee750-ffffffff813ee7c2: folio_mapping (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
