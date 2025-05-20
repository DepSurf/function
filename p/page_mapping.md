# Function: <code>page_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811ac0e0)
Location: mm/util.c:331
Inline: False
Direct callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_replace_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:mark_buffer_dirty
```
**Symbols:**

```
ffffffff811ac0e0-ffffffff811ac129: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c47e0)
Location: mm/util.c:384
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:delete_from_page_cache
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/compaction.c:isolate_migratepages_block
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff811c47e0-ffffffff811c484b: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d48d0)
Location: mm/util.c:387
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:delete_from_page_cache
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff811d48d0-ffffffff811d4956: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd650)
Location: mm/util.c:471
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:delete_from_page_cache
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff811dd650-ffffffff811dd6f1: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f30d0)
Location: mm/util.c:471
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff811f30d0-ffffffff811f3175: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214110)
Location: mm/util.c:497
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff81214110-ffffffff812141b5: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81226fe0)
Location: mm/util.c:500
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81226fe0-ffffffff81227081: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81236d90)
Location: mm/util.c:543
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81236d90-ffffffff81236e31: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81244f50)
Location: mm/util.c:648
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81244f50-ffffffff81244ff1: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272c00)
Location: mm/util.c:676
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:page_endio
  - mm/filemap.c:delete_from_page_cache
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_mkclean
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81272c00-ffffffff81272ca1: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d2b0)
Location: mm/util.c:689
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/filemap.c:delete_from_page_cache
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:__isolate_lru_page_prepare
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_mkclean
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff8127d2b0-ffffffff8127d351: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282440)
Location: mm/util.c:689
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/filemap.c:delete_from_page_cache
  - mm/page-writeback.c:wait_on_page_writeback_killable
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_undo_range
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/mlock.c:__munlock_pagevec
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_mkclean
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_clean
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81282440-ffffffff812824e9: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c04b0)
Location: mm/util.c:710
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/filemap.c:delete_from_page_cache
  - mm/page-writeback.c:wait_on_page_writeback_killable
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_undo_range
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/mlock.c:__munlock_pagevec
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_mkclean
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_clean
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
```
**Symbols:**

```
ffffffff812c04b0-ffffffff812c0555: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8130105b)
Location: mm/folio-compat.c:12
Inline: True
Inline callers:
  - mm/folio-compat.c:__set_page_dirty_nobuffers
Direct callers:
  - mm/filemap.c:page_endio
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/shmem.c:shmem_replace_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:PageMovable
  - mm/debug.c:__dump_page
  - mm/memory.c:__do_fault
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/migrate_device.c:migrate_vma_pages
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_clean
  - mm/memory-failure.c:hwpoison_filter
  - mm/zsmalloc.c:zs_page_migrate
  - fs/buffer.c:mark_buffer_dirty
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
```
**Symbols:**

```
ffffffff81300e30-ffffffff81300e87: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b8ab)
Location: mm/folio-compat.c:12
Inline: True
Inline callers:
  - mm/folio-compat.c:__set_page_dirty_nobuffers
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:__do_fault
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_device_unmap
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_clean
  - mm/memory-failure.c:hwpoison_filter
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/buffer.c:mark_buffer_dirty
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
```
**Symbols:**

```
ffffffff8136b5d0-ffffffff8136b627: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139dadc)
Location: mm/folio-compat.c:13
Inline: True
Inline callers:
  - mm/folio-compat.c:__set_page_dirty_nobuffers
Direct callers:
  - mm/debug.c:__dump_page
  - mm/memory.c:__do_fault
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_device_unmap
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_clean
  - mm/memory-failure.c:hwpoison_filter
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
```
**Symbols:**

```
ffffffff8139d7a0-ffffffff8139d804: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7848)
Location: mm/folio-compat.c:13
Inline: True
Inline callers:
  - mm/folio-compat.c:__set_page_dirty_nobuffers
Direct callers:
  - mm/debug.c:__dump_page
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_device_unmap
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:hwpoison_filter
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/crypto/inline_crypt.c:bh_get_inode_and_lblk_num
```
**Symbols:**

```
ffffffff813c7690-ffffffff813c76f1: page_mapping (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d7f90)
Location: mm/util.c:648
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffff8000102d7f90-ffff8000102d8048: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff404)
Location: mm/util.c:648
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
c04ff404-c04ff4a8: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000397aa0)
Location: mm/util.c:648
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:page_endio
  - mm/filemap.c:delete_from_page_cache
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_mkclean
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
c000000000397aa0-c000000000397b98: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f286c)
Location: mm/util.c:648
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffe0001f286c-ffffffe0001f291a: page_mapping (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d5a0)
Location: mm/util.c:648
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff8123d5a0-ffffffff8123d641: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812305a0)
Location: mm/util.c:648
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812305a0-ffffffff81230641: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b340)
Location: mm/util.c:648
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff8123b340-ffffffff8123b3e1: page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct address_space *page_mapping(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124aa50)
Location: mm/util.c:648
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:page_evictable
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/util.c:page_mapping_file
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff8124aa50-ffffffff8124aaf1: page_mapping (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
