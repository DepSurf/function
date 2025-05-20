# Function: <code>xas_reset</code>

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
In mm/filemap.c (ffffffff811fd123)
Location: include/linux/xarray.h:1301
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff81226afb)
Location: include/linux/xarray.h:1301
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812920ea)
Location: include/linux/xarray.h:1301
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff8130ed9b)
Location: include/linux/xarray.h:1301
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (ffffffff81a178e7)
Location: include/linux/xarray.h:1301
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff8121554f)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff81235fc8)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812accf7)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff81334a86)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (ffffffff81a8766f)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff81222978)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff81244208)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812be5a6)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/dax.c (ffffffff8134865e)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (ffffffff81abe90f)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff812500d3)
Location: include/linux/xarray.h:1465
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff8126e370)
Location: include/linux/xarray.h:1465
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812f247e)
Location: include/linux/xarray.h:1465
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/dax.c (ffffffff8138db37)
Location: include/linux/xarray.h:1465
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (ffffffff815faedb)
Location: include/linux/xarray.h:1465
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff8125a34b)
Location: include/linux/xarray.h:1467
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff8127c572)
Location: include/linux/xarray.h:1467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812fe93d)
Location: include/linux/xarray.h:1467
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/dax.c (ffffffff8139f5aa)
Location: include/linux/xarray.h:1467
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/fuse/file.c (ffffffff81491494)
Location: include/linux/xarray.h:1467
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/xarray.c (ffffffff8161f703)
Location: include/linux/xarray.h:1467
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff8125e24a)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
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
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff81281741)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff813055b5)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/dax.c (ffffffff813a6316)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/fuse/file.c (ffffffff814965eb)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/iov_iter.c (ffffffff815acd34)
Location: include/linux/xarray.h:1469
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
In lib/xarray.c (ffffffff81603010)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff8129a98f)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
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
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff812bcd03)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8134f3d9)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/dax.c (ffffffff813f5d86)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/fuse/file.c (ffffffff814ef2ff)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff81619b9a)
Location: include/linux/xarray.h:1469
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
In lib/xarray.c (ffffffff816714a1)
Location: include/linux/xarray.h:1469
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff812f15bc)
Location: include/linux/xarray.h:1472
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff81318c3f)
Location: include/linux/xarray.h:1472
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/huge_memory.c (ffffffff813bf775)
Location: include/linux/xarray.h:1472
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c5fcd)
Location: include/linux/xarray.h:1472
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/dax.c (ffffffff814695dd)
Location: include/linux/xarray.h:1472
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/fuse/file.c (ffffffff8157f046)
Location: include/linux/xarray.h:1472
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff816e6f59)
Location: include/linux/xarray.h:1472
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
In lib/xarray.c (ffffffff8178af21)
Location: include/linux/xarray.h:1472
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff8135bf5c)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff8138caff)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/huge_memory.c (ffffffff81441cbe)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8144abc6)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/dax.c (ffffffff814fa07d)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/squashfs/file.c (ffffffff815ee0f4)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81624d07)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff817d680f)
Location: include/linux/xarray.h:1487
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
In lib/xarray.c (ffffffff82048491)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff8138cc91)
Location: include/linux/xarray.h:1487
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
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff813bf1c3)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/huge_memory.c (ffffffff8147779b)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81480dcd)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/dax.c (ffffffff815314fb)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/squashfs/file.c (ffffffff816260a5)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff8165cec6)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/scatterlist.c (ffffffff8180de80)
Location: include/linux/xarray.h:1487
Inline: True
```
```
In lib/iov_iter.c (ffffffff81813e5d)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In lib/xarray.c (ffffffff820c6c17)
Location: include/linux/xarray.h:1487
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff813b679e)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff813ea213)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/huge_memory.c (ffffffff814a6ddd)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814aeda1)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/dax.c (ffffffff815663db)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/squashfs/file.c (ffffffff8165f1e2)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81696c23)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/scatterlist.c (ffffffff81853b2c)
Location: include/linux/xarray.h:1505
Inline: True
```
```
In lib/iov_iter.c (ffffffff8185717d)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In net/core/skbuff.c (ffffffff81ece8fb)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
```
In net/core/datagram.c (ffffffff81eddc41)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In lib/xarray.c (ffffffff821a1597)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffff8000102afffc)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffff8000102d65e4)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffff80001036025c)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffff8000104095d8)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (ffff800010d99bbc)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (c04dcc30)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (c04fe608)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In lib/xarray.c (c0e96348)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (c000000000365130)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (c0000000003966a0)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (c00000000044af30)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/dax.c (c000000000514c14)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (c000000000edfb60)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffe0001d5494)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffe0001f1c9a)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In fs/dax.c (ffffffe0002b4250)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (ffffffe0008c3218)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff8121afc8)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff8123c858)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812b6b86)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/dax.c (ffffffff81340c3e)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (ffffffff81a5d75f)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff8120e1c2)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff8122f858)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812a7d56)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/dax.c (ffffffff81331628)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (ffffffff81a1a82f)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff81218d68)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff8123a5f8)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812b4996)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/dax.c (ffffffff8133e70e)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (ffffffff81ac9b4f)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
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
In mm/filemap.c (ffffffff81227e5e)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff81249ced)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812c53c0)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff813515a5)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:get_unlocked_entry
```
```
In lib/xarray.c (ffffffff81ad60a2)
Location: include/linux/xarray.h:1430
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:xa_load
```
</details>
</li>
</ul>

## Differences
