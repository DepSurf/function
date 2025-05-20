# Function: <code>set_page_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81198aa0)
Location: mm/page-writeback.c:2545
Inline: True
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/gup.c:follow_page_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:end_swap_bio_write
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_with_ksm_page
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:nobh_truncate_page
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff81198aa0-ffffffff81198b03: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811ad8a0)
Location: mm/page-writeback.c:2589
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/khugepaged.c:collapse_shmem
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff811ad8a0-ffffffff811ad948: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bde00)
Location: mm/page-writeback.c:2556
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/khugepaged.c:collapse_shmem
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff811bde00-ffffffff811bdea8: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c5fb0)
Location: mm/page-writeback.c:2559
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/khugepaged.c:collapse_shmem
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff811c5fb0-ffffffff811c6058: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dadc0)
Location: mm/page-writeback.c:2542
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/khugepaged.c:collapse_shmem
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff811dadc0-ffffffff811dae6b: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fbec0)
Location: mm/page-writeback.c:2543
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/khugepaged.c:collapse_shmem
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap.c:iomap_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff811fbec0-ffffffff811fbf6c: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8120e7a0)
Location: mm/page-writeback.c:2537
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_shmem
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff8120e7a0-ffffffff8120e84c: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121e2b0)
Location: mm/page-writeback.c:2545
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/truncate.c:pagecache_isize_extended
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_shmem
  - mm/hmm.c:hmm_range_dma_unmap
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff8121e2b0-ffffffff8121e364: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122bd50)
Location: mm/page-writeback.c:2549
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - mm/hmm.c:hmm_range_dma_unmap
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff8122bd50-ffffffff8122be04: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812586e0)
Location: mm/page-writeback.c:2559
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/truncate.c:pagecache_isize_extended
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:write_protect_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff812586e0-ffffffff81258796: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81262cf0)
Location: mm/page-writeback.c:2557
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/truncate.c:pagecache_isize_extended
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:write_protect_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff81262cf0-ffffffff81262da6: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81267710)
Location: mm/page-writeback.c:2557
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/truncate.c:pagecache_isize_extended
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:write_protect_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff81267710-ffffffff812677c6: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a4280)
Location: mm/page-writeback.c:2591
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/truncate.c:pagecache_isize_extended
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:write_protect_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff812a4280-ffffffff812a432b: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300dd0)
Location: mm/folio-compat.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/truncate.c:pagecache_isize_extended
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:zap_pte_range
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:end_swap_bio_write
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:write_protect_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff81300dd0-ffffffff81300e27: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b640)
Location: mm/folio-compat.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/truncate.c:pagecache_isize_extended
  - mm/shmem.c:shmem_write_end
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:zap_pte_range
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:end_swap_bio_write
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:write_protect_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff8136b640-ffffffff8136b697: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139d820)
Location: mm/folio-compat.c:55
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/truncate.c:pagecache_isize_extended
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:zap_pte_range
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:__end_swap_bio_write
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:write_protect_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - fs/libfs.c:simple_write_end
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff8139d820-ffffffff8139d884: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7610)
Location: mm/folio-compat.c:55
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/truncate.c:pagecache_isize_extended
  - mm/gup.c:follow_page_pte
  - mm/page_io.c:sio_write_complete
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:write_protect_page
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff813c7610-ffffffff813c7671: set_page_dirty (STB_GLOBAL)
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
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bc210)
Location: mm/page-writeback.c:2549
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - mm/hmm.c:hmm_range_dma_unmap
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffff8000102bc210-ffff8000102bc340: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04e6970)
Location: mm/page-writeback.c:2549
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/ksm.c:write_protect_page
  - mm/hmm.c:hmm_range_dma_unmap
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
c04e6970-c04e6a3c: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c000000000372f60)
Location: mm/page-writeback.c:2549
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/truncate.c:pagecache_isize_extended
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - mm/hmm.c:hmm_range_dma_unmap
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
c000000000372f60-c0000000003730d0: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001dd9c8)
Location: mm/page-writeback.c:2549
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hmm.c:hmm_range_dma_unmap
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffe0001dd9c8-ffffffe0001dda84: set_page_dirty (STB_GLOBAL)
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
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812243a0)
Location: mm/page-writeback.c:2549
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - mm/hmm.c:hmm_range_dma_unmap
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff812243a0-ffffffff81224454: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81217550)
Location: mm/page-writeback.c:2549
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - mm/hmm.c:hmm_range_dma_unmap
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff81217550-ffffffff81217604: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81222140)
Location: mm/page-writeback.c:2549
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - mm/hmm.c:hmm_range_dma_unmap
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff81222140-ffffffff812221f4: set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81231590)
Location: mm/page-writeback.c:2549
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:follow_page_pte
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - mm/hmm.c:hmm_range_dma_unmap
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
```
**Symbols:**

```
ffffffff81231590-ffffffff81231644: set_page_dirty (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
