# Function: <code>folio_test_dirty</code>

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
In mm/filemap.c (ffffffff812f1d60)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff812ff06d)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/swap.c (ffffffff813064ac)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/truncate.c (ffffffff81307662)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff8130e2e5)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff81337543)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/rmap.c (ffffffff8135d927)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff813b0908)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/memcontrol.c (ffffffff813d087e)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff81432422)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff81443976)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8148997d)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
```
```
In fs/ext4/inode.c (ffffffff814dfc70)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dirty_folio
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
In mm/filemap.c (ffffffff8135b186)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff813697f2)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/swap.c (ffffffff81370153)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff81371794)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff8138113e)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/gup.c (ffffffff813ae69d)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/mlock.c (ffffffff813c25ba)
Location: include/linux/page-flags.h:477
Inline: True
```
```
In mm/rmap.c (ffffffff813d8795)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f43e0)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8143459d)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8144999a)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81456031)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff814c0484)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814d21d6)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8151d815)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
```
```
In fs/ext4/inode.c (ffffffff81578fb0)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dirty_folio
```
```
In fs/fuse/dev.c (ffffffff8161b026)
Location: include/linux/page-flags.h:477
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
In mm/filemap.c (ffffffff8138caf0)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff8139b98f)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:folio_mark_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff813a22d3)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813a38a4)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813b24f0)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813daf10)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e2f9d)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/mlock.c (ffffffff813f6f08)
Location: include/linux/page-flags.h:471
Inline: True
```
```
In mm/rmap.c (ffffffff8140cf81)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814278ea)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff81469eea)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81477e27)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147fa49)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8148cf3d)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff814f5874)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff81509be6)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:folio_create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff81555ab6)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_release_folio
```
```
In fs/ext4/inode.c (ffffffff815b03e0)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dirty_folio
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/page-io.c (ffffffff815daaae)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/fuse/dev.c (ffffffff81653196)
Location: include/linux/page-flags.h:471
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
In mm/filemap.c (ffffffff813b6448)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff813c442e)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:folio_mark_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff813cbf4b)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813cd407)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813dba9d)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff81404e0c)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140d7da)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/mlock.c (ffffffff814230e6)
Location: include/linux/page-flags.h:473
Inline: True
```
```
In mm/mprotect.c (ffffffff8142efa1)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81439693)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814610c5)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8149abdf)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814a8b87)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814ad950)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814bc877)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff81529f84)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff8153ea16)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8158bd6d)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:ifs_alloc
```
```
In fs/ext4/inode.c (ffffffff815e91d0)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dirty_folio
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/page-io.c (ffffffff816132e0)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/fuse/dev.c (ffffffff8168c79a)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff817ac551)
Location: include/linux/page-flags.h:473
Inline: True
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
