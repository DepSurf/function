# Function: <code>xa_is_value</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fcfda)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffffffff812128c2)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffffffff81215bbf)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff81216064)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812200ff)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (ffffffff812454f1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff812593c7)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/khugepaged.c (ffffffff812920a1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8129464a)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (ffffffff812a8ec5)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/dax.c (ffffffff8130ec9f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff81330438)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/idr.c (ffffffff81a08717)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a0d788)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a1855b)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121545a)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffffffff812222b4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffffffff812255af)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff81225a64)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8122f8a6)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (ffffffff81257572)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff81274bfc)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/khugepaged.c (ffffffff812acaf8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812b0880)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (ffffffff812c54cb)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff8133498e)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff81358268)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/idr.c (ffffffff81a780c1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a7c9d1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a8817e)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812227eb)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffffffff8122fd64)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffffffff8123341f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff812338b4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123da76)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (ffffffff81265ac2)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8128428a)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812be386)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c22e0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (ffffffff812d6e9f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81348561)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff81370498)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/idr.c (ffffffff81aaf971)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81ab3d01)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81abf41e)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124ff19)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/readahead.c (ffffffff8125cf00)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_readahead_unbounded
```
```
In mm/swap.c (ffffffff81260a0f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff81260fd9)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8126c1a6)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (ffffffff81295dfe)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff812b61c1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/khugepaged.c (ffffffff812f2256)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812f9239)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (ffffffff8130bfe8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff8138da55)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff813b8363)
Location: include/linux/xarray.h:77
Inline: True
```
```
In lib/idr.c (ffffffff815e91d5)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff815ee20a)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff815fb8fe)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_expand
```
```
In net/core/devlink.c (ffffffff81a51347)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_snapshot_id_decrement
  - net/core/devlink.c:__devlink_snapshot_id_increment
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
In mm/filemap.c (ffffffff8125a123)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/readahead.c (ffffffff81267262)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap.c (ffffffff8126ad5f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff8126b3d9)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81276bf6)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/madvise.c (ffffffff812c1000)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812c4ee1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/khugepaged.c (ffffffff812fe706)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff81317ea8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff8139f4c5)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff813c9ab7)
Location: include/linux/xarray.h:77
Inline: True
```
```
In lib/idr.c (ffffffff8160e285)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff8161293a)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff8161fa06)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_expand
```
```
In net/core/devlink.c (ffffffff81a57457)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_snapshot_id_decrement
  - net/core/devlink.c:__devlink_snapshot_id_increment
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
In mm/filemap.c (ffffffff8125e0ee)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/readahead.c (ffffffff8126b9b8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap.c (ffffffff8126ff0f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff8127044c)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8127ed93)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/madvise.c (ffffffff812c7e13)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812cbb88)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/huge_memory.c (ffffffff813001cb)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
```
```
In mm/khugepaged.c (ffffffff81305386)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8131e098)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff813a6235)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff813d0ba4)
Location: include/linux/xarray.h:77
Inline: True
```
```
In lib/iov_iter.c (ffffffff815acb3c)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/idr.c (ffffffff815f19d5)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff815f5ec8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81603186)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
```
```
In net/core/devlink.c (ffffffff81a42217)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
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
In mm/filemap.c (ffffffff8129a816)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/readahead.c (ffffffff812a8688)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap.c (ffffffff812ad2ff)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff812ae0e2)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812bd813)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/madvise.c (ffffffff8130cbd9)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff81310cac)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/huge_memory.c (ffffffff81349e1b)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
```
```
In mm/khugepaged.c (ffffffff8134f1d6)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8136b494)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff813f5ca5)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff81421442)
Location: include/linux/xarray.h:77
Inline: True
```
```
In lib/iov_iter.c (ffffffff816197a9)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/idr.c (ffffffff8165eb4c)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff816633c1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81671660)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
```
```
In net/core/devlink.c (ffffffff81afa8d7)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
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
In mm/filemap.c (ffffffff812f1476)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/folio-compat.c (ffffffff81300a26)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff8130195d)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap.c (ffffffff81307391)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_remove_exceptionals
```
```
In mm/truncate.c (ffffffff81307612)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8130cd56)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8131959a)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/workingset.c (ffffffff81335cfb)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/madvise.c (ffffffff81376120)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff8137bade)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/huge_memory.c (ffffffff813c06ef)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
```
```
In mm/khugepaged.c (ffffffff813c5dd0)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff813e9501)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/inode.c (0)
Location: include/linux/xarray.h:78
Inline: True
```
```
In fs/dax.c (ffffffff814694e1)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/iov_iter.c (ffffffff816e6bb3)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/idr.c (ffffffff817783e8)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff8177d451)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff8178c0d2)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
```
```
In net/core/devlink.c (ffffffff81c7f407)
Location: include/linux/xarray.h:78
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
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
In mm/filemap.c (ffffffff8135be16)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/folio-compat.c (ffffffff8136b2fc)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff8136c031)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap.c (ffffffff81371211)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_remove_exceptionals
```
```
In mm/truncate.c (ffffffff8137172c)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8137620b)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8138d50e)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/workingset.c (ffffffff813acafb)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/madvise.c (ffffffff813f3a6d)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff813f9462)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/huge_memory.c (ffffffff814431bb)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
```
```
In mm/khugepaged.c (ffffffff8144a870)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814714e2)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/inode.c (0)
Location: include/linux/xarray.h:79
Inline: True
```
```
In fs/dax.c (ffffffff814f9f81)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/iov_iter.c (ffffffff817d651c)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In net/core/devlink.c (ffffffff81e382cf)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
```
In lib/idr.c (ffffffff82021178)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff8203a721)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff82048687)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
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
In mm/filemap.c (ffffffff8138ca8d)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffffffff8139e29c)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap.c (ffffffff813a33b3)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_remove_exceptionals
```
```
In mm/truncate.c (ffffffff813a383c)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813a6238)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff813bfed5)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/workingset.c (ffffffff813e0ea9)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/madvise.c (ffffffff81427530)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8142c1bf)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/khugepaged.c (ffffffff81480ab1)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814a5a37)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/inode.c (0)
Location: include/linux/xarray.h:79
Inline: True
```
```
In fs/dax.c (ffffffff815313fe)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/scatterlist.c (ffffffff8180dcd3)
Location: include/linux/xarray.h:79
Inline: True
```
```
In lib/iov_iter.c (ffffffff81813ba7)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In net/devlink/leftover.c (ffffffff820391ef)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - net/devlink/leftover.c:__devlink_region_snapshot_create
  - net/devlink/leftover.c:__devlink_snapshot_id_decrement
```
```
In lib/idr.c (ffffffff820a1198)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff820b8b91)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff820c6e8c)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
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
In mm/filemap.c (ffffffff813b6639)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffffffff813c7f3c)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap.c (ffffffff813cd023)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_remove_exceptionals
```
```
In mm/truncate.c (ffffffff813cd454)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813cfda5)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff813eacc3)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/workingset.c (ffffffff8140b779)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/madvise.c (ffffffff81460c14)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8146591f)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/khugepaged.c (ffffffff814aea91)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814d69e7)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/inode.c (0)
Location: include/linux/xarray.h:79
Inline: True
```
```
In fs/dax.c (ffffffff815662de)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/scatterlist.c (ffffffff8185397d)
Location: include/linux/xarray.h:79
Inline: True
```
```
In lib/iov_iter.c (ffffffff818587e4)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In net/core/skbuff.c (ffffffff81ece6cd)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
```
In net/core/datagram.c (ffffffff81edda64)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In net/devlink/region.c (ffffffff8210ff8e)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - net/devlink/region.c:__devlink_region_snapshot_create
  - net/devlink/region.c:__devlink_snapshot_id_decrement
