# Function: <code>xas_next_entry</code>

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
In mm/filemap.c (ffffffff811fd06b)
Location: include/linux/xarray.h:1426
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff81226a8c)
Location: include/linux/xarray.h:1426
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812920f2)
Location: include/linux/xarray.h:1426
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812a8f41)
Location: include/linux/xarray.h:1426
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/dax.c (ffffffff8130e7c8)
Location: include/linux/xarray.h:1426
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a08726)
Location: include/linux/xarray.h:1426
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a17806)
Location: include/linux/xarray.h:1426
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff812154e8)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff81235f4e)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812acc8e)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812c53a6)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81334f02)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a780d0)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a874b9)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff81222911)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff8124418e)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812be53f)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812d6d7b)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81348ae2)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81aaf980)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81abe759)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff8124fffd)
Location: include/linux/xarray.h:1590
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/shmem.c (ffffffff8126e097)
Location: include/linux/xarray.h:1590
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812f22d9)
Location: include/linux/xarray.h:1590
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8130be58)
Location: include/linux/xarray.h:1590
Inline: True
```
```
In fs/dax.c (ffffffff8138de0c)
Location: include/linux/xarray.h:1590
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In fs/fuse/file.c (ffffffff81475dfc)
Location: include/linux/xarray.h:1590
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff815e91e6)
Location: include/linux/xarray.h:1590
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff815faf3f)
Location: include/linux/xarray.h:1590
Inline: True
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065b7e)
Location: include/linux/xarray.h:1625
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8125a251)
Location: include/linux/xarray.h:1625
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/shmem.c (ffffffff8127c297)
Location: include/linux/xarray.h:1625
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/madvise.c (ffffffff812c104b)
Location: include/linux/xarray.h:1625
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812c4ad9)
Location: include/linux/xarray.h:1625
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/khugepaged.c (ffffffff812fe790)
Location: include/linux/xarray.h:1625
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff81317d18)
Location: include/linux/xarray.h:1625
Inline: True
```
```
In fs/dax.c (ffffffff8139f0ff)
Location: include/linux/xarray.h:1625
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff8149132f)
Location: include/linux/xarray.h:1625
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff8160e296)
Location: include/linux/xarray.h:1625
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff8161f771)
Location: include/linux/xarray.h:1625
Inline: True
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8106612e)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8125fe55)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/shmem.c (ffffffff81281457)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/madvise.c (ffffffff812c7e5e)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812cb772)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/khugepaged.c (ffffffff81305410)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8131df08)
Location: include/linux/xarray.h:1627
Inline: True
```
```
In fs/dax.c (ffffffff813a68c2)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff81496482)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/iov_iter.c (ffffffff815acc43)
Location: include/linux/xarray.h:1627
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
In lib/idr.c (ffffffff815f19e6)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81602e0a)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070250)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8129c7c5)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:page_cache_delete_batch
```
```
In mm/shmem.c (ffffffff812bca36)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/madvise.c (ffffffff8130cc28)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff81310867)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/khugepaged.c (ffffffff8134f260)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8136b236)
Location: include/linux/xarray.h:1627
Inline: True
```
```
In fs/dax.c (ffffffff813f6364)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff814eeff0)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff81619882)
Location: include/linux/xarray.h:1627
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
In lib/idr.c (ffffffff8165eb61)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff816712b2)
Location: include/linux/xarray.h:1627
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e412)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff812f3a61)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff81318ac6)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff81334bfe)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff81376188)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff8137b590)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/khugepaged.c (ffffffff813c5dea)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff813e91f9)
Location: include/linux/xarray.h:1654
Inline: True
```
```
In fs/dax.c (ffffffff814686b9)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/fuse/file.c (ffffffff8157eda6)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff816e6caf)
Location: include/linux/xarray.h:1654
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
In lib/idr.c (ffffffff817783fd)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff8178ad1f)
Location: include/linux/xarray.h:1654
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810910ad)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8135dde7)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff8138c986)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff813ab9ee)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff813f3ad5)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff813f8f10)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/khugepaged.c (ffffffff8144a94f)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814711a9)
Location: include/linux/xarray.h:1669
Inline: True
```
```
In fs/dax.c (ffffffff814f9149)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/squashfs/file.c (ffffffff815ee064)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81624a74)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff817d1b40)
Location: include/linux/xarray.h:1669
Inline: True
Direct callers:
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
In lib/idr.c (ffffffff8202118d)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff8204828f)
Location: include/linux/xarray.h:1669
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
```
**Symbols:**

```
ffffffff817d1b40-ffffffff817d1bfc: xas_next_entry.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093fed)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff8138cb18)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff813bf03d)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff813dfd7e)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff814275ab)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8142bce0)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/khugepaged.c (ffffffff81480c0e)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814a56fd)
Location: include/linux/xarray.h:1670
Inline: True
```
```
In fs/dax.c (ffffffff8152f939)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/squashfs/file.c (ffffffff81626011)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff8165ce35)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/scatterlist.c (ffffffff8180dd99)
Location: include/linux/xarray.h:1670
Inline: True
```
```
In lib/iov_iter.c (ffffffff818155f2)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_to_iter_nofault
Direct callers:
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
In lib/idr.c (ffffffff820a11ad)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff820c6a30)
Location: include/linux/xarray.h:1670
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
```
**Symbols:**

```
ffffffff818108a0-ffffffff81810958: xas_next_entry.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109b4cd)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In mm/filemap.c (ffffffff813b6687)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff813ea08d)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/list_lru.c (ffffffff8140a4ee)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_destroy_list_lru
```
```
In mm/madvise.c (ffffffff81460c73)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff81465440)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/khugepaged.c (ffffffff814aebe8)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814d66bd)
Location: include/linux/xarray.h:1688
Inline: True
```
```
In fs/libfs.c (ffffffff815220af)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - fs/libfs.c:offset_iterate_dir
```
```
In fs/dax.c (ffffffff81564819)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/squashfs/file.c (ffffffff8165f14e)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81696b92)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/scatterlist.c (ffffffff81853a83)
Location: include/linux/xarray.h:1688
Inline: True
```
```
In lib/iov_iter.c (ffffffff8185a76e)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
Direct callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In net/core/skbuff.c (ffffffff81ece809)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
```
In net/core/datagram.c (ffffffff81eddb80)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In lib/idr.c (ffffffff8217918d)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff821a13b0)
Location: include/linux/xarray.h:1688
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
```
**Symbols:**

