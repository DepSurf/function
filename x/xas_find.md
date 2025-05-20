# Function: <code>xas_find</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17410)
Location: lib/xarray.c:1055
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff81a17410-ffffffff81a1759f: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a870a0)
Location: lib/xarray.c:1074
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff81a870a0-ffffffff81a87250: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abe330)
Location: lib/xarray.c:1081
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff81abe330-ffffffff81abe4e6: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fab60)
Location: lib/xarray.c:1081
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/fuse/file.c:__readahead_batch
  - fs/fuse/file.c:__readahead_batch
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff815fab60-ffffffff815fad28: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161f360)
Location: lib/xarray.c:1231
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/fuse/file.c:__readahead_batch
  - fs/fuse/file.c:__readahead_batch
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff8161f360-ffffffff8161f528: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816029b0)
Location: lib/xarray.c:1232
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/fuse/file.c:__readahead_batch
  - fs/fuse/file.c:__readahead_batch
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff816029b0-ffffffff81602b5b: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81670e30)
Location: lib/xarray.c:1232
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readahead
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff81670e30-ffffffff81670ffe: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178a830)
Location: lib/xarray.c:1239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/list_lru.c:memcg_destroy_list_lru
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readahead
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff8178a830-ffffffff8178aa19: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82047d70)
Location: lib/xarray.c:1239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/list_lru.c:memcg_destroy_list_lru
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/squashfs/file.c:__readahead_batch
  - fs/squashfs/file.c:__readahead_batch
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readahead
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff82047d70-ffffffff82047f59: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c6510)
Location: lib/xarray.c:1237
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/list_lru.c:memcg_destroy_list_lru
  - mm/madvise.c:shmem_swapin_range
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/squashfs/file.c:__readahead_batch
  - fs/squashfs/file.c:__readahead_batch
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readahead
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff820c6510-ffffffff820c66ef: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a0e90)
Location: lib/xarray.c:1237
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/list_lru.c:memcg_destroy_list_lru
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:shmem_swapin_range
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - fs/libfs.c:offset_iterate_dir
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/squashfs/file.c:__readahead_batch
  - fs/squashfs/file.c:__readahead_batch
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readahead
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff821a0e90-ffffffff821a106f: xas_find (STB_GLOBAL)
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
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d995d0)
Location: lib/xarray.c:1081
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffff800010d995d0-ffff800010d997a8: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e960cc)
Location: lib/xarray.c:1081
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
c0e960cc-c0e96294: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edf380)
Location: lib/xarray.c:1081
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
c000000000edf380-c000000000edf5c0: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2556)
Location: lib/xarray.c:1081
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffe0008c2556-ffffffe0008c26b6: xas_find (STB_GLOBAL)
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
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5d180)
Location: lib/xarray.c:1081
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff81a5d180-ffffffff81a5d336: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1a250)
Location: lib/xarray.c:1081
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff81a1a250-ffffffff81a1a406: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9570)
Location: lib/xarray.c:1081
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff81ac9570-ffffffff81ac9726: xas_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xas_find(struct xa_state *xas, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad5a80)
Location: lib/xarray.c:1081
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_range_has_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - lib/idr.c:ida_destroy
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
```
**Symbols:**

```
ffffffff81ad5a80-ffffffff81ad5c36: xas_find (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
