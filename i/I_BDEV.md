# Function: <code>I_BDEV</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812470b0)
Location: fs/block_dev.c:47
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:iterate_bdevs
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:__generic_file_write_iter
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/readahead.c:file_ra_state_init
  - mm/readahead.c:force_page_cache_readahead
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapon
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:memory_failure
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inode
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff812470b0-ffffffff812470c2: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812721f0)
Location: fs/block_dev.c:48
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_writepages
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/fadvise.c:SyS_fadvise64
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:memory_failure
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8126f9b0-ffffffff8126f9c2: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81283f45)
Location: fs/block_dev.c:50
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_writepages
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/fadvise.c:SyS_fadvise64
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:memory_failure
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81282bb0-ffffffff81282bc2: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81293324)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_writepages
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/fadvise.c:SyS_fadvise64
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81290590-ffffffff812905a2: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b6124)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_writepages
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/fadvise.c:SyS_fadvise64
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff812b3250-ffffffff812b3262: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dde63)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff812daf70-ffffffff812daf82: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f3453)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:vfs_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_page
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_page
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff812f0440-ffffffff812f0452: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81314eca)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:vfs_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81311de0-ffffffff81311df2: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81327d6a)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81324d40-ffffffff81324d52: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81361aba)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/vmscan.c:pageout
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff8135e8f0-ffffffff8135e902: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136ed5a)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:bdev_alloc
  - fs/block_dev.c:bdev_free_inode
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:file_ra_state_init
  - mm/vmscan.c:pageout
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/io_uring.c:io_file_supports_async
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_cache_write_iter
  - block/ioctl.c:compat_blkdev_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_validate_file
```
**Symbols:**

```
ffffffff8136c1e0-ffffffff8136c1f2: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813756ca)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:bdev_alloc
  - fs/block_dev.c:bdev_free_inode
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:file_ra_state_init
  - mm/vmscan.c:pageout
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/io_uring.c:__io_file_supports_async
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_cache_write_iter
  - block/ioctl.c:compat_blkdev_ioctl
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:loop_validate_file
```
**Symbols:**

```
ffffffff81372b10-ffffffff81372b22: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c512c)
Location: block/bdev.c:42
Inline: True
Inline callers:
  - block/bdev.c:iterate_bdevs
  - block/bdev.c:bdev_alloc
  - block/bdev.c:bdev_free_inode
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_ra
  - mm/readahead.c:file_ra_state_init
  - mm/vmscan.c:pageout
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:hwpoison_user_mappings
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/io_uring.c:__io_file_supports_nowait
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_cache_write_iter
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_write_iter
  - block/fops.c:block_ioctl
  - block/fops.c:blkdev_close
  - block/fops.c:blkdev_fsync
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_iopoll
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:blkdev_get_block
  - block/ioctl.c:compat_blkdev_ioctl
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:loop_validate_file
```
**Symbols:**

```
ffffffff815c3a00-ffffffff815c3a12: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166f47b)
Location: block/bdev.c:42
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - io_uring/io_uring.c:io_file_get_flags
  - drivers/block/loop.c:loop_validate_file
```
**Symbols:**

```
ffffffff8166e310-ffffffff8166e328: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a80b)
Location: block/bdev.c:43
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_get_block
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - io_uring/io_uring.c:io_file_get_flags
  - drivers/block/loop.c:loop_validate_file
```
**Symbols:**

```
ffffffff817294c0-ffffffff817294d8: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817669a2)
Location: block/bdev.c:43
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - block/fops.c:blkdev_mmap
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
  - block/fops.c:blkdev_release
  - block/fops.c:blkdev_fsync
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
  - block/fops.c:blkdev_get_block
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_validate_file
```
**Symbols:**

```
ffffffff81765820-ffffffff81765838: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a85c2)
Location: block/bdev.c:46
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc
Direct callers:
  - block/fops.c:blkdev_mmap
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
  - block/fops.c:blkdev_fsync
  - block/fops.c:blkdev_get_block
  - block/fops.c:blkdev_iomap_begin
  - block/fops.c:__blkdev_direct_IO_async
  - block/fops.c:__blkdev_direct_IO_simple
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_validate_file
  - drivers/block/loop.c:__loop_update_dio
```
**Symbols:**

```
ffffffff817a7420-ffffffff817a7438: I_BDEV (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e2d3c)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffff8000103df230-ffff8000103df258: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05baeb0)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/vmscan.c:shrink_page_list
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c05b766c-c05b7688: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e8c2c)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c0000000004e3f50-c0000000004e3f60: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe00029919c)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffe0002960b4-ffffffe0002960d8: I_BDEV (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132034a)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8131d320-ffffffff8131d332: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81310eea)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8130dec0-ffffffff8130ded2: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131de1a)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8131adf0-ffffffff8131ae02: I_BDEV (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct block_device *I_BDEV(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132fb16)
Location: fs/block_dev.c:51
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:block_ioctl
  - fs/block_dev.c:blkdev_close
  - fs/block_dev.c:blkdev_fsync
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_get_block
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/fadvise.c:generic_fadvise
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:force_page_cache_readahead
  - mm/readahead.c:file_ra_state_init
  - mm/mmap.c:vma_wants_writenotify
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/buffer.c:init_page_buffers
  - fs/ext4/super.c:ext4_commit_super
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8132ca90-ffffffff8132caa2: I_BDEV (STB_GLOBAL)
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
