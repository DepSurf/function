# Function: <code>folio_mark_dirty</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
bool folio_mark_dirty(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812fc650)
Location: mm/page-writeback.c:2705
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/folio-compat.c:set_page_dirty
  - mm/folio-compat.c:set_page_dirty
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/swap_state.c:add_to_swap
  - fs/buffer.c:nobh_truncate_page
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
**Symbols:**

```
ffffffff812fc650-ffffffff812fc6b3: folio_mark_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool folio_mark_dirty(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81366970)
Location: mm/page-writeback.c:2843
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/folio-compat.c:set_page_dirty
  - mm/folio-compat.c:set_page_dirty
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_file
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
**Symbols:**

```
ffffffff81366970-ffffffff813669d3: folio_mark_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool folio_mark_dirty(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81398fe0)
Location: mm/page-writeback.c:2784
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/folio-compat.c:set_page_dirty
  - mm/folio-compat.c:set_page_dirty
  - mm/folio-compat.c:set_page_dirty
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/swap_state.c:add_to_swap
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_file
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:do_journal_get_write_access
```
**Symbols:**

```
ffffffff81398fe0-ffffffff81399040: folio_mark_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool folio_mark_dirty(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c2de0)
Location: mm/page-writeback.c:2763
Inline: False
Direct callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/folio-compat.c:set_page_dirty
  - mm/folio-compat.c:set_page_dirty
  - mm/folio-compat.c:set_page_dirty
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:__end_swap_bio_write
  - mm/swap_state.c:add_to_swap
  - mm/zswap.c:zswap_load
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/khugepaged.c:collapse_file
  - fs/libfs.c:simple_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:do_journal_get_write_access
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
```
**Symbols:**

```
ffffffff813c2de0-ffffffff813c2e40: folio_mark_dirty (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
