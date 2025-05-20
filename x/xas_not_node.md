# Function: <code>xas_not_node</code>

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
In mm/filemap.c (ffffffff811fd06f)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff8120ea99)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81226a90)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8125be74)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812825ca)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812920f2)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812a8f45)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812e15f6)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8130ee10)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a0872a)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a178ef)
Location: include/linux/xarray.h:1274
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (ffffffff812154ec)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff8121e699)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81235f55)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81277037)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8129e584)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812acc92)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812c5549)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812ffd79)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81334afb)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a780d4)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a874bd)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (ffffffff81222915)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff8122c139)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81244195)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81286b17)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ade28)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812be543)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812d6f57)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8131257f)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813486d3)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81aaf984)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81abe75d)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (ffffffff81250001)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/page-writeback.c (ffffffff812591f9)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8126e09e)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812b9097)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812e495e)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812f22dd)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8130c088)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8134bd65)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8138e0bf)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In fs/fuse/file.c (ffffffff81475dfc)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff815e91ea)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff815facea)
Location: include/linux/xarray.h:1438
Inline: True
Inline callers:
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065b82)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8125a255)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/page-writeback.c (ffffffff812637e9)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8127c29e)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/madvise.c (ffffffff812c104f)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812c4add)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ef358)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812fe794)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff81317f48)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81358c7a)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8139f82c)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff8149132f)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff8160e29a)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff8161f4ea)
Location: include/linux/xarray.h:1440
Inline: True
Inline callers:
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066132)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8125fe59)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/page-writeback.c (ffffffff81268469)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8128145e)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/madvise.c (ffffffff812c7e62)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812cb776)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812f5fc8)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff81305414)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8131e138)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8135f7da)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813a659c)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff81496482)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/iov_iter.c (ffffffff815acc47)
Location: include/linux/xarray.h:1442
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
In lib/idr.c (ffffffff815f19ea)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81602e0e)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070254)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8129c7c9)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/page-writeback.c (ffffffff812a629d)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff812bca3d)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/madvise.c (ffffffff8130cc2c)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff8131086b)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff813405ac)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8134f264)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8136b4ec)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813ae141)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff813f600c)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff814eeff0)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff81619886)
Location: include/linux/xarray.h:1442
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
In lib/idr.c (ffffffff8165eb65)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff816712b6)
Location: include/linux/xarray.h:1442
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e416)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff812f3a65)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff812fc78e)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81318acd)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff81334c02)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff8137618c)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff8137b594)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff813c5dee)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff813e9550)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81432432)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff81469bd8)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff8157eda6)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff816e6cb3)
Location: include/linux/xarray.h:1445
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
In lib/idr.c (ffffffff81778401)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff8178ad23)
Location: include/linux/xarray.h:1445
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810910b1)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8135ddeb)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81366ac1)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8138c98d)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff813ab9f2)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff813f3ad9)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff813f8f14)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8144a953)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff81471532)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814c04e1)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff814fa328)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/squashfs/file.c (ffffffff815ee068)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81624a74)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff817d25d9)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/idr.c (ffffffff82021191)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff82048293)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093ff1)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8138cb1c)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81399111)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff813bf044)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff813dfd82)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff814275af)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8142bce4)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81480c12)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814a5a86)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814f58d1)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff8152f93d)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/squashfs/file.c (ffffffff81626011)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff8165ce35)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/scatterlist.c (ffffffff8180dd9d)
Location: include/linux/xarray.h:1460
Inline: True
```
```
In lib/iov_iter.c (ffffffff81810cd9)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In lib/idr.c (ffffffff820a11b1)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff820c6a34)
Location: include/linux/xarray.h:1460
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109b4d1)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff813b668b)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff813c2f11)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff813ea094)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff8140a4f2)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff81460c77)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff81465444)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff814969a7)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/khugepaged.c (ffffffff814aebec)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814d6a36)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/libfs.c (ffffffff815220b3)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - fs/libfs.c:offset_iterate_dir
```
```
In fs/fs-writeback.c (ffffffff81529fde)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff8156481d)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/squashfs/file.c (ffffffff8165f14e)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81696b92)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/scatterlist.c (ffffffff81853a87)
Location: include/linux/xarray.h:1478
Inline: True
```
```
In lib/iov_iter.c (ffffffff81857106)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In net/core/skbuff.c (ffffffff81ece80d)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
```
In net/core/datagram.c (ffffffff81eddb84)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In lib/idr.c (ffffffff82179191)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff821a13b4)
Location: include/linux/xarray.h:1478
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (ffff8000102aff14)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffff8000102ba88c)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffff8000102d63c0)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffff80001032136c)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffff80001034fe14)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffff80001035fecc)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffff80001037bef4)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffff8000103c7634)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffff8000104096a0)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffff800010d88d44)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffff800010d99a0c)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (c04dcd9c)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (c04e6bbc)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (c04fe668)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c0539c38)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (0)
Location: include/linux/xarray.h:1403
Inline: True
```
```
In mm/memfd.c (c0566c90)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c05a44ec)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/idr.c (c0e841b0)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (c0e9636c)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (c000000000364f34)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (c000000000373444)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (c000000000396620)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c0000000003f68cc)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (c0000000004332b8)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (c00000000044ac60)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (c00000000047140c)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c0000000004c9098)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (c000000000514cc0)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (c000000000ec971c)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (c000000000edf90c)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (ffffffe0001d5446)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffe0001ddcba)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffe0001f1c46)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffe000222738)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (0)
Location: include/linux/xarray.h:1403
Inline: True
```
```
In mm/memfd.c (ffffffe0002526b4)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffe00028629a)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffe0002b4302)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffe0008b3020)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffe0008c3236)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (ffffffff8121af65)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81224789)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8123c7e5)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127f167)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a6408)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812b6b23)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812cf537)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130ab5f)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81340cb3)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a4e7d4)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a5d5ad)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (ffffffff8120e15f)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81217939)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8122f7e5)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81270f87)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81297eb8)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812a7cf3)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812c01b5)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812fb77f)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81331697)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a0b8c4)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a1a67d)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (ffffffff81218d05)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81222529)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8123a585)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127cf07)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a4218)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812b4933)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812cd347)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130894f)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8133e783)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81ababc4)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81ac999d)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
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
In mm/filemap.c (ffffffff81227dfb)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81231919)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81249c7a)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128cac7)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812b3988)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812c535c)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812de0bf)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8131a5cf)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8135160c)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81ac7014)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81ad5ee2)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
```
</details>
</li>
</ul>

## Differences
