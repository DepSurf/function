# Function: <code>xas_retry</code>

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
In mm/filemap.c (ffffffff811fcfc0)
Location: include/linux/xarray.h:1318
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
In mm/shmem.c (ffffffff81226a53)
Location: include/linux/xarray.h:1318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8129208b)
Location: include/linux/xarray.h:1318
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In lib/xarray.c (ffffffff81a17910)
Location: include/linux/xarray.h:1318
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
In mm/filemap.c (ffffffff81215440)
Location: include/linux/xarray.h:1447
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
In mm/shmem.c (ffffffff81235edb)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812acade)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In lib/xarray.c (ffffffff81a87490)
Location: include/linux/xarray.h:1447
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
In mm/filemap.c (ffffffff812227d1)
Location: include/linux/xarray.h:1447
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
In mm/shmem.c (ffffffff8124411b)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812be36c)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In lib/xarray.c (ffffffff81abe730)
Location: include/linux/xarray.h:1447
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
In mm/filemap.c (ffffffff8124feff)
Location: include/linux/xarray.h:1482
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
In mm/shmem.c (ffffffff8126e004)
Location: include/linux/xarray.h:1482
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812f223c)
Location: include/linux/xarray.h:1482
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In lib/xarray.c (ffffffff815fae90)
Location: include/linux/xarray.h:1482
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
In mm/filemap.c (ffffffff8125a109)
Location: include/linux/xarray.h:1484
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
In mm/shmem.c (ffffffff8127c204)
Location: include/linux/xarray.h:1484
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812fe6ec)
Location: include/linux/xarray.h:1484
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/fuse/file.c (ffffffff81491347)
Location: include/linux/xarray.h:1484
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/xarray.c (ffffffff8161f6a9)
Location: include/linux/xarray.h:1484
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
In mm/filemap.c (ffffffff8125e0d4)
Location: include/linux/xarray.h:1486
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
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff812813c4)
Location: include/linux/xarray.h:1486
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8130536c)
Location: include/linux/xarray.h:1486
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/fuse/file.c (ffffffff8149649d)
Location: include/linux/xarray.h:1486
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/iov_iter.c (ffffffff815acb22)
Location: include/linux/xarray.h:1486
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
In lib/xarray.c (ffffffff81602dde)
Location: include/linux/xarray.h:1486
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
In mm/filemap.c (ffffffff8129a7fc)
Location: include/linux/xarray.h:1486
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
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff812bc999)
Location: include/linux/xarray.h:1486
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8134f1bc)
Location: include/linux/xarray.h:1486
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/fuse/file.c (ffffffff814ef008)
Location: include/linux/xarray.h:1486
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff8161978f)
Location: include/linux/xarray.h:1486
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
In lib/xarray.c (ffffffff81671282)
Location: include/linux/xarray.h:1486
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
In mm/filemap.c (ffffffff812f145c)
Location: include/linux/xarray.h:1489
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
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff81318a63)
Location: include/linux/xarray.h:1489
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff813c5dba)
Location: include/linux/xarray.h:1489
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In fs/fuse/file.c (ffffffff8157ed4c)
Location: include/linux/xarray.h:1489
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff816e6b99)
Location: include/linux/xarray.h:1489
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
In lib/xarray.c (ffffffff8178acf3)
Location: include/linux/xarray.h:1489
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
In mm/filemap.c (ffffffff8135bdfc)
Location: include/linux/xarray.h:1504
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
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff8138c923)
Location: include/linux/xarray.h:1504
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8144a856)
Location: include/linux/xarray.h:1504
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/squashfs/file.c (ffffffff815edffb)
Location: include/linux/xarray.h:1504
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81624a0c)
Location: include/linux/xarray.h:1504
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff817d6502)
Location: include/linux/xarray.h:1504
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
In lib/xarray.c (ffffffff82048263)
Location: include/linux/xarray.h:1504
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
In mm/filemap.c (ffffffff8138ca73)
Location: include/linux/xarray.h:1504
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
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff813befd1)
Location: include/linux/xarray.h:1504
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff81480a97)
Location: include/linux/xarray.h:1504
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/squashfs/file.c (ffffffff81625fbb)
Location: include/linux/xarray.h:1504
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff8165cde0)
Location: include/linux/xarray.h:1504
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/scatterlist.c (ffffffff8180dcb9)
Location: include/linux/xarray.h:1504
Inline: True
```
```
In lib/iov_iter.c (ffffffff81813b8d)
Location: include/linux/xarray.h:1504
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
In lib/xarray.c (ffffffff820c6a03)
Location: include/linux/xarray.h:1504
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
In mm/filemap.c (ffffffff813b65d0)
Location: include/linux/xarray.h:1522
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
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/shmem.c (ffffffff813ea021)
Location: include/linux/xarray.h:1522
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff814aea77)
Location: include/linux/xarray.h:1522
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/squashfs/file.c (ffffffff8165f0fb)
Location: include/linux/xarray.h:1522
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81696b40)
Location: include/linux/xarray.h:1522
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/scatterlist.c (ffffffff81853965)
Location: include/linux/xarray.h:1522
Inline: True
```
```
In lib/iov_iter.c (ffffffff81857044)
Location: include/linux/xarray.h:1522
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
In net/core/skbuff.c (ffffffff81ece6b3)
Location: include/linux/xarray.h:1522
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
```
In net/core/datagram.c (ffffffff81edda4a)
Location: include/linux/xarray.h:1522
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In lib/xarray.c (ffffffff821a1383)
Location: include/linux/xarray.h:1522
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
In mm/filemap.c (ffff8000102afde0)
Location: include/linux/xarray.h:1447
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
In mm/shmem.c (ffff8000102d6368)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffff80001035fcb8)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In lib/xarray.c (ffff800010d999e8)
Location: include/linux/xarray.h:1447
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
In mm/filemap.c (c04dcc20)
Location: include/linux/xarray.h:1447
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
In mm/shmem.c (c04fe5f8)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In lib/xarray.c (c0e9633c)
Location: include/linux/xarray.h:1447
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
In mm/filemap.c (c000000000364da0)
Location: include/linux/xarray.h:1447
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
In mm/shmem.c (c0000000003965c0)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (c00000000044aa4c)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In lib/xarray.c (c000000000edf8e0)
Location: include/linux/xarray.h:1447
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
In mm/filemap.c (ffffffe0001d5338)
Location: include/linux/xarray.h:1447
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
In mm/shmem.c (ffffffe0001f1bf2)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In lib/xarray.c (ffffffe0008c320a)
Location: include/linux/xarray.h:1447
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
In mm/filemap.c (ffffffff8121ae21)
Location: include/linux/xarray.h:1447
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
In mm/shmem.c (ffffffff8123c76b)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812b694c)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In lib/xarray.c (ffffffff81a5d580)
Location: include/linux/xarray.h:1447
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
In mm/filemap.c (ffffffff8120e021)
Location: include/linux/xarray.h:1447
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
In mm/shmem.c (ffffffff8122f76b)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812a7b1c)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In lib/xarray.c (ffffffff81a1a650)
Location: include/linux/xarray.h:1447
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
In mm/filemap.c (ffffffff81218bc1)
Location: include/linux/xarray.h:1447
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
In mm/shmem.c (ffffffff8123a50b)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812b475c)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In lib/xarray.c (ffffffff81ac9970)
Location: include/linux/xarray.h:1447
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
In mm/filemap.c (ffffffff81227cb6)
Location: include/linux/xarray.h:1447
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
In mm/shmem.c (ffffffff81249c00)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812c5132)
Location: include/linux/xarray.h:1447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In lib/xarray.c (ffffffff81ad5eb5)
Location: include/linux/xarray.h:1447
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
