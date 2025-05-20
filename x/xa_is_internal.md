# Function: <code>xa_is_internal</code>

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
In kernel/memremap.c (ffffffff811fa4cd)
Location: include/linux/xarray.h:161
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/filemap.c (ffffffff811fd0aa)
Location: include/linux/xarray.h:161
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff81226acd)
Location: include/linux/xarray.h:161
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8125bbff)
Location: include/linux/xarray.h:161
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8129227b)
Location: include/linux/xarray.h:161
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812a91e0)
Location: include/linux/xarray.h:161
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/dax.c (ffffffff8130e826)
Location: include/linux/xarray.h:161
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a08767)
Location: include/linux/xarray.h:161
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a0ce3e)
Location: include/linux/xarray.h:161
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81a17fe7)
Location: include/linux/xarray.h:161
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_reserve
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
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
In mm/filemap.c (ffffffff81215528)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff81235f9b)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81276dbe)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812acccf)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memremap.c (ffffffff812c2b25)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In mm/memfd.c (ffffffff812c53e7)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81334f43)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a7810f)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next
```
```
In lib/radix-tree.c (ffffffff81a7c7a2)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81a87baa)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
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
In mm/filemap.c (ffffffff81222951)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff812441db)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128689a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812be57f)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff812d49e2)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In mm/memfd.c (ffffffff812d6dba)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81348b23)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81aaf9bf)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81ab3ad2)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81abee4a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
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
In mm/filemap.c (ffffffff8125007f)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/shmem.c (ffffffff8126e0f5)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812b8e37)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812f2348)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff8130a50e)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In mm/memfd.c (ffffffff8130beb1)
Location: include/linux/xarray.h:167
Inline: True
```
```
In fs/dax.c (ffffffff8138f360)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In fs/fuse/file.c (ffffffff81475ead)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff815e922f)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff815edb54)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_free_nodes
```
```
In lib/xarray.c (ffffffff815fb763)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_shrink
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
```
```
In drivers/base/memory.c (ffffffff817d9167)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
```
```
In net/core/devlink.c (ffffffff81a587c7)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065bcb)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8125a181)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/shmem.c (ffffffff8127c2f5)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/madvise.c (ffffffff812c1097)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812c4b23)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812fe800)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff81315ed3)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In mm/memfd.c (ffffffff81317d71)
Location: include/linux/xarray.h:167
Inline: True
```
```
In fs/io_uring.c (ffffffff8138a97c)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_add_task_file
```
```
In fs/dax.c (ffffffff813a09f9)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In fs/fuse/file.c (ffffffff81491404)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff8160e2df)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81612284)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_free_nodes
```
```
In lib/xarray.c (ffffffff816202d3)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_shrink
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
```
```
In drivers/base/memory.c (ffffffff817ed710)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
```
```
In net/core/devlink.c (ffffffff81a607ac)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8106617b)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81069933)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff8125feb2)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/shmem.c (ffffffff812814b5)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/madvise.c (ffffffff812c7eaa)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812cb7bc)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81305480)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff8131c0d6)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In mm/memfd.c (ffffffff8131df61)
Location: include/linux/xarray.h:167
Inline: True
```
```
In fs/io_uring.c (ffffffff8139265a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_add_task_file
```
```
In fs/dax.c (ffffffff813a7bca)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In fs/fuse/file.c (ffffffff8149655a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In block/bio.c (ffffffff815635ab)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In lib/iov_iter.c (ffffffff815accb3)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In lib/idr.c (ffffffff815f1a2f)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff815f59a1)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81603912)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
```
```
In drivers/base/memory.c (ffffffff817d1faa)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
```
```
In net/core/devlink.c (ffffffff81a427fe)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107029e)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81074013)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff8129c82e)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/shmem.c (ffffffff812bca98)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/madvise.c (ffffffff8130cc87)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff813108b3)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8134f2af)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff813693c2)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In mm/memfd.c (ffffffff8136b28c)
Location: include/linux/xarray.h:167
Inline: True
```
```
In fs/io_uring.c (ffffffff813e06a1)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_add_tctx_node
```
```
In fs/dax.c (ffffffff813f756c)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In fs/fuse/file.c (ffffffff814ef0d8)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff815c7f1e)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In lib/iov_iter.c (ffffffff81619903)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/idr.c (ffffffff8165ebae)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81662e07)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81672044)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
```
```
In drivers/base/memory.c (ffffffff8185d0bf)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
```
```
In drivers/vfio/vfio.c (ffffffff81922b61)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_assign_device_set
```
```
In net/core/devlink.c (ffffffff81afae9e)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e460)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082564)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff812f3abb)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813077d4)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff8130cd42)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81318b21)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813359fa)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/workingset.c (ffffffff81335ce7)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/madvise.c (ffffffff813761f3)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff8137b5dc)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff813bf6c7)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c5e39)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff813e7542)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In mm/memfd.c (ffffffff813e9252)
Location: include/linux/xarray.h:168
Inline: True
```
```
In fs/inode.c (ffffffff81417a31)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
```
```
In fs/dax.c (ffffffff8146a353)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In fs/fuse/file.c (ffffffff8157edf3)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff81672c47)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In io_uring/io_uring.c (ffffffff816c923d)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_add_tctx_node
  - io_uring/io_uring.c:io_provide_buffers