```
```
In lib/idr.c (ffffffff82179178)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff821934a1)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff821a180c)
Location: include/linux/xarray.h:79
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
```
</details>
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
In mm/filemap.c (ffff8000102afdf0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffff8000102bf598)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffff8000102c3624)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffff8000102c3d18)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffff8000102cf4f0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (ffff8000102fccb4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffff80001031e6b8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
```
```
In mm/khugepaged.c (ffff80001035fcc8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff800010363dc4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (ffff80001037be30)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffff80001040950c)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffff80001043a140)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/idr.c (ffff800010d88d30)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffff800010d8dff4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffff800010d9a688)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
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
In mm/filemap.c (c04dcc3c)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (c04eb06c)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (c04ee410)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (c04ee930)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c04f8d28)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (c051c3cc)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (c0538628)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/memcontrol.c (c05560e4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (c0566be4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (c0600c74)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In lib/idr.c (c0e84198)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (c0e89050)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (c0e973b4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
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
In mm/filemap.c (c000000000364db0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (c0000000003782b8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (c00000000037daa0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (c00000000037e1f0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c00000000038cea0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (c0000000003c7c24)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (c0000000003f28c0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/khugepaged.c (c00000000044aa5c)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c000000000451004)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (c000000000471320)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (c000000000514b50)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (c00000000054e0c4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/idr.c (c000000000ec9700)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (c000000000ed0a50)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (c000000000ee0d14)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffe0001d5350)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffffffe0001e16e0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffffffe0001e45a8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffe0001e49a8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffe0001ecda8)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (ffffffe00020b914)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffe000221592)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/memcontrol.c (ffffffe000241c92)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (ffffffe0002525e6)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffe0002b4176)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffe0002d343e)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/idr.c (ffffffe0008b3008)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffe0008b6c6e)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffe0008c2c8c)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121ae3b)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffffffff812283b4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffffffff8122ba6f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff8122bf04)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812360c6)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (ffffffff8125e112)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8127c8da)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812b6966)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812ba8c0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (ffffffff812cf47f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81340b41)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff81368a78)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/idr.c (ffffffff81a4e7c1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a52b51)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a5e26e)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120e03b)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffffffff8121b4f4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffffffff8121eb5f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff8121efe4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81229126)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (ffffffff812505a2)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8126e78a)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812a7b36)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812aba7e)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (ffffffff812c0103)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81331531)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff81359d2a)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/idr.c (ffffffff81a0b8b1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a0fc51)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a1b33e)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218bdb)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffffffff81226154)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffffffff8122980f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff81229ca4)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81233e66)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (ffffffff8125beb2)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8127a67a)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812b4776)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812b86d0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (ffffffff812cd28f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff8133e611)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff81366548)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/idr.c (ffffffff81ababb1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81abef41)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81aca65e)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81227cd0)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/readahead.c (ffffffff81235454)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffffffff81238c1f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff8123909f)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81243436)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/mincore.c (ffffffff8126b8a2)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8128a25a)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/khugepaged.c (ffffffff812c514c)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c8d10)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memfd.c (ffffffff812de015)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff813514b1)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/proc/task_mmu.c (ffffffff81379888)
Location: include/linux/xarray.h:77
Inline: True
```
```
In lib/idr.c (ffffffff81ac7001)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81acb411)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81ad6c2e)
Location: include/linux/xarray.h:77
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>

## Differences
