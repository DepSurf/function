# Function: <code>folio_test_writeback</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812ef46c)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/filemap.c:filemap_release_folio
  - mm/filemap.c:find_lock_entries
```
```
In mm/page-writeback.c (ffffffff812fcaba)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
```
```
In mm/readahead.c (ffffffff8130245f)
Location: include/linux/page-flags.h:539
Inline: True
```
```
In mm/truncate.c (ffffffff81307ed7)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff8130e30b)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/migrate.c (ffffffff813b23c8)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/memcontrol.c (ffffffff813d0799)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff814324bc)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814438ed)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/iomap/buffered-io.c (ffffffff8148996d)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
```
```
In fs/ext4/inode.c (ffffffff814e146f)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff81359fac)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/filemap.c:filemap_release_folio
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:filemap_range_has_writeback
```
```
In mm/page-writeback.c (ffffffff81366e1a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
```
```
In mm/readahead.c (ffffffff8136cc0f)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/swap.c (ffffffff81370147)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813712d7)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff8138114a)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/memory.c (ffffffff813bc45b)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff813c25ee)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In mm/swapfile.c (ffffffff813fe607)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/migrate.c (ffffffff81431509)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff81441ba5)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814499a5)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81455ea9)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff814c056c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814d214d)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/aio.c (ffffffff814f17f5)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8151d809)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
```
```
In fs/ext4/inode.c (ffffffff81579cfc)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/fuse/dev.c (ffffffff8161b02d)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8138cafc)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_release_folio
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:filemap_range_has_writeback
```
```
In mm/page-writeback.c (ffffffff8139949a)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8139ee6f)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In mm/swap.c (ffffffff813a22c7)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813a34a7)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff813b24fc)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813daf04)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff813f0ce1)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff813f6f3b)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In mm/swapfile.c (ffffffff8143159d)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/migrate.c (ffffffff81468778)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff8147754c)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8147fa54)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8148cf7d)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff814f59bf)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff81509b5d)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8150f01e)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff81529685)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/iomap/buffered-io.c (ffffffff81555aaa)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_release_folio
```
```
In fs/ext4/inode.c (ffffffff815b5ba2)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff815cfd03)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815da9a9)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/fuse/dev.c (ffffffff8165319d)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff813b5501)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/filemap.c:filemap_release_folio
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:filemap_range_has_writeback
```
```
In mm/page-writeback.c (ffffffff813c329a)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff813c8acf)
Location: include/linux/page-flags.h:513
Inline: True
```
```
In mm/swap.c (ffffffff813cbf40)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813ce71b)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff813dbaa8)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff81404e07)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff814207a6)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff81423115)
Location: include/linux/page-flags.h:513
Inline: True
```
```
In mm/swapfile.c (ffffffff8146a98d)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/migrate.c (ffffffff81497e22)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814a6cbc)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814ad95b)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814bc8b7)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff8152a0c9)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff8153e990)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8154385e)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff8155e555)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8158bd62)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/ext4/inode.c (ffffffff815ee952)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff81608583)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8161316b)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/fuse/dev.c (ffffffff8168c7a1)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
