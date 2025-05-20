# Function: <code>blk_finish_plug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813bbb50)
Location: block/blk-core.c:3318
Inline: True
Direct callers:
  - mm/page-writeback.c:generic_writepages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/vmscan.c:shrink_lruvec
  - mm/madvise.c:SyS_madvise
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
ffffffff813bbb50-ffffffff813bbb8a: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ff960)
Location: block/blk-core.c:3290
Inline: True
Direct callers:
  - mm/page-writeback.c:generic_writepages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:SyS_madvise
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
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff813ff960-ffffffff813ff99a: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814193a0)
Location: block/blk-core.c:3290
Inline: True
Direct callers:
  - mm/page-writeback.c:generic_writepages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:SyS_madvise
  - mm/swap_state.c:swapin_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:do_io_submit
  - fs/iomap.c:iomap_dio_rw
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
ffffffff814193a0-ffffffff814193da: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814272d0)
Location: block/blk-core.c:3395
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:SyS_madvise
  - mm/swap_state.c:swapin_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:do_io_submit
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
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
ffffffff814272d0-ffffffff8142730a: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81452390)
Location: block/blk-core.c:3619
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/vmscan.c:shrink_node_memcg
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
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
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
ffffffff81452390-ffffffff814523ca: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814855d0)
Location: block/blk-core.c:3748
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/swap_state.c:swapin_readahead
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
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff814855d0-ffffffff81485604: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149fe80)
Location: block/blk-core.c:1790
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/swap_state.c:swapin_readahead
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
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff8149fe80-ffffffff8149feb4: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cded0)
Location: block/blk-core.c:1741
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
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
  - fs/io_uring.c:io_submit_state_end
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff814cded0-ffffffff814cdf04: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e71f0)
Location: block/blk-core.c:1782
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
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
  - fs/io_uring.c:io_submit_state_end
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff814e71f0-ffffffff814e7224: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81546160)
Location: block/blk-core.c:1873
Inline: True
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
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff81546160-ffffffff8154619a: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81561f90)
Location: block/blk-core.c:1768
Inline: True
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
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
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff81561f90-ffffffff81561fca: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8156a6f0)
Location: block/blk-core.c:1760
Inline: True
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
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
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff8156a6f0-ffffffff8156a72a: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cebf0)
Location: block/blk-core.c:1746
Inline: True
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
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
  - fs/io_uring.c:io_submit_sqes
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
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
ffffffff815cebf0-ffffffff815cec2a: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8167a0d0)
Location: block/blk-core.c:1227
Inline: True
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
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
  - fs/ext4/inode.c:ext4_writepages
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
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - io_uring/io_uring.c:io_submit_sqes
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff8167a0d0-ffffffff8167a11a: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81736580)
Location: block/blk-core.c:1165
Inline: True
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
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
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/fops.c:blkdev_write_iter
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:__blkdev_direct_IO
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - io_uring/io_uring.c:io_submit_sqes
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff81736580-ffffffff817365ca: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81772b90)
Location: block/blk-core.c:1162
Inline: True
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
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
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - io_uring/io_uring.c:io_submit_sqes
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff81772b90-ffffffff81772bda: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b4f30)
Location: block/blk-core.c:1197
Inline: True
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
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
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
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
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-cgroup.c:blkg_async_bio_workfn
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - io_uring/io_uring.c:io_submit_sqes
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:do_work
```
**Symbols:**

```
ffffffff817b4f30-ffffffff817b4f7a: blk_finish_plug (STB_GLOBAL)
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
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e4be0)
Location: block/blk-core.c:1782
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__arm64_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/io_uring.c:io_submit_state_end
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffff8000105e4be0-ffff8000105e4c2c: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0791df0)
Location: block/blk-core.c:1782
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
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
  - fs/io_uring.c:io_submit_state_end
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
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
c0791df0-c0791e44: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000778be0)
Location: block/blk-core.c:1782
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__se_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/io_uring.c:io_submit_state_end
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
c000000000778be0-c000000000778c4c: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000426240)
Location: block/blk-core.c:1782
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__se_sys_madvise
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - fs/fs-writeback.c:wb_writeback
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_writepages
  - fs/aio.c:__se_sys_io_submit
  - fs/io_uring.c:io_submit_state_end
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffe000426240-ffffffe000426280: blk_finish_plug (STB_GLOBAL)
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
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814df7d0)
Location: block/blk-core.c:1782
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
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
  - fs/io_uring.c:io_submit_state_end
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff814df7d0-ffffffff814df804: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d0170)
Location: block/blk-core.c:1782
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
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
  - fs/io_uring.c:io_submit_state_end
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff814d0170-ffffffff814d01a4: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db860)
Location: block/blk-core.c:1782
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
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
  - fs/io_uring.c:io_submit_state_end
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff814db860-ffffffff814db894: blk_finish_plug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_finish_plug(struct blk_plug *plug);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f46d0)
Location: block/blk-core.c:1782
Inline: True
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/readahead.c:read_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/madvise.c:__do_sys_madvise
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
  - fs/io_uring.c:io_submit_state_end
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__flush_batch
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
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
ffffffff814f46d0-ffffffff814f4704: blk_finish_plug (STB_GLOBAL)
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
