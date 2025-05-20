# Function: <code>__filemap_get_folio</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct folio *__filemap_get_folio(struct address_space *mapping, long unsigned int index, int fgp_flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:1940
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/folio-compat.c:pagecache_get_page
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/buffer.c:nobh_truncate_page
  - fs/verity/enable.c:read_file_data_page
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
```
**Symbols:**

```
ffffffff81e6b5c0-ffffffff81e6b602: __filemap_get_folio.cold (STB_LOCAL)
ffffffff812f3c40-ffffffff812f3ff2: __filemap_get_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct folio *__filemap_get_folio(struct address_space *mapping, long unsigned int index, int fgp_flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:1910
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/folio-compat.c:pagecache_get_page
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
```
**Symbols:**

```
ffffffff8206222d-ffffffff8206226f: __filemap_get_folio.cold (STB_LOCAL)
ffffffff8135df30-ffffffff8135e2e7: __filemap_get_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct folio *__filemap_get_folio(struct address_space *mapping, long unsigned int index, int fgp_flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81390e30)
Location: mm/filemap.c:1882
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/folio-compat.c:pagecache_get_page
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__find_get_block_slow
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
```
**Symbols:**

```
ffffffff81390e30-ffffffff81391055: __filemap_get_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct folio *__filemap_get_folio(struct address_space *mapping, long unsigned int index, fgf_t fgp_flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813bab10)
Location: mm/filemap.c:1848
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/folio-compat.c:pagecache_get_page
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - fs/libfs.c:simple_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__find_get_block_slow
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_get_folio
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
**Symbols:**

```
ffffffff813bab10-ffffffff813badf3: __filemap_get_folio (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int fgp_flags</code> ➡️ <code>fgf_t fgp_flags</code>
</li>
</ul>
</details>
</li>
</ul>
