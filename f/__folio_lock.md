# Function: <code>__folio_lock</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __folio_lock(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f1c24)
Location: mm/filemap.c:1688
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__folio_lock_or_retry
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/events/uprobes.c:__replace_page
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/hugetlb.c:hugetlb_no_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:get_ksm_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:writeout
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/fuse/file.c:fuse_page_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff812f1a80-ffffffff812f1aa7: __folio_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __folio_lock(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135cccf)
Location: mm/filemap.c:1658
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__folio_lock_or_retry
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/events/uprobes.c:__replace_page
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/hugetlb.c:hugetlb_no_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:get_ksm_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:writeout
  - mm/migrate.c:putback_movable_pages
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memremap.c:zone_device_page_init
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/fuse/file.c:fuse_page_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff8135c890-ffffffff8135c8b7: __folio_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __folio_lock(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138ecfd)
Location: mm/filemap.c:1632
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__folio_lock_or_retry
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/events/uprobes.c:__replace_page
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/hugetlb.c:hugetlb_no_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:get_ksm_page
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:writeout
  - mm/migrate.c:putback_movable_pages
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memremap.c:zone_device_page_init
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/fuse/file.c:fuse_page_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff8138e8c0-ffffffff8138e8e7: __folio_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __folio_lock(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b80ea)
Location: mm/filemap.c:1612
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__folio_lock_or_retry
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/events/uprobes.c:__replace_page
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:pageout
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/hugetlb.c:hugetlb_no_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:get_ksm_page
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:writeout
  - mm/migrate.c:putback_movable_pages
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/userfaultfd.c:move_pages_pte
  - mm/memremap.c:zone_device_page_init
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/fuse/file.c:fuse_page_mkwrite
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff813b7f80-ffffffff813b7fa7: __folio_lock (STB_GLOBAL)
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
