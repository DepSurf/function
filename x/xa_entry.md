# Function: <code>xa_entry</code>

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
In mm/filemap.c (ffffffff811fd09f)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff8120eb54)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81226ac2)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8125be9a)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812825ec)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff81292270)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812a91d5)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812e1858)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8130ee81)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a0875c)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a17997)
Location: include/linux/xarray.h:1000
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8121551d)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff8121e754)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81235f90)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127705d)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8129e5a6)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812accc4)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812c55ad)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812ffdd1)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81334b64)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a78104)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a874ee)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff81222833)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff8122c1f4)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff812441d0)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81286b3d)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ade4a)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812be574)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812d6fb3)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813125d7)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8134873c)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81aaf9b4)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81abe78e)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8124ff61)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/page-writeback.c (ffffffff812592b4)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8126e0ec)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812b90bd)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812e4980)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812f233f)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8130c13a)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8134bdbd)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8138e148)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In fs/fuse/file.c (ffffffff81475ea4)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff815e9226)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff815fb246)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065bc2)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8125a175)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/page-writeback.c (ffffffff812638a4)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8127c2ec)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/madvise.c (ffffffff812c108e)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812c4b1a)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ef37a)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812fe7f7)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff81317ffa)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81358fe7)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8139f8b5)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff814913fb)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff8160e2d6)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff8161fdaf)
Location: include/linux/xarray.h:1176
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066172)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8125fea9)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/page-writeback.c (ffffffff81268524)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff812814ac)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/madvise.c (ffffffff812c7ea1)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812cb7b3)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812f5fea)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff81305477)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8131e1ea)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8135fb47)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813a6668)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff81496551)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/iov_iter.c (ffffffff815accaa)
Location: include/linux/xarray.h:1178
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
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In lib/idr.c (ffffffff815f1a26)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81602e53)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070287)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8129c817)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/page-writeback.c (ffffffff812a6359)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff812bca81)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/madvise.c (ffffffff8130cc70)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff813108a0)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff813405ce)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8134f298)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8136b5a6)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813ae3e0)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff813f60d8)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff814ef0c1)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff816198ec)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In lib/idr.c (ffffffff8165eb9b)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff816712f4)
Location: include/linux/xarray.h:1178
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e449)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff812f3aa4)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff812fc7e2)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81318b0a)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff81334c38)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff813761dc)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff8137b5c9)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff813c5e22)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff813e9619)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81432701)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff81469caf)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff8157eddc)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff816e6d02)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In lib/idr.c (ffffffff81778437)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff8178ad61)
Location: include/linux/xarray.h:1179
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_start
  - lib/xarray.c:xas_start
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810910e5)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8135de2a)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81366b13)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8138c9ca)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff813aba28)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff813f3b29)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff813f8f49)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8144a987)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814715f7)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814c07ef)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff814fa3a7)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/squashfs/file.c (ffffffff815ee0a6)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81624aaa)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff817d24f5)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/idr.c (ffffffff820211c7)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff820482d1)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81094023)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8138cb52)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81399167)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff813bf081)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff813dfdb9)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff814275fc)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8142bd17)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81480c46)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814a5adc)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814f5927)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff8152f974)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/squashfs/file.c (ffffffff81626055)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff8165ce77)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/scatterlist.c (ffffffff8180ddd2)
Location: include/linux/xarray.h:1194
Inline: True
```
```
In lib/iov_iter.c (ffffffff81810bf6)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In lib/idr.c (ffffffff820a11ea)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff820c6a81)
Location: include/linux/xarray.h:1194
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109b503)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff813b66bf)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff813c2f67)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff813ea0d1)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff8140a529)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff81460cac)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff81465477)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81496979)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/khugepaged.c (ffffffff814aec20)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814d6a8c)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/libfs.c (ffffffff81522108)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - fs/libfs.c:offset_iterate_dir
```
```
In fs/fs-writeback.c (ffffffff8152a034)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff81564854)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/squashfs/file.c (ffffffff8165f192)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81696bd4)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/scatterlist.c (ffffffff81853abd)
Location: include/linux/xarray.h:1212
Inline: True
```
```
In lib/iov_iter.c (ffffffff81857026)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In net/core/skbuff.c (ffffffff81ece856)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
```
In net/core/datagram.c (ffffffff81eddbc7)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In lib/idr.c (ffffffff821791ca)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff821a1401)
Location: include/linux/xarray.h:1212
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
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
In mm/filemap.c (ffff8000102afe48)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffff8000102ba980)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffff8000102d6550)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffff8000103213b8)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffff80001034fe54)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffff80001035ff30)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffff80001037bfc8)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffff8000103c7918)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffff80001040974c)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffff800010d88d80)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffff800010d99a48)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (c04dcca0)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (c04e6c80)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (c04fe6b4)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c0539cf8)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (0)
Location: include/linux/xarray.h:1141
Inline: True
```
```
In mm/memfd.c (c0566af8)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (0)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/idr.c (c0e841fc)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (c0e963b8)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
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
In mm/filemap.c (c000000000364e10)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (c0000000003734a8)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (c000000000396668)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c0000000003f6914)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (c000000000433304)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (c00000000044acbc)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (c00000000047146c)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c0000000004c90fc)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (c000000000514b3c)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (c000000000ec9764)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (c000000000edf96c)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffe0001d5464)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffe0001ddd32)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffe0001f1c66)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffe0002227b2)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (0)
Location: include/linux/xarray.h:1141
Inline: True
```
```
In mm/memfd.c (ffffffe000252794)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffe00028655c)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffe0002b438c)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffe0008b3040)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffe0008c3254)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8121ae83)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81224844)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8123c820)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127f18d)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a642a)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812b6b54)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812cf593)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130abb7)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81340d1c)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a4e804)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a5d5de)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8120e083)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff812179ee)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8122f820)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81270fad)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81297eda)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812a7d24)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812c0211)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812fb7d7)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81331700)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a0b8f4)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a1a6ae)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff81218c23)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff812225e4)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff8123a5c0)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127cf2d)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a423a)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812b4964)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812cd3a3)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813089a7)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8133e7ec)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81ababf4)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81ac99ce)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff81227d18)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_prev_miss
  - mm/filemap.c:page_cache_next_miss
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff812319c6)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81249cb5)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128caed)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812b39aa)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812c538d)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812de11f)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8131a627)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8135167d)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81ac7044)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81ad5f13)
Location: include/linux/xarray.h:1141
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_load
```
</details>
</li>
</ul>

## Differences
