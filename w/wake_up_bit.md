# Function: <code>wake_up_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3740)
Location: kernel/sched/wait.c:480
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:blkdev_get
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_do_io
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/indirect.c:ext4_ind_direct_IO
  - fs/ext4/indirect.c:ext4_ind_direct_IO
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_reject_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810c3740-ffffffff810c376a: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c70d0)
Location: kernel/sched/wait.c:480
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:blkdev_get
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_do_io
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810c70d0-ffffffff810c70fa: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810cd0b0)
Location: kernel/sched/wait.c:477
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:blkdev_get
  - fs/direct-io.c:dio_complete
  - fs/iomap.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810cd0b0-ffffffff810cd0da: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810c9c70)
Location: kernel/sched/wait_bit.c:145
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:blkdev_get
  - fs/direct-io.c:dio_complete
  - fs/iomap.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810c9c70-ffffffff810c9cb4: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d1490)
Location: kernel/sched/wait_bit.c:145
Inline: False
Direct callers:
  - kernel/signal.c:task_clear_jobctl_trapping
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:inode_sync_complete
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:blkdev_get
  - fs/direct-io.c:dio_complete
  - fs/iomap.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810d1490-ffffffff810d14d4: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d9a60)
Location: kernel/sched/wait_bit.c:146
Inline: False
Direct callers:
  - kernel/signal.c:task_clear_jobctl_trapping
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:inode_sync_complete
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:blkdev_get
  - fs/direct-io.c:dio_complete
  - fs/iomap.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810d9a60-ffffffff810d9aa4: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810e3560)
Location: kernel/sched/wait_bit.c:146
Inline: False
Direct callers:
  - kernel/signal.c:task_clear_jobctl_trapping
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:inode_sync_complete
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:blkdev_get
  - fs/direct-io.c:dio_complete
  - fs/iomap.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810e3560-ffffffff810e35a4: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ea170)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:task_clear_jobctl_trapping
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:inode_sync_complete
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:bd_abort_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810ea170-ffffffff810ea1b4: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f5b40)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:task_clear_jobctl_trapping
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:inode_sync_complete
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:bd_abort_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810f5b40-ffffffff810f5b84: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ff310)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:task_participate_group_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:bd_finish_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/jbd2/commit.c:journal_finish_inode_data_buffers
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810ff310-ffffffff810ff3a5: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810fde10)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:task_participate_group_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_finish_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/jbd2/commit.c:journal_finish_inode_data_buffers
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810fde10-ffffffff810fdea5: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff811001f0)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:task_participate_group_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/block_dev.c:bd_abort_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff811001f0-ffffffff81100285: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff8111c290)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - block/bdev.c:truncate_bdev_range
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff8111c290-ffffffff8111c325: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141d10)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - block/bdev.c:truncate_bdev_range
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff81141d10-ffffffff81141db7: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116ca00)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - block/bdev.c:truncate_bdev_range
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff8116ca00-ffffffff8116caa7: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117d260)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - block/bdev.c:truncate_bdev_range
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff8117d260-ffffffff8117d307: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c650)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:task_participate_group_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:truncate_bdev_range
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff8118c650-ffffffff8118c717: wake_up_bit (STB_GLOBAL)
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
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff800010159108)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:unlock_buffer
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:bd_abort_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffff800010159108-ffff8000101591bc: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c03a6488)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_finish_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
c03a6488-c03a6528: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0000000001ad670)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:task_clear_jobctl_pending
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:bd_clear_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
c0000000001ad670-c0000000001ad6c0: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0000ff24a)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_stop
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
  - fs/block_dev.c:bd_abort_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffe0000ff24a-ffffffe0000ff2a6: wake_up_bit (STB_GLOBAL)
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
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810eef40)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:task_clear_jobctl_trapping
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:inode_sync_complete
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:bd_abort_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810eef40-ffffffff810eef84: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810defc0)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:task_clear_jobctl_trapping
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:inode_sync_complete
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:bd_abort_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810defc0-ffffffff810df004: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ec070)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:task_clear_jobctl_trapping
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:inode_sync_complete
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:bd_abort_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810ec070-ffffffff810ec0b4: wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wake_up_bit(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f70c0)
Location: kernel/sched/wait_bit.c:147
Inline: False
Direct callers:
  - kernel/signal.c:task_clear_jobctl_trapping
  - fs/dcache.c:d_instantiate_new
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:evict
  - fs/fs-writeback.c:inode_sync_complete
  - fs/buffer.c:unlock_buffer
  - fs/block_dev.c:bd_abort_claiming
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - drivers/md/dm.c:dm_internal_resume
```
**Symbols:**

```
ffffffff810f70c0-ffffffff810f7104: wake_up_bit (STB_GLOBAL)
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
