# Function: <code>PageWriteback</code>

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
In mm/filemap.c (ffffffff8118cadd)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81198b8a)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8119c25c)
Location: include/linux/page-flags.h:242
Inline: True
```
```
In mm/swap.c (ffffffff8119d181)
Location: include/linux/page-flags.h:242
Inline: True
```
```
In mm/truncate.c (ffffffff8119e9e8)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff811a0aaf)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811a94c5)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff811d49d7)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff811f1cf0)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (ffffffff811fd39c)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8120277c)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
```
```
In fs/fs-writeback.c (ffffffff8123a6ee)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/splice.c (ffffffff8123e7d8)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81242fde)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
```
```
In fs/mpage.c (ffffffff8124dd20)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff8125b685)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/proc/task_mmu.c (ffffffff81276a3d)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff81296065)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/page-io.c (ffffffff8129fe20)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff812d6afd)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/fuse/dev.c (ffffffff8130ea47)
Location: include/linux/page-flags.h:242
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff8119fac3)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811afd1f)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811b145c)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In mm/swap.c (ffffffff811b32c5)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In mm/truncate.c (ffffffff811b4489)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff811b89f7)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811c1144)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff811f3ada)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff81211da2)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memcontrol.c (ffffffff81220e02)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81227c26)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff8126241b)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/splice.c (ffffffff8126653a)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8126c918)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812764a3)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff81285125)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/proc/task_mmu.c (ffffffff812a4750)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff812c52bd)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/page-io.c (ffffffff812ce720)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff813067f3)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/fuse/dev.c (ffffffff81342e10)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff811afcf8)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811c03df)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811c1a8c)
Location: include/linux/page-flags.h:306
Inline: True
```
```
In mm/swap.c (ffffffff811c393b)
Location: include/linux/page-flags.h:306
Inline: True
```
```
In mm/truncate.c (ffffffff811c4b28)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff811c9027)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d174d)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff8120460d)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff8122400c)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memcontrol.c (ffffffff81233552)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8123a1c1)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff8127596a)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/splice.c (ffffffff8127a29a)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8127f978)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8128a17d)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff81299335)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/proc/task_mmu.c (ffffffff812ba0c9)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff812da96d)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/page-io.c (ffffffff812e4500)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff8131c7b3)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/fuse/dev.c (ffffffff81358c2f)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff811b6d82)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811c859b)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811c9d2c)
Location: include/linux/page-flags.h:306
Inline: True
```
```
In mm/swap.c (ffffffff811cbd46)
Location: include/linux/page-flags.h:306
Inline: True
```
```
In mm/truncate.c (ffffffff811ccd6d)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff811d1b04)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811da03a)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff8120fa51)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff8122f93a)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memcontrol.c (ffffffff8123ee2b)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81245d93)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff81282e58)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/splice.c (ffffffff8128779b)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8128d178)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81296ec3)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff812a701d)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/proc/task_mmu.c (ffffffff812c7818)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff812fe77d)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff81315332)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8131e1e0)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff8136d1e3)
Location: include/linux/page-flags.h:306
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff811ca81f)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811db09d)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811debec)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/swap.c (ffffffff811e0773)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/truncate.c (ffffffff811e20e9)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff811e6f94)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811efd68)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff8122b309)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff8124d43a)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8125478d)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff8125e9ab)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81265db7)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff812a59a8)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/splice.c (ffffffff812a9cbb)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812af998)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812b9fd5)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff812cacac)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/proc/task_mmu.c (ffffffff812eb418)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff81322f3a)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff81339914)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81342801)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff8139200d)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff811ec15d)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811fc54d)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8120035c)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/swap.c (ffffffff81201a29)
Location: include/linux/page-flags.h:314
Inline: True
```
```
In mm/truncate.c (ffffffff8120384a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff812084b5)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81211585)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff8124c771)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff81270e03)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8127860a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff81282bb5)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8128a20c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In fs/fs-writeback.c (ffffffff812cc57a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/splice.c (ffffffff812d170a)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812d781f)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812e2bd0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff812f3bf6)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/proc/task_mmu.c (ffffffff81318748)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff81350d13)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff81367e7e)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81370681)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff813c1034)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff811fe4be)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8120ee3d)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81212c5c)
Location: include/linux/page-flags.h:326
Inline: True
```
```
In mm/swap.c (ffffffff812142dc)
Location: include/linux/page-flags.h:326
Inline: True
```
```
In mm/truncate.c (ffffffff8121611a)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff8121b145)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81223563)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff81260cbb)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff81285415)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8128cc6a)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff81296d55)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8129f1b6)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In fs/fs-writeback.c (ffffffff812e1689)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/splice.c (ffffffff812e6b6a)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812ecc7f)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812f7832)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff813092a6)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap.c (ffffffff81325a6e)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/iomap.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff8132f65a)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff81368cb4)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff81380300)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81388b11)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff813da396)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff81213e3b)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122039e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81222644)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/swap.c (ffffffff812236f1)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/truncate.c (ffffffff8122614c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff8122add3)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffffffff8127a259)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff8129fa49)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812a797e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff812b2aa5)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff812ffe46)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130e431)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81317e7f)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff8132a860)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8134cc3e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff8135708c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff813920e0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff813a9409)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2c0e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff81405ef9)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8122164b)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122de4e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff812300f4)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/swap.c (ffffffff812310e8)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/truncate.c (ffffffff81233fad)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff81238ca3)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffffffff81289d39)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff812b0de9)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812b8e51)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff812c4540)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff8131264d)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81321451)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8132acf5)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff8133da00)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff81364f0e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff8136f65c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff813aaa70)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff813c2329)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cbc6e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff81420a55)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8124e2cb)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
```
```
In mm/page-writeback.c (ffffffff81259d7a)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8125d334)
Location: include/linux/page-flags.h:367
Inline: True
```
```
In mm/swap.c (ffffffff8125f892)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/truncate.c (ffffffff8126157d)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff812677e3)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:pageout
```
```
In mm/swapfile.c (ffffffff812bcba4)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff812e61d2)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812ed9f0)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff812fa433)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff8134bea9)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8135bb8d)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff81364911)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff81376f50)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff813ab7f8)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff813b6ebc)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff813f5d60)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff8140e9ec)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81417dcb)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff8146fb23)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff812586db)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
```
```
In mm/page-writeback.c (ffffffff812631b9)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff812676cd)
Location: include/linux/page-flags.h:375
Inline: True
```
```
In mm/swap.c (ffffffff81269e79)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/truncate.c (ffffffff8126b97d)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff8127224f)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page_prepare
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:pageout
```
```
In mm/swapfile.c (ffffffff812c86d4)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff812f1642)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812f90c4)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff81306345)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff81358ce4)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8136a12d)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff813718de)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff81384b5a)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff813bc1d2)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff813c855c)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff814086be)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff81421f39)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8142b8c5)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff8148a3ca)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8125cd5b)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:filemap_range_needs_writeback
```
```
In mm/page-writeback.c (ffffffff81267bdd)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_on_page_writeback_killable
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8126c2df)
Location: include/linux/page-flags.h:375
Inline: True
```
```
In mm/swap.c (ffffffff8126ee28)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/truncate.c (ffffffff812710d4)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff8127549f)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/swapfile.c (ffffffff812cf091)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff812f7942)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812ff6d2)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff8130c810)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81314da4)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff8135f844)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81370d4d)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff81378bae)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff8138b647)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff813c36b0)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff813cf59d)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff8140ee4f)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff814285f9)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff814324e5)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff8148ff1f)
Location: include/linux/page-flags.h:375
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff81298ccb)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:filemap_range_needs_writeback
```
```
In mm/page-writeback.c (ffffffff812a464a)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_on_page_writeback_killable
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff812a8fef)
Location: include/linux/page-flags.h:389
Inline: True
```
```
In mm/swap.c (ffffffff812abe90)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/truncate.c (ffffffff812ae614)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff812b3070)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/swapfile.c (ffffffff81314631)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff81341fb2)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff813492e2)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8134e5f5)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81357a10)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81360e44)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff813ae1ac)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff813bf99d)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff813c5588)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff813d8bfa)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff81413d18)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff8142097d)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff81461b7a)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff8147c339)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81485da5)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff814e798c)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff812f03da)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/filemap.c:filemap_range_has_writeback
```
```
In mm/page-writeback.c (ffffffff812fd2fd)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff81305d47)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/compaction.c (ffffffff8133127c)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff81344350)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swapfile.c (ffffffff8137fa82)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_free_swap
```
```
In mm/migrate.c (ffffffff813b3f7c)
Location: include/linux/page-flags.h:539
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bf645)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c507a)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff813dc47a)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81447492)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8144c5f8)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff814646b8)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/proc/task_mmu.c (ffffffff814996c1)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff814e1eee)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/move_extent.c (ffffffff814feaa7)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8150935e)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff81575deb)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/page-writeback.c (ffffffff81367c1d)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/compaction.c (ffffffff813a7f41)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/khugepaged.c (ffffffff81449d37)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff81463482)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff814d60bd)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff814daa7d)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/proc/task_mmu.c (ffffffff8152d87b)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff8157b23c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/move_extent.c (ffffffff815992f7)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815a3f3e)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In mm/khugepaged.c (ffffffff8147f921)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff814990d2)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc/task_mmu.c (ffffffff81565cab)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/khugepaged.c (ffffffff814adc23)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff814c87c4)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc/task_mmu.c (ffffffff8159dc8b)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffff8000102ae214)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/page-writeback.c (ffff8000102bcdc0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffff8000102bf95c)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/swap.c (ffff8000102c1fbc)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/truncate.c (ffff8000102c4650)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffff8000102c9ae8)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffff800010324ce8)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffff800010351328)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffff800010359560)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffff800010367190)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffff8000103c7690)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffff8000103d87cc)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffff8000103e6304)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffff8000103fcf78)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffff80001042a990)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffff800010438d50)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffff80001047e044)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffff800010499d48)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a3e00)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffff800010503654)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (c04db788)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/page-writeback.c (c04e9260)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (c04eb410)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/swap.c (c04ed190)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/truncate.c (c04eefa0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (c04f39e4)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (c053c788)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (c05528bc)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/memcontrol.c (c055890c)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In fs/fs-writeback.c (c05a45bc)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (c05b3208)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (c05be05c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (c05cf7d4)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (c05f4c1c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/ext4/inode.c (c06409bc)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (c065b558)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0665ca8)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (c06bfce0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (c000000000362f98)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
```
```
In mm/page-writeback.c (c000000000375854)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (c000000000378804)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/swap.c (c00000000037a0dc)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/truncate.c (c00000000037eb40)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (c000000000386290)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (c0000000003fadf0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (c0000000004376b0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (c000000000442a8c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (c0000000004545ec)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (c0000000004c916c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (c0000000004deaac)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (c0000000004ec6f0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (c000000000504de0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (c00000000053c304)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (c00000000054c634)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (c0000000005a2b9c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (c0000000005c3fd0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d0eec)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (c0000000006481d4)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffe0001d4e44)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/page-writeback.c (ffffffe0001dfc36)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffe0001e19b8)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/swap.c (ffffffe0001e337a)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/truncate.c (ffffffe0001e4f44)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffe0001e8e0a)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffffffe000225378)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffe00023fc6c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/memcontrol.c (ffffffe0002453b6)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In fs/fs-writeback.c (ffffffe0002862f4)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffe000292e70)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffe00029b678)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffe0002aaf0e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8b08)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/ext4/inode.c (ffffffe000307ce4)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffe00031d512)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe000325356)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffe000370470)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff81219c9b)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122649e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81228744)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/swap.c (ffffffff81229738)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/truncate.c (ffffffff8122c5fd)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff812312f3)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffffffff81282319)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff812a93c9)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812b1431)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff812bcb20)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff8130ac2d)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81319a31)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff813232d5)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff81335fe0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8135d4ee)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff81367c3c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff813a3050)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff813ba909)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c424e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff81419035)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8120ceab)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/page-writeback.c (ffffffff8121960e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8121b884)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/swap.c (ffffffff8121c858)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/truncate.c (ffffffff8121f6dd)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff812243b3)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffffffff81273e39)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff8129ad29)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812a2801)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff812adc80)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff812fb84d)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130a5f1)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81313e75)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff81326cd0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8134e18e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff813588dc)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff81393ae0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff813ab399)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b4cce)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff81409ab5)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff81217a3b)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122423e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff812264e4)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/swap.c (ffffffff812274d8)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/truncate.c (ffffffff8122a39d)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff8122f093)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffffffff81280129)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff812a71d9)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812af241)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff812ba930)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff81308a1d)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81317501)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81320da5)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff81333ab0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8135afbe)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff8136570c)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff813a08b0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff813b8169)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c16de)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff814151d5)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff81226afb)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/page-writeback.c (ffffffff8123350e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8123580b)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/swap.c (ffffffff81236808)
Location: include/linux/page-flags.h:359
Inline: True
```
```
In mm/truncate.c (ffffffff8123978d)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff8123e4a3)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffffffff8128fe18)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/migrate.c (ffffffff812b74e4)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812bf591)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff812cb070)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff8131a69d)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff813290f0)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81332ac5)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/aio.c (ffffffff81345b1e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8136e73e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
```
In fs/proc/task_mmu.c (ffffffff81378dec)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/ext4/inode.c (ffffffff813b50de)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff813cce69)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d683e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/fuse/dev.c (ffffffff8142bf42)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
</details>
</li>
</ul>

## Differences