```
ffffffff818562e0-ffffffff81856398: xas_next_entry.constprop.0 (STB_LOCAL)
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
In mm/filemap.c (ffff8000102aff10)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffff8000102d63bc)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffff80001035fec8)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffff80001037bd68)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffff800010408f60)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffff800010d88d40)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffff800010d99a08)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (c04dcd98)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (c04fe664)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/memfd.c (c0566aa8)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In lib/idr.c (c0e841ac)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (c0e96368)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (c000000000364f30)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (c00000000039661c)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (c00000000044ac60)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (c000000000471190)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (c000000000515284)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (c000000000ec9718)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (c000000000edf908)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffe0001d533c)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffe0001f1bf0)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/memfd.c (ffffffe000252406)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffe0002b3392)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffe0008b3000)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffe0008c320e)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff8121af61)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff8123c7de)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812b6b1f)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812cf35b)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff813410c2)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a4e7d0)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a5d5a9)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff8120e15b)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff8122f7de)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812a7cef)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812bffe5)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81331a9c)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81a0b8c0)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81a1a679)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff81218d01)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff8123a57e)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812b492f)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812cd16b)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff8133eb92)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81ababc0)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81ac9999)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff81227df7)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/shmem.c (ffffffff81249c73)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812c5358)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812ddefd)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dax.c (ffffffff81351a54)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
```
```
In lib/idr.c (ffffffff81ac7010)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
```
```
In lib/xarray.c (ffffffff81ad5ede)
Location: include/linux/xarray.h:1555
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
```
</details>
</li>
</ul>

## Differences
