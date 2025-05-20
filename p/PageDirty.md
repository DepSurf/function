# Function: <code>PageDirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e518)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff81198ae7)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffff8119d189)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8119ea87)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff811a028d)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/gup.c (ffffffff811ba5cc)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/swapfile.c (ffffffff811d5675)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff811f1760)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff811f7405)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff811fd32f)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812027f9)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff8123a625)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812438dd)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/proc/task_mmu.c (ffffffff81276971)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff81297d64)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff8130ea40)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff813b2d77)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81473735)
Location: include/linux/page-flags.h:213
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1f56)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811adcb7)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff811b337f)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff811b4629)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff811b89ff)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff811d4ac2)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/rmap.c (ffffffff811e9509)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811eedfa)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff811f368f)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/ksm.c (ffffffff812042fe)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff81211608)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8121835b)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81220ed9)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81226ea0)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff8126236a)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8126b9e3)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/proc/task_mmu.c (ffffffff812a46f7)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inode.c (ffffffff812c52a3)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff81342dfa)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff813f652e)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1da6)
Location: include/linux/page-flags.h:260
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b1da6)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811be305)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff811c39ff)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff811c4cae)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff811c902f)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff811e4afa)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/rmap.c (ffffffff811fa859)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ff875)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8120415a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/ksm.c (ffffffff81216458)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812237c8)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8122a8ff)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81233629)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81239468)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff812758af)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8127eb23)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/proc/task_mmu.c (ffffffff812ba057)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inode.c (ffffffff812d8b03)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff81358c19)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff8140ff0e)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3d96)
Location: include/linux/page-flags.h:270
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b8c13)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811c7616)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff811cbe0f)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff811ccdc9)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff811d1b0c)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff811ef172)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/rmap.c (ffffffff812043f7)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8120a2a4)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8120f803)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/ksm.c (ffffffff812219f8)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122f1c2)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81236597)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8123eef6)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81244a89)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81282da4)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8128ca0f)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/proc/task_mmu.c (ffffffff812c7796)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inode.c (ffffffff812fcddf)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff8136d491)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff8141d88b)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814efb66)
Location: include/linux/page-flags.h:270
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca181)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff811dc444)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff811e0dff)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff811e2322)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff811e6fab)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff8120628e)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/rmap.c (ffffffff8121d1c7)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81223508)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8122b0a1)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/ksm.c (ffffffff8123ccf1)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124bf0e)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81255526)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8125ea85)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81264979)
Location: include/linux/page-flags.h:271
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a58f4)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812afa2c)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/proc/task_mmu.c (ffffffff812eb396)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inode.c (ffffffff813216df)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff81391f15)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff8144871b)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815246d5)
Location: include/linux/page-flags.h:271
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb2fd)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff811fe6f4)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff8120268f)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81203a1a)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812084d0)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff81226535)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff81239228)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8123f0b5)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812466a7)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8124c308)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/ksm.c (ffffffff812607f2)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812723e4)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81276d38)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81282d33)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812890cf)
Location: include/linux/page-flags.h:278
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cc4d0)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812d78ac)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/proc/task_mmu.c (ffffffff813186c6)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inode.c (ffffffff8134f73f)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff813c0f3f)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff8147b85b)
Location: include/linux/page-flags.h:278
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a425)
Location: include/linux/page-flags.h:278
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fbe6d)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8120efe6)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff8121500f)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8121630d)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8121b160)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff8123a873)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff8124d7af)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812536cd)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8125aaca)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8126080b)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/ksm.c (ffffffff81274f44)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812869f6)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812885ce)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81296ed3)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8129e01f)
Location: include/linux/page-flags.h:287
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e15d8)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812ecd0c)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap.c (ffffffff81325a55)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/iomap.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff8132f5d8)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inode.c (ffffffff8136791f)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff813da2a1)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff81499a2c)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571d35)
Location: include/linux/page-flags.h:287
Inline: True
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
In mm/filemap.c (ffffffff81213f70)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8121eb67)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff81224a2f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81225ce1)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8122adef)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff8124bb73)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:__put_user_pages_dirty
```
```
In mm/mprotect.c (ffffffff8125f7b8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81265931)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812759ce)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff8128fb5f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a0f8a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a320c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b2b60)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812b91d4)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812ffd5b)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130e4c0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8134cc25)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff81357024)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff81390c1f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff81405edf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814c7b17)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a2215)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/filemap.c (ffffffff812217a8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8122c607)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff812327bf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81233b40)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81238cbf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff8125a063)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff8126dfc8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81274246)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8128499e)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff8129f8ef)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812b239a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b470c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812bc4dd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c4619)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812cb0c4)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81312561)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff813214e0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff81364ef5)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff8136f5f4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff813a95df)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff81420a3f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814e0c17)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c3095)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/filemap.c (ffffffff8124f6c9)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81259f17)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff8125f8a9)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff812610e3)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812677fb)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff81288574)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff8129e86d)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812a54c7)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812b6b97)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff812d3f5f)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812e793a)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812e9cb6)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812f1960)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812fa514)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8130116f)
Location: include/linux/page-flags.h:326
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8134bd47)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8135bc24)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813abff8)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff813b6e46)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff813f547f)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff8146fb06)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff8153fa6b)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d235)
Location: include/linux/page-flags.h:326
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
In mm/filemap.c (ffffffff81259980)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812656cb)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff81269e90)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8126b4e1)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81272267)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page_prepare
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff8129225d)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff812a9c23)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b095c)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c2dd4)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff812df94f)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812f2cdb)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f4e96)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812fdee4)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81306441)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8130d1bf)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81358c5c)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8136a1c4)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813bc1f1)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff813c84e6)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff81407c1f)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff8148a3ac)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff8155c28b)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168d955)
Location: include/linux/page-flags.h:334
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
In mm/filemap.c (ffffffff8125dc39)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8126a1c7)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff8126ee43)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81270645)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812773d1)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff81297e1c)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/mprotect.c (ffffffff812af0ae)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b5f8e)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c9c4d)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff812e826b)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812f90aa)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fb40a)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81304891)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130c92a)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8131377f)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8135f7bc)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81370de3)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813c36cf)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff813cf524)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff8140e09f)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff8148ff01)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff81564b3b)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81670645)
Location: include/linux/page-flags.h:334
Inline: True
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
In mm/filemap.c (ffffffff81299edd)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812a6e5a)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff812abeab)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff812ae2d0)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812b4d2e)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff812d885c)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/mprotect.c (ffffffff812f08bc)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812f7ba4)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8130ec6d)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff8133019b)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff813435b9)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81345239)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134e5da)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81357b2a)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81360494)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/fs-writeback.c (ffffffff813ae123)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff813bfa82)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff81413d37)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff81420904)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff81460f6f)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff814e796e)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff815c8ebb)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e4915)
Location: include/linux/page-flags.h:348
Inline: True
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
In mm/filemap.c (ffffffff812f0396)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/filemap.c:filemap_range_has_writeback
```
```
In mm/page-writeback.c (ffffffff812fd2de)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff81305d63)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff81313577)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff8133129c)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81338993)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff8135407b)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff81376d4b)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff813a0b88)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff813b5e22)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_folio
```
```
In mm/huge_memory.c (ffffffff813bb0d3)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c505b)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff813dbbaa)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/buffer.c (ffffffff814453ef)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/proc/task_mmu.c (ffffffff81499749)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff814e1ecf)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff81575da3)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff81673f81)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
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
In mm/page-writeback.c (ffffffff81367bfe)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/compaction.c (ffffffff813a7f61)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813b0135)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff813ce53f)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (ffffffff814203f8)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81435fb5)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff81444024)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81449d18)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff81462900)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/buffer.c (ffffffff814d4c6f)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/proc/task_mmu.c (ffffffff8152da04)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff8157b21d)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/page-io.c (ffffffff815a4212)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In block/bio.c (ffffffff8172fbf1)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
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
In mm/gup.c (ffffffff813e47ba)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff81402e38)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (ffffffff81455008)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8146bc40)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff814795cc)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8147f902)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff81498771)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff81565e3b)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In block/bio.c (ffffffff8176be1f)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
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
In mm/gup.c (ffffffff8140ed8c)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/ksm.c (ffffffff814902bf)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/khugepaged.c (ffffffff814adc04)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff814c7c83)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8159de0f)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
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
In mm/filemap.c (ffff8000102aed90)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffff8000102bc0c0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffff8000102c25a0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffff8000102c401c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffff8000102c9b04)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffff8000102f1ae0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffff800010305210)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff800010309e54)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffff80001031eb6c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffff80001033ecd4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffff800010352ba8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff800010355cd4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035d7d0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff80001036728c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffff80001036eaac)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103c7618)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffff8000103d88a8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffff80001042a970)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffff800010438cf0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffff80001047d458)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffff800010503638)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffff8000105dd73c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c188)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/filemap.c (c04da9a0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c04e6f54)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (c04ed7f8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (c04ee9e8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (c04f3a00)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (c0514310)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/mprotect.c (c05234a0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0526698)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0537780)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (c05453b8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (c05521f8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (c05589a0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/fs-writeback.c (c05a44d0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (c05b32bc)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (c05f4bf8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (c0600ac0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (c063ed34)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (c06bfcc4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (c078ab94)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (c08cebf4)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/filemap.c (c00000000036222c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c000000000373814)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (c00000000037c560)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (c00000000037e560)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (c0000000003862ac)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (c0000000003b61a8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (c0000000003d2534)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0000000003d9ab8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0000000003f3384)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (c00000000041b2d4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (c0000000004395b0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c00000000043bff0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (c000000000448a58)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c0000000004546e4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (c00000000045f79c)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/fs-writeback.c (c0000000004c907c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (c0000000004deb80)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:attach_nobh_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (c00000000053c2e0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (c00000000054c5d4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (c0000000005a109c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (c0000000006481b8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (c00000000076f028)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008adff8)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/filemap.c (ffffffe0001d4348)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffe0001de188)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffe0001e39c4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffe0001e4b76)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffe0001e8e1e)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffe000204504)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/mprotect.c (ffffffe000211350)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000213de2)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffe0002205c2)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffe000234ace)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023f568)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffe000245428)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/fs-writeback.c (ffffffe000286284)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffe000292f18)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8af4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffe0002d3254)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffe000306ef2)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffe000370458)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffe000420810)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9d52)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/filemap.c (ffffffff81219df8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81224c57)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff8122ae0f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8122c190)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8123130f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff812526b3)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff81266618)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126c896)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127cfee)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff81297ecf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812aa97a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812accec)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b4abd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812bcbf9)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c36a4)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130ab41)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81319ac0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8135d4d5)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff81367bd4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff813a1bbf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff8141901f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814d91f7)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b71e5)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/filemap.c (ffffffff8120d008)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81217e07)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff8121df2f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8121f26a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812243cf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff8124543f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff81258cfb)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125e8ef)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8126ee5f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff81289a8a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8129c2da)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8129ddbd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812a5b0f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812add4d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812b46e4)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fb761)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130a680)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8134e175)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff81358874)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff8139264f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff81409a9f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814c9ba7)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a5fc5)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/filemap.c (ffffffff81217b98)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812229f7)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff81228baf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81229f30)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8122f0af)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff81250453)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff812643b8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126a636)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127ad8e)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff81295cdf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a878a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812aaafc)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b28cd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812baa09)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c14b4)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81308931)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81317590)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8135afa5)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff813656a4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff8139f41f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff814151bf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814d5287)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b7775)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/filemap.c (ffffffff81226c58)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81231bd7)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff81237f2f)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8123931d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8123e4bf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffffffff8125fdd7)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/mprotect.c (ffffffff81273d78)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8127a014)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8128a967)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff812a5aea)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812b8aaa)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812bae4c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812c2b06)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812cb149)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812d1f74)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131a5b1)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8132917d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8136e725)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff81378d84)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/ext4/inode.c (ffffffff813b3abf)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/fuse/dev.c (ffffffff8142bf2c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814ede37)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d11e5)
Location: include/linux/page-flags.h:318
Inline: True
```
</details>
</li>
</ul>

## Differences