```
```
In lib/iov_iter.c (ffffffff816e6d19)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/idr.c (ffffffff8177844e)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff8177cf83)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff8178c7f8)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
```
```
In drivers/xen/grant-dma-ops.c (0)
Location: include/linux/xarray.h:168
Inline: True
```
```
In drivers/base/memory.c (ffffffff819a4354)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - drivers/base/memory.c:add_memory_block
```
```
In drivers/vfio/vfio.c (ffffffff81a77456)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_assign_device_set
```
```
In net/core/devlink.c (ffffffff81c7fa0c)
Location: include/linux/xarray.h:168
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810910fc)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094fe1)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff8135de41)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff81371944)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff813761f7)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8138c9e1)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813ac7ba)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/workingset.c (ffffffff813acae7)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/madvise.c (ffffffff813f3b40)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff813f8f5c)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff81441c23)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8144a99e)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff8146f1c2)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In mm/memfd.c (ffffffff81471202)
Location: include/linux/xarray.h:169
Inline: True
```
```
In fs/inode.c (ffffffff814a31d1)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
```
```
In fs/dax.c (ffffffff814fae00)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In fs/squashfs/file.c (ffffffff815ee0bd)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81624ac1)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff8172e707)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In io_uring/tctx.c (ffffffff8179bd36)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
```
In io_uring/kbuf.c (ffffffff8179faeb)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
```
```
In lib/iov_iter.c (ffffffff817d255b)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a35591)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac1f63)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/iommu.c (ffffffff81acf380)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
```
In drivers/base/memory.c (ffffffff81b16374)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/base/memory.c:add_memory_block
```
```
In net/core/devlink.c (ffffffff81e38a9d)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
```
```
In lib/idr.c (ffffffff820211de)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/maple_tree.c (ffffffff82030999)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_rev_awalk
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_destroy_rebalance
```
```
In lib/radix-tree.c (ffffffff82039833)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff82049ea8)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109403a)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097f64)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff8138cb69)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813a3a51)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff813a6224)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff813bf098)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813e0b5a)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/workingset.c (ffffffff813e0e95)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/madvise.c (ffffffff81427613)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8142bd2a)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff814775ca)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81480c5d)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff814a39a7)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In mm/memfd.c (ffffffff814a5753)
Location: include/linux/xarray.h:169
Inline: True
```
```
In fs/inode.c (ffffffff814d8321)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
```
```
In fs/dax.c (ffffffff81532253)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In fs/squashfs/file.c (ffffffff8162606c)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff8165ce8e)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff8176a9d7)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In io_uring/tctx.c (ffffffff817dce66)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
```
In io_uring/kbuf.c (ffffffff817e0bf4)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
```
```
In lib/scatterlist.c (ffffffff8180dde9)
Location: include/linux/xarray.h:169
Inline: True
```
```
In lib/iov_iter.c (ffffffff81810c5c)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a7efb3)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0ebfc)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/iommu.c (ffffffff81b1e010)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
```
In drivers/base/memory.c (ffffffff81b650e4)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/base/memory.c:add_memory_block
```
```
In net/devlink/leftover.c (ffffffff82039bed)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:__devlink_region_snapshot_create
```
```
In lib/idr.c (ffffffff820a1201)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/maple_tree.c (ffffffff820ac4b6)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_walk
  - lib/maple_tree.c:mas_rev_awalk
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_destroy_rebalance
```
```
In lib/radix-tree.c (ffffffff820b7b53)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff820c873a)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_descend
  - lib/xarray.c:xas_descend
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109b51a)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f504)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff813b66d6)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813cd573)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff813cfd91)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff813ea0e8)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff8140b42a)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/workingset.c (ffffffff8140b765)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/madvise.c (ffffffff81460cc3)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8146548a)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff814a6d3f)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814aec37)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff814d4842)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In mm/memfd.c (ffffffff814d6713)
Location: include/linux/xarray.h:169
Inline: True
```
```
In fs/inode.c (ffffffff8150ab01)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
```
```
In fs/libfs.c (ffffffff8152211f)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/libfs.c:offset_iterate_dir
```
```
In fs/dax.c (ffffffff81567143)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In fs/squashfs/file.c (ffffffff8165f1a9)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81696beb)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff817ace66)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In io_uring/tctx.c (ffffffff818211b5)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
```
In io_uring/kbuf.c (ffffffff818251aa)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
```
```
In lib/scatterlist.c (ffffffff81853ad4)
Location: include/linux/xarray.h:169
Inline: True
```
```
In lib/iov_iter.c (ffffffff8185708c)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81ad1523)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b665aa)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/iommu.c (ffffffff81b73fbd)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
```
In drivers/base/memory.c (ffffffff81bb8e73)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - drivers/base/memory.c:add_memory_block
```
```
In net/core/skbuff.c (ffffffff81ece86d)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
```
In net/core/datagram.c (ffffffff81eddbda)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In net/netlink/genetlink.c (ffffffff81f8fdfd)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_sk_priv_get
```
```
In net/devlink/region.c (ffffffff82110cd9)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:__devlink_region_snapshot_create
```
```
In lib/idr.c (ffffffff821791e1)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/maple_tree.c (ffffffff8218db8f)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mtree_dup
  - lib/maple_tree.c:__mt_dup
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_walk
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
```
```
In lib/radix-tree.c (ffffffff82192463)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff821a30ba)
Location: include/linux/xarray.h:169
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_descend
  - lib/xarray.c:xas_descend
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffff8000102affa0)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffff8000102d6560)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffff800010321080)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffff80001035ff40)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffff80001037c090)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffff800010408ffc)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffff800010d88d90)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffff800010d8d79c)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffff800010d9acb0)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
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
In mm/filemap.c (c04dce28)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (c04fe6bc)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c05399b4)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/memfd.c (c0566b00)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In lib/idr.c (c0e84204)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (c0e87d88)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (c0e96dd0)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In mm/filemap.c (c000000000364fa0)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (c000000000396678)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c0000000003f653c)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (c00000000044accc)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (c00000000046e30c)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In mm/memfd.c (c0000000004711ec)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (c0000000005152e0)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (c000000000ec9774)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (c000000000ecfde8)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (c000000000ee0344)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
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
In mm/filemap.c (ffffffe0001d547c)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffe0001f1c82)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffe00022250e)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/memfd.c (ffffffe000252516)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffe0002b33d4)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffe0008b3058)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffe0008b6a14)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffe0008c2c1a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In mm/filemap.c (ffffffff8121afa1)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff8123c82b)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127eeea)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812b6b5f)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff812ccfc2)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In mm/memfd.c (ffffffff812cf39a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81341103)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a4e80f)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81a52922)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81a5dc9a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
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
In mm/filemap.c (ffffffff8120e19b)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff8122f82b)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81270d1a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812a7d2f)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff812bde32)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In mm/memfd.c (ffffffff812c0024)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81331add)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a0b8ff)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81a0fa22)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81a1ad6a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
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
In mm/filemap.c (ffffffff81218d41)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff8123a5cb)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127cc8a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812b496f)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff812cadd2)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In mm/memfd.c (ffffffff812cd1aa)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff8133ebd3)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81ababff)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81abed12)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81aca08a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
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
In mm/filemap.c (ffffffff81227e37)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff81249cc0)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128c85a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812c5398)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff812dbb10)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In mm/memfd.c (ffffffff812ddf3c)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81351a95)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81ac704f)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:idr_get_next_ul
```
```
In lib/radix-tree.c (ffffffff81acb1d2)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81ad661a)
Location: include/linux/xarray.h:167
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
```
</details>
</li>
</ul>

## Differences
