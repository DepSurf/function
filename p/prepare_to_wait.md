# Function: <code>prepare_to_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void prepare_to_wait(wait_queue_head_t *q, wait_queue_t *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3420)
Location: kernel/sched/wait.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/cpu.c:cpu_hotplug_begin
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/sched/wait.c:__wait_on_bit
  - kernel/sched/wait.c:out_of_line_wait_on_atomic_t
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:wait_iff_congested
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:inode_dio_wait
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/mbcache.c:__mb_cache_entry_find
  - fs/mbcache.c:mb_cache_entry_get
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - block/blk-mq-tag.c:bt_get
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_do_sync
  - drivers/md/bitmap.c:bitmap_startwrite
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_memory
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810c3420-ffffffff810c349c: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void prepare_to_wait(wait_queue_head_t *q, wait_queue_t *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6da0)
Location: kernel/sched/wait.c:172
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_begin
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/sched/wait.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait.c:__wait_on_bit
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - block/blk-mq-tag.c:bt_get
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_make_request
  - drivers/md/bitmap.c:bitmap_startwrite
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810c6da0-ffffffff810c6e1c: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void prepare_to_wait(wait_queue_head_t *q, wait_queue_t *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccd80)
Location: kernel/sched/wait.c:172
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_begin
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/sched/wait.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait.c:__wait_on_bit
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_make_request
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810ccd80-ffffffff810ccdfd: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9650)
Location: kernel/sched/wait.c:174
Inline: False
Direct callers:
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - block/blk-mq-tag.c:blk_mq_get_tag
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_make_request
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810c9650-ffffffff810c96ce: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0e90)
Location: kernel/sched/wait.c:229
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - block/blk-mq-tag.c:blk_mq_get_tag
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810d0e90-ffffffff810d0f0e: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9440)
Location: kernel/sched/wait.c:223
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810d9440-ffffffff810d94bd: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2f40)
Location: kernel/sched/wait.c:225
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810e2f40-ffffffff810e2fbd: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9ae0)
Location: kernel/sched/wait.c:222
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810e9ae0-ffffffff810e9b5d: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f54b0)
Location: kernel/sched/wait.c:222
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810f54b0-ffffffff810f552d: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810febf0)
Location: kernel/sched/wait.c:239
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - fs/pipe.c:wait_for_partner
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - net/core/sock.c:sock_wait_for_wmem
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff810febf0-ffffffff810fec6d: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fdb40)
Location: kernel/sched/wait.c:254
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - fs/pipe.c:wait_for_partner
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_prepare_to_claim
  - fs/io_uring.c:io_sqpoll_wait_sq
  - fs/io_uring.c:__io_uring_task_cancel
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:kjournald2
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - net/core/sock.c:sock_wait_for_wmem
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff810fdb40-ffffffff810fdbe5: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ffe80)
Location: kernel/sched/wait.c:254
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:wait_for_partner
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_prepare_to_claim
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:io_uring_cancel_sqpoll
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:kjournald2
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff810ffe80-ffffffff810fff25: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111bf60)
Location: kernel/sched/wait.c:262
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:wait_for_partner
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:kjournald2
  - block/bdev.c:bd_prepare_to_claim
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff8111bf60-ffffffff8111bfef: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f22c5e)
Location: kernel/sched/wait.c:261
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:wait_for_partner
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:kjournald2
  - block/bdev.c:bd_prepare_to_claim
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_sq_thread
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff81142110-ffffffff811421b3: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820cd5c9)
Location: kernel/sched/wait.c:265
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:wait_for_partner
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:kjournald2
  - block/bdev.c:bd_prepare_to_claim
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/cancel.c:io_sync_cancel
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff8116d530-ffffffff8116d5d3: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82151a46)
Location: kernel/sched/wait.c:265
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:wait_for_partner
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:kjournald2
  - block/bdev.c:bd_prepare_to_claim
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff8117e140-ffffffff8117e1e6: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82234886)
Location: kernel/sched/wait.c:230
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/shmem.c:shmem_falloc_wait
  - mm/shmem.c:shmem_falloc_wait
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:wait_for_partner
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:kjournald2
  - block/bdev.c:bd_prepare_to_claim
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff8118bbe0-ffffffff8118bc86: prepare_to_wait (STB_GLOBAL)
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
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010158a20)
Location: kernel/sched/wait.c:222
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffff800010158a20-ffff800010158b38: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5b68)
Location: kernel/sched/wait.c:222
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_sq_thread
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
c03a5b68-c03a5c18: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001acba0)
Location: kernel/sched/wait.c:222
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
c0000000001acba0-c0000000001acc74: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000feab6)
Location: kernel/sched/wait.c:222
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffe0000feab6-ffffffe0000feb24: prepare_to_wait (STB_GLOBAL)
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
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee8b0)
Location: kernel/sched/wait.c:222
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810ee8b0-ffffffff810ee92d: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de940)
Location: kernel/sched/wait.c:222
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810de940-ffffffff810de9bd: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eb9e0)
Location: kernel/sched/wait.c:222
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810eb9e0-ffffffff810eba5d: prepare_to_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void prepare_to_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6a40)
Location: kernel/sched/wait.c:222
Inline: False
Direct callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - mm/mempool.c:mempool_alloc
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/dm.c:dm_wait_for_completion
  - net/core/sock.c:sock_alloc_send_pskb
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810f6a40-ffffffff810f6abd: prepare_to_wait (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_head *wq_head</code>
</li>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry *wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t *q</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_t *wait</code>
</li>
</ul>
</details>
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
