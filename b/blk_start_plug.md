# Function: <code>blk_start_plug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b46d0)
Location: block/blk-core.c:3156
Inline: False
Direct callers:
  - mm/page-writeback.c:generic_writepages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/vmscan.c:shrink_lruvec
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_write_iter
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:do_io_submit
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff813b46d0-ffffffff813b4716: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813f83c0)
Location: block/blk-core.c:3128
Inline: False
Direct callers:
  - mm/page-writeback.c:generic_writepages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:do_io_submit
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff813f83c0-ffffffff813f8406: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81411d90)
Location: block/blk-core.c:3128
Inline: False
Direct callers:
  - mm/page-writeback.c:generic_writepages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:do_io_submit
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff81411d90-ffffffff81411dd6: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8141fbd0)
Location: block/blk-core.c:3231
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:do_io_submit
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff8141fbd0-ffffffff8141fc16: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144a740)
Location: block/blk-core.c:3455
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:do_io_submit
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff8144a740-ffffffff8144a786: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147d9a0)
Location: block/blk-core.c:3592
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff8147d9a0-ffffffff8147d9e6: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149b090)
Location: block/blk-core.c:1707
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff8149b090-ffffffff8149b0d4: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814c91c0)
Location: block/blk-core.c:1658
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff814c91c0-ffffffff814c9204: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e23a0)
Location: block/blk-core.c:1699
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff814e23a0-ffffffff814e23e4: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81541060)
Location: block/blk-core.c:1790
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_lruvec
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:fsync_buffers_list
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff81541060-ffffffff815410a4: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155dcf0)
Location: block/blk-core.c:1684
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_lruvec
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:fsync_buffers_list
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/io_uring.c:io_init_req
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff8155dcf0-ffffffff8155dd31: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81566550)
Location: block/blk-core.c:1676
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_lruvec
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:fsync_buffers_list
  - fs/block_dev.c:blkdev_write_iter
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/io_uring.c:io_init_req
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff81566550-ffffffff81566591: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ca970)
Location: block/blk-core.c:1662
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_lruvec
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:fsync_buffers_list
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x64_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/io_uring.c:io_init_req
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/fops.c:blkdev_write_iter
  - block/fops.c:__blkdev_direct_IO
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff815ca970-ffffffff815ca9b1: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff816784a0)
Location: block/blk-core.c:1153
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_lruvec
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:fsync_buffers_list
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/fops.c:blkdev_write_iter
  - block/fops.c:__blkdev_direct_IO
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff816784a0-ffffffff8167850c: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81734990)
Location: block/blk-core.c:1091
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:fsync_buffers_list
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/fops.c:blkdev_write_iter
  - block/fops.c:__blkdev_direct_IO
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff81734990-ffffffff817349fc: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176e2c0)
Location: block/blk-core.c:1089
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:lru_gen_seq_write
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:fsync_buffers_list
  - fs/mpage.c:mpage_writepages
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff8176e2c0-ffffffff8176e323: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b04e0)
Location: block/blk-core.c:1124
Inline: False
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:fsync_buffers_list
  - fs/mpage.c:mpage_writepages
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/fops.c:blkdev_writepages
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff817b04e0-ffffffff817b0543: blk_start_plug (STB_GLOBAL)
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
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105df708)
Location: block/blk-core.c:1699
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffff8000105df708-ffff8000105df758: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078c4d4)
Location: block/blk-core.c:1699
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:fsync_buffers_list
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__se_sys_io_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
c078c4d4-c078c528: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007719d0)
Location: block/blk-core.c:1699
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
c0000000007719d0-c000000000771a10: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000422118)
Location: block/blk-core.c:1699
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__se_sys_io_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffe000422118-ffffffe000422156: blk_start_plug (STB_GLOBAL)
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
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814da980)
Location: block/blk-core.c:1699
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff814da980-ffffffff814da9c4: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb330)
Location: block/blk-core.c:1699
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff814cb330-ffffffff814cb374: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d6a10)
Location: block/blk-core.c:1699
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff814d6a10-ffffffff814d6a54: blk_start_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_start_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ef620)
Location: block/blk-core.c:1699
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff814ef620-ffffffff814ef664: blk_start_plug (STB_GLOBAL)
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
