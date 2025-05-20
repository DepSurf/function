# Function: <code>waitqueue_active</code>

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
In arch/x86/kernel/kvm.c (ffffffff81063bb9)
Location: include/linux/wait.h:105
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/wait.h:105
Inline: True
```
```
In kernel/signal.c (ffffffff8108e573)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:send_sigqueue
```
```
In kernel/workqueue.c (0)
Location: include/linux/wait.h:105
Inline: True
```
```
In kernel/sched/wait.c (ffffffff810c35fd)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - kernel/sched/wait.c:abort_exclusive_wait
  - kernel/sched/wait.c:__wake_up_bit
```
```
In kernel/printk/printk.c (0)
Location: include/linux/wait.h:105
Inline: True
```
```
In kernel/relay.c (ffffffff8113c58a)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff81186ecf)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/vmscan.c (ffffffff811a0457)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:pfmemalloc_watermark_ok
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/backing-dev.c (ffffffff811ae12b)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In fs/splice.c (ffffffff8123d7a0)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_readers
  - fs/splice.c:splice_to_pipe
  - fs/splice.c:wakeup_pipe_writers
```
```
In fs/eventpoll.c (ffffffff81254dc6)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_scan_ready_list
  - fs/eventpoll.c:ep_scan_ready_list
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/signalfd.c (ffffffff81257695)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff81258faa)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_signal
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff81259ab7)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/aio.c (ffffffff8125c41c)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/locks.c (ffffffff8125f825)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_free_lock
```
```
In fs/fuse/dev.c (ffffffff8130fba1)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:fuse_dev_splice_read
```
```
In fs/fuse/file.c (ffffffff81315365)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-core.c (ffffffff813b5dca)
Location: include/linux/wait.h:105
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff813c6cd0)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_clear_tag
```
```
In drivers/tty/tty_io.c (ffffffff814e31cd)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/n_tty.c (ffffffff814e43d5)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_fasync
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/wait.h:105
Inline: True
```
```
In drivers/net/tun.c (ffffffff815ee1bb)
Location: include/linux/wait.h:105
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/wait.h:105
Inline: True
```
```
In net/core/sock.c (ffffffff81700ef4)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
  - net/core/sock.c:release_sock
```
```
In net/core/stream.c (ffffffff8170e2e4)
Location: include/linux/wait.h:105
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff817be815)
Location: include/linux/wait.h:105
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
In kernel/cpu.c (ffffffff81083ffa)
Location: include/linux/wait.h:135
Inline: True
```
```
In kernel/signal.c (ffffffff81092e46)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff8109e76a)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait.c (ffffffff810c6fcc)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_bit
  - kernel/sched/wait.c:abort_exclusive_wait
```
```
In kernel/printk/printk.c (ffffffff810dcca1)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/relay.c (ffffffff81144ada)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff811993e3)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/vmscan.c (ffffffff811b9106)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:pfmemalloc_watermark_ok
```
```
In mm/backing-dev.c (ffffffff811c7553)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff811d2489)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff81265af0)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:splice_to_pipe
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff8127f0b8)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff8127ff95)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff81281eb8)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff81282a60)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff812854f0)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/dax.c (ffffffff81287793)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_mapping_entry_waiter
```
```
In fs/locks.c (ffffffff8128b8a5)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/locks.c:locks_free_lock
```
```
In fs/fuse/dev.c (ffffffff81345448)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff81349bb5)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-core.c (ffffffff813fac1a)
Location: include/linux/wait.h:135
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8140aed0)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_clear_tag
```
```
In drivers/tty/tty_io.c (ffffffff815331fc)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff815ae180)
Location: include/linux/wait.h:135
Inline: True
```
```
In drivers/net/tun.c (ffffffff8164d2aa)
Location: include/linux/wait.h:135
Inline: True
```
```
In drivers/md/md.c (ffffffff820e87a8)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In net/core/sock.c (ffffffff81769559)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81775a19)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8182bd47)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In kernel/cpu.c (ffffffff8108852a)
Location: include/linux/wait.h:135
Inline: True
```
```
In kernel/signal.c (ffffffff81097dd6)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810a3347)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait.c (ffffffff810ccf3c)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff810e33eb)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/relay.c (ffffffff8114e967)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff811a8dd3)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff811af351)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff811c9746)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:pfmemalloc_watermark_ok
```
```
In mm/backing-dev.c (ffffffff811d7673)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff811e2349)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff812791e0)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff81292c48)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff81293b05)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff812959e8)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff81296580)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff81298aa2)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/dax.c (ffffffff8129b368)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_mapping_entry_waiter
```
```
In fs/locks.c (ffffffff812a06a5)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/locks.c:locks_free_lock
```
```
In fs/fuse/dev.c (ffffffff81359d0d)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff8135f4c5)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-core.c (ffffffff8141457a)
Location: include/linux/wait.h:135
Inline: True
```
```
In block/blk-wbt.c (ffffffff8144a978)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff81482514)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/tty/tty_io.c (ffffffff8155f92c)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff815dcf80)
Location: include/linux/wait.h:135
Inline: True
```
```
In drivers/net/tun.c (ffffffff8167efea)
Location: include/linux/wait.h:135
Inline: True
```
```
In drivers/md/md.c (ffffffff821ce4ae)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In net/core/sock.c (ffffffff81796469)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff817a2fe9)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8185d773)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In kernel/signal.c (ffffffff810950e5)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810a067a)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810c9c1c)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff810e29fe)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/relay.c (ffffffff81151007)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff811b063d)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff811b6291)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff811d2219)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/backing-dev.c (ffffffff811e07cd)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff811ec169)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff81286750)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff8129fe7d)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff812a0df5)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff812a2b88)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff812a3db3)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff812a6bb3)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/dax.c (ffffffff812a93e8)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_mapping_entry_waiter
```
```
In fs/locks.c (ffffffff812af4e5)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - fs/locks.c:locks_free_lock
```
```
In fs/fuse/dev.c (ffffffff8136e4da)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff81374053)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-core.c (ffffffff8142219a)
Location: include/linux/wait.h:122
Inline: True
```
```
In block/blk-wbt.c (ffffffff81458c18)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff8148ba80)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/tty/tty_io.c (ffffffff8157325b)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff815f1934)
Location: include/linux/wait.h:122
Inline: True
```
```
In drivers/net/tun.c (ffffffff816942ba)
Location: include/linux/wait.h:122
Inline: True
```
```
In drivers/md/md.c (ffffffff822c36b8)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In net/core/sock.c (ffffffff817b4629)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff817c1135)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81881f43)
Location: include/linux/wait.h:122
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In kernel/signal.c (ffffffff8109bf85)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810a6c1c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810d143c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff810ea89a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/relay.c (ffffffff8115d82a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/bpf/sockmap.c (ffffffff811b1723)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_state_change
```
```
In kernel/events/uprobes.c (ffffffff811c414d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff811ca5a1)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff811e76b9)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/backing-dev.c (ffffffff811f67c1)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff812024dc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff812a9213)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff812c3278)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff812c4145)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff812c5ecc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff812c7236)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff812ca1a6)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/dax.c (ffffffff812cc8b8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_mapping_entry_waiter
```
```
In fs/locks.c (ffffffff812d2f66)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_free_lock
```
```
In fs/fuse/dev.c (ffffffff813930f2)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff81398dc6)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-core.c (ffffffff8144d01a)
Location: include/linux/wait.h:124
Inline: True
```
```
In block/blk-wbt.c (ffffffff81484978)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff814c7b8b)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/tty/tty_io.c (ffffffff815d8cde)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff81658f24)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (ffffffff816fe2aa)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffffffff828d68f7)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In net/core/sock.c (ffffffff8182c88c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff8183ab5b)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81902ff6)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In kernel/signal.c (ffffffff810a0355)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810ad8a8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810d9a0f)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff810f46d9)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (ffffffff8116c79a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff811e45bc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff811eb651)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff81208c41)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff81217aa1)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff8122388c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff812cfd53)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff812ead59)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff812ed735)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff812ef178)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff812f01b2)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff812f4110)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/dax.c (ffffffff812f6c78)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_mapping_entry_waiter
```
```
In fs/locks.c (ffffffff812fd855)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_free_lock
```
```
In fs/fuse/dev.c (ffffffff813c18e5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff813c8f1e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-core.c (ffffffff8148028a)
Location: include/linux/wait.h:124
Inline: True
```
```
In block/blk-wbt.c (ffffffff814b9772)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff814f88cb)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff81611442)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (ffffffff8164731a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (ffffffff81694b54)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (ffffffff8173c3db)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffffffff8290825c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In net/core/sock.c (ffffffff818769ec)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff8188529a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8195b2ca)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In kernel/signal.c (ffffffff810a8697)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810b6b98)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810e350f)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff810ffe69)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (ffffffff8117a4ba)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff811f4b1c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff811fc191)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff8121b8e0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff8122a9b1)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff812368ec)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff812e5163)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff812ffb82)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff813020c5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff81303b08)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff813050f2)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff81308d67)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/dax.c (ffffffff8130bd2f)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff813130e5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_free_lock
```
```
In fs/fuse/dev.c (ffffffff813daf80)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff813e2ee4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff814bdb02)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff814ccc8a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff8150cafe)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff8162e1b2)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (ffffffff816657ba)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (ffffffff816b51e4)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (ffffffff8175fd1b)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffffffff82ae008a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff818335fa)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff818419e3)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff8189887c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff818a59cf)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8198fb0a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In kernel/signal.c (ffffffff810abc7b)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810bcff4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810ea127)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff81108625)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (ffffffff811872fa)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff8120c981)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff812138bd)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff8122b574)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff8123a61d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff81247e27)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff81303963)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff8132189e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff81323635)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff813250d8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff81326e21)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff8132b7b8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8132d235)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (ffffffff8133324c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff8133a8e5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffffffff81406b6f)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff8140e9e1)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff814ec1a7)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff814fb6fe)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff8153b276)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff81661d7f)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (ffffffff8169b3ed)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (ffffffff816eed84)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (ffffffff8179d42b)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffffffff82b050b6)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff81875536)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff81884804)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff818e2e1c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff818f0cdf)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff819fb267)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In kernel/signal.c (ffffffff810b228b)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810c2c74)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810f5af7)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff81114a05)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (ffffffff8119321a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff81219c71)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff8122108d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff81239444)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff8124892d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff81256287)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff813169e3)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff8133568e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff81336395)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff81337e68)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff81339bb1)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff8133e608)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff81340095)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (ffffffff81346dfc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff81352e15)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffffffff81420044)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81427931)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff815055f7)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff81513761)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff8151964e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff8155c096)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff816843ef)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (ffffffff816be10d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (ffffffff81712fa4)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (ffffffff817c0ecb)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffffffff82b14022)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff818a72e6)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff818b66f4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff81914ffc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81922c54)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81a31ef7)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In kernel/signal.c (ffffffff810bab31)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810ca824)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810ff2d3)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff811202c7)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/relay.c (ffffffff811a7d7a)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff81246054)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff8124ecab)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff8126a9ca)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff812768ad)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff8128491e)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff8135111b)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/eventpoll.c (ffffffff8136deb7)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff81370065)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff81371b98)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff81372f04)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
  - fs/userfaultfd.c:userfaultfd_wake
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_poll
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/aio.c (ffffffff81375833)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/io_uring.c (ffffffff8137b170)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_req_issued
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (ffffffff8138cb7e)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff813995c5)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffffffff8146ed84)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81477858)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff81565fb7)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff81574abe)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff8157a297)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815e5b16)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff81736c13)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff817cebf4)
Location: include/linux/wait.h:125
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188a72b)
Location: include/linux/wait.h:125
Inline: True
```
```
In drivers/md/md.c (ffffffff82f25ab0)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff81977012)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - drivers/md/dm.c:end_io_acct
```
```
In net/core/sock.c (ffffffff819e811c)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff819f66d0)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81b260c7)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81baf912)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/signal.c (ffffffff810b5dfd)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810c5954)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810fddd3)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff8111b269)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/seccomp.c (ffffffff811a3734)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff811a538a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff812506c4)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff8125906b)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff81275426)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff812811b1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
```
```
In mm/compaction.c (ffffffff8128ec3e)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff8135e38b)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/eventpoll.c (ffffffff8137c872)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff8137ddd5)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff8137f99c)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff81380d64)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
  - fs/userfaultfd.c:userfaultfd_wake
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_poll
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/aio.c (ffffffff8138370a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/io_uring.c (ffffffff81399c81)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sq_thread
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_cqring_ev_posted_iopoll
  - fs/io_uring.c:io_cqring_ev_posted_iopoll
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
```
```
In fs/dax.c (ffffffff8139e30e)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff813ab0a5)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffffffff8148950c)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81492cda)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff81580f37)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff815917c8)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff81597185)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81609ed6)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff817524b3)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff817e2d40)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/net/tun.c (ffffffff8189885b)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/md/md.c (ffffffff8321e017)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff8197bdb2)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/dm.c:end_io_acct
```
```
In net/core/sock.c (ffffffff819e7d8c)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff819f62b1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81b34cb6)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81bc30c5)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/signal.c (ffffffff810b79fd)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810c7273)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff811001b3)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff8111b869)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/seccomp.c (ffffffff811a4354)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff811a5f5a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff81254b54)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff8125d48b)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff8127a746)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff812862e1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
```
```
In mm/compaction.c (ffffffff812942be)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff81365dc3)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/eventpoll.c (ffffffff81383ac0)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/signalfd.c (ffffffff81384a55)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff8138661b)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff8138860c)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_poll
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/aio.c (ffffffff8138c3f7)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/io_uring.c (ffffffff8139e664)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
```
```
In fs/io-wq.c (ffffffff813a2ea1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/dax.c (ffffffff813a53cf)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff813b2575)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffffffff8148ed9c)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81497c4a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff81588a93)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff81598618)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff8159df45)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815edc36)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff81736603)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff817c7100)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/net/tun.c (ffffffff8187af9e)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/md/md.c (ffffffff83451ff4)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff819608d4)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In net/core/sock.c (ffffffff819cdd5c)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff819dc43d)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81b22896)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81bb37d1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/signal.c (ffffffff810c9e7d)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810d9fa2)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait.c (ffffffff8111bb95)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_pollfree
```
```
In kernel/sched/wait_bit.c (ffffffff8111c253)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff8113be2f)
Location: include/linux/wait.h:127
Inline: True
```
```
In kernel/seccomp.c (ffffffff811cda44)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff811cf6ea)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff81290594)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff812993db)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff812b87a6)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff812c5574)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
```
```
In mm/compaction.c (ffffffff812d48ee)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff813b46b3)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/eventpoll.c (ffffffff813d0d60)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/signalfd.c (ffffffff813d1ce5)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff813d38eb)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff813d594d)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_poll
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/aio.c (ffffffff813d99b7)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/io_uring.c (ffffffff813ee9f4)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
```
```
In fs/io-wq.c (ffffffff813f248d)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/dax.c (ffffffff813f4e3f)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff81402435)
Location: include/linux/wait.h:127
Inline: True
```
```
In fs/fuse/dev.c (ffffffff814e67d4)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff814ef85b)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff815ee7a7)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff815ffddd)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff8160662e)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff8165acf8)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff817b6fc3)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff818514dd)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/net/tun.c (ffffffff8190c49e)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/md/md.c (ffffffff8354569f)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff81a0a2cc)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_dec_pending
```
```
In net/core/sock.c (ffffffff81a7d53c)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81a8c67d)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81bea79a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81c81f05)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/signal.c (ffffffff810e195b)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff810f336d)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/build_utility.c (ffffffff8113c375)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wake_up_pollfree
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff8115bcf6)
Location: include/linux/wait.h:127
Inline: True
```
```
In kernel/seccomp.c (ffffffff812017f6)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff8120395a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff812e53a2)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff812ef2ec)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/filemap.c:folio_wake_bit
```
```
In mm/vmscan.c (ffffffff813141e3)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff8133391d)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:isolate_migratepages_block
```
```
In fs/splice.c (ffffffff81439ab8)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/eventpoll.c (ffffffff81459ed6)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/signalfd.c (ffffffff8145af25)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff8145cdc9)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff8145fb46)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_poll
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/aio.c (ffffffff814618aa)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/dax.c (ffffffff81468461)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff81476dd5)
Location: include/linux/wait.h:127
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8157456b)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8157ccb5)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff8169f077)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff816b2522)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff816ba398)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff816d8a7a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_poll_task_func
  - io_uring/io_uring.c:io_poll_check_events
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_msg_ring
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In io_uring/io-wq.c (ffffffff816daed3)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In lib/sbitmap.c (ffffffff81773109)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff818f339d)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff819977ad)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/net/tun.c (ffffffff81a600ae)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/md/md.c (ffffffff83723bce)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff81b71fd6)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_complete
```
```
In net/core/sock.c (ffffffff81bf0bbc)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
  - net/core/sock.c:sock_wfree
```
```
In net/core/stream.c (ffffffff81c01f00)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81d82b4f)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81e27c1a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/signal.c (ffffffff81101c7b)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff811149dd)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/build_utility.c (ffffffff8117b9e2)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff8118e746)
Location: include/linux/wait.h:127
Inline: True
```
```
In kernel/seccomp.c (ffffffff812495b6)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff8124ba5a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff8134ed52)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff81359e0c)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/filemap.c:folio_wake_bit
```
```
In mm/vmscan.c (ffffffff813882a3)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:try_to_inc_max_seq
  - mm/vmscan.c:walk_pud_range
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff813aa64d)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:isolate_migratepages_block
```
```
In fs/splice.c (ffffffff814c7de8)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/eventpoll.c (ffffffff814e9346)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/signalfd.c (ffffffff814ea505)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff814ec5d1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal_mask
```
```
In fs/userfaultfd.c (ffffffff814efc10)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_poll
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/aio.c (ffffffff814f1a27)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/dax.c (ffffffff814f8ed1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff81509615)
Location: include/linux/wait.h:127
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81619e65)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81622805)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff8175d937)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff81771a67)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff8177a918)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff8178c281)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_cq_unlock_post
```
```
In io_uring/sqpoll.c (ffffffff8179a5c9)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/rw.c (ffffffff817a4e90)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
```
```
In io_uring/io-wq.c (ffffffff817a6fc1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In lib/sbitmap.c (ffffffff818a3562)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff81a4baf4)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff81b08230)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/net/tun.c (ffffffff81beb82e)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/md/md.c (ffffffff842b2a77)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff81d0e960)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_io_complete
```
```
In net/core/sock.c (ffffffff81d9d28c)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
  - net/core/sock.c:sock_wfree
```
```
In net/core/stream.c (ffffffff81db12e0)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81f5015f)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81fffb4a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/signal.c (ffffffff8110de93)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff8112096d)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/build_utility.c (ffffffff811773b5)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wake_up_pollfree
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff811a00a6)
Location: include/linux/wait.h:127
Inline: True
```
```
In kernel/seccomp.c (ffffffff812609a6)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff81262cda)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff8137fef2)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff8138b74c)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/filemap.c:folio_wake_bit
```
```
In mm/vmscan.c (ffffffff813ba583)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff813dd76e)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:isolate_migratepages_block
```
```
In fs/splice.c (ffffffff814fddce)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/eventpoll.c (ffffffff815200f1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/signalfd.c (ffffffff815212a5)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff815230c5)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal_mask
```
```
In fs/userfaultfd.c (ffffffff81526937)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_poll
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/aio.c (ffffffff815287a1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/dax.c (ffffffff8152f5f1)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff81540bd5)
Location: include/linux/wait.h:127
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81651fab)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8165ac45)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e277)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - crypto/jitterentropy-testing.c:jent_raw_hires_entropy_store
```
```
In block/blk-rq-qos.c (ffffffff8179c697)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff817b0d32)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff817ba86a)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff817cd4e0)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_cq_unlock_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
```
In io_uring/sqpoll.c (ffffffff817db61f)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/rw.c (ffffffff817e5e52)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
```
```
In io_uring/io-wq.c (ffffffff817e80f4)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In lib/sbitmap.c (ffffffff818e58b2)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff81a95d1e)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff81b56260)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/net/tun.c (ffffffff81c43cde)
Location: include/linux/wait.h:127
Inline: True
```
```
In drivers/md/md.c (ffffffff83af5787)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff81d76d0f)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_io_complete
```
```
In net/core/sock.c (ffffffff81e0badc)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
  - net/core/sock.c:sock_wfree
```
```
In net/core/stream.c (ffffffff81e217f0)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81faf9bb)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff8207bae8)
Location: include/linux/wait.h:127
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/signal.c (ffffffff811177f3)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff8112a21d)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/build_utility.c (ffffffff8118c1cd)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wake_up_pollfree
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff811af0a6)
Location: include/linux/wait.h:125
Inline: True
```
```
In kernel/seccomp.c (ffffffff8127ab76)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff8127cefa)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff813a9172)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff813b5236)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - mm/filemap.c:folio_wake_bit
```
```
In mm/vmscan.c (ffffffff813e36a3)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff814076ce)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:isolate_migratepages_block
```
```
In fs/splice.c (ffffffff81532a49)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/eventpoll.c (ffffffff81554701)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/signalfd.c (ffffffff815558e5)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff815577c5)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal_mask
```
```
In fs/userfaultfd.c (ffffffff8155aefc)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_poll
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/aio.c (ffffffff8155d83d)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/dax.c (ffffffff815644d1)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff815760b5)
Location: include/linux/wait.h:125
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8168b5bb)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81694915)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff817e00f7)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff817f4b42)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff817fefda)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff8181555c)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_fill_cqe_req_aux
  - io_uring/io_uring.c:io_cq_unlock_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
```
In io_uring/sqpoll.c (ffffffff8181f96a)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/register.c (ffffffff8182ba17)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
  - io_uring/register.c:__io_uring_register
```
```
In io_uring/io-wq.c (ffffffff8182dea9)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In lib/sbitmap.c (ffffffff8192c8b2)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff81ae877e)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/base/power/wakeup.c (ffffffff81bae820)
Location: include/linux/wait.h:125
Inline: True
```
```
In drivers/net/tun.c (ffffffff81cf959e)
Location: include/linux/wait.h:125
Inline: True
```
```
In drivers/md/md.c (ffffffff83d51547)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff81e2df3f)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_io_complete
```
```
In net/core/sock.c (ffffffff81ec8508)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
  - net/core/sock.c:sock_wfree
```
```
In net/core/stream.c (ffffffff81edf710)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8207cfbb)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff82150ee8)
Location: include/linux/wait.h:125
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/signal.c (ffff80001010dfa4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffff80001011f628)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffff800010159220)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
```
In kernel/printk/printk.c (ffff8000101759d8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (ffff80001020aef8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffff8000102a5454)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffff8000102af158)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffff8000102ca314)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffff8000102ddb18)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffff8000102ed8c0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffff8000103cd364)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffff8000103f254c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffff8000103f4160)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffff8000103f64e0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffff8000103f8a9c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffff8000103fb5e8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/io_uring.c (ffff800010400128)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (ffff8000104071d8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffff800010414890)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffff800010502978)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffff80001050c5cc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffff800010607758)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffff800010617c98)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffff8000106210cc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffff8000106698b0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffff8000108518b0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (ffff8000108aecc8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (ffff800010903acc)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (ffff8000109dbe54)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffff8000114bade8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffff800010afe5b4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffff800010b0e70c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffff800010bade64)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffff800010bbd8d8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffff800010cf2dcc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In kernel/signal.c (c03662c8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (c0373a70)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (c03a6588)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
```
In kernel/printk/printk.c (c03c7c2c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (c0449b4c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (c04d4388)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (c04db1d8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (c04f4164)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (c050311c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (c051186c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In mm/highmem.c (c0515e00)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/highmem.c:kunmap_high
```
```
In fs/splice.c (c05a8ed0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (c05c803c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (c05c8f60)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (c05cae48)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (c05ccabc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/aio.c (c05ce610)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/io_uring.c (c05d1f90)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (c05e1378)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (c06be920)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (c06c5edc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (c07b2934)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (c07c2fec)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (c07c88ac)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (c08126b0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (c095c404)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (c09aabcc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (c09ee070)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (c0ac2660)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (c15c10e8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (c0bdccf8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (c0becb24)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (c0ccb93c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (c0cd9a20)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (c0df9184)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In kernel/signal.c (c0000000001553e8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (c000000000169e90)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (c0000000001ad60c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (c0000000001cf3d0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (c000000000288014)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (c0000000003578a4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (c000000000362bbc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (c000000000386c78)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (c00000000039d2b8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (c0000000003b1734)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (c0000000004cf178)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (c0000000004fa6c8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (c0000000004fbf30)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (c0000000004fe6b0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (c0000000004ffea8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/aio.c (c0000000005076b8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (c000000000509650)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (c000000000512500)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (c000000000521e98)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (c000000000646940)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (c00000000064ffc0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (c0000000007a4388)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (c0000000007b73b4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (c0000000007c0f24)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (c00000000081f444)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (c0000000008ef210)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (c0000000009471c0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (c0000000009a2560)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (c000000000a9dea0)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (c0000000013cea50)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (c000000000beacb8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (c000000000c016e8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (c000000000c83854)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (c000000000c96c74)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (c000000000e16ea4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In kernel/signal.c (ffffffe0000cef84)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffe0000d9a98)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffe0000ff210)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffe000111196)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (ffffffe00016c842)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In mm/filemap.c (ffffffe0001d4928)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffe0001e9428)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffe0001f5e8a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffe000201db0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffe00028a71e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffe0002a4ac0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffe0002a53da)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffe0002a6b88)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffe0002a785e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffe0002a95ae)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/io_uring.c (ffffffe0002ac7fe)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (ffffffe0002b2120)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffe0002bc5d0)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffffffe00036f97e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffe000376dee)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffe0004422fe)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffe00044e224)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffe000453538)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffe000494c26)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffe00052ee6c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (ffffffe000562814)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/net/tun.c (ffffffe00062637a)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffffffe0000a2780)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffe0006ed84a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffe0006fba1e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffe00073febe)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffe00074bd02)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffe00083ec02)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In kernel/signal.c (ffffffff810ac5fb)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810bcfe4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810eeef7)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff8110cfe5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (ffffffff8118b83a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff812122c1)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff812196dd)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff81231a94)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff81240f7d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff8124e8d7)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff8130efc3)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff8132dc6e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff8132e975)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff81330448)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff81332191)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff81336be8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff81338675)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (ffffffff8133f3dc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff8134b3f5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffffffff81418624)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8141ff11)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff814fdbd7)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff8150bd41)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff81511c2e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff81554686)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff81649e6f)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (ffffffff81683b7d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (ffffffff816d9324)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (ffffffff8178599b)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffffffff82af3eee)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff8184d166)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff8185c574)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff818b4ffc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff818c2c54)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff819d1587)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In kernel/signal.c (ffffffff8109af8b)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810ab81d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810def77)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff810fdda5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (ffffffff8117e91a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff81205051)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff8120c8ed)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff81224b54)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff81233f7d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff81241877)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff812ffbd3)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff8131dfba)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff8131f5b5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff81321058)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff81322d51)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff8132755e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff813293a5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (ffffffff8133009c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff8133c0d5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffffffff814090a4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81410991)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff814ee0e7)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff814fc18b)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff81501f4e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff81544906)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff8162a2bf)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (ffffffff816617fd)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (ffffffff816b3964)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (ffffffff817652eb)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffffffff82ac42c9)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff81814786)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff81823b44)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff8186ef4c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff8187cb94)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8198e347)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In kernel/signal.c (ffffffff810abb5b)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810bc544)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810ec027)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff8110aed5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (ffffffff8118960a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff81210061)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff8121747d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff8122f834)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff8123ed1d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff8124c677)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff8130cdb3)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff8132b73e)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff8132c445)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff8132df18)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff8132fc61)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff813346b8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff81336145)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (ffffffff8133ceac)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff81348ec5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffffffff814147c4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8141c0b1)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff814f9c67)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff81507dd1)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff8150dcbe)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff815503c6)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff8167822f)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (ffffffff816b1f4d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (ffffffff81706c64)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (ffffffff817b5d4b)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffffffff82b0f35c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff8189c796)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff818abba4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff81905ffc)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81913c54)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81a3c007)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In kernel/signal.c (ffffffff810b3cc4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810c4154)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/wait_bit.c (ffffffff810f7077)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wake_up_bit
```
```
In kernel/printk/printk.c (ffffffff81116370)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:wake_up_klogd
```
```
In kernel/relay.c (ffffffff81196f7a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/relay.c:relay_switch_subbuf
```
```
In kernel/events/uprobes.c (ffffffff8121f081)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In mm/filemap.c (ffffffff8122652d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/vmscan.c (ffffffff8123ec64)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/backing-dev.c (ffffffff8124e44d)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/compaction.c (ffffffff8125c017)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/splice.c (ffffffff8131e5c3)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
```
```
In fs/eventpoll.c (ffffffff8133cad9)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
```
In fs/signalfd.c (ffffffff8133edc5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_cleanup
```
```
In fs/eventfd.c (ffffffff813407f8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffffffff813425ec)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffffffff81346ba8)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff81349215)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (ffffffff8135013c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_entry
```
```
In fs/locks.c (ffffffff8135c2f5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/locks.c:locks_release_private
```
```
In fs/fuse/dev.c (ffffffff8142b032)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81431bf1)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In block/blk-rq-qos.c (ffffffff81512cc7)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-iocost.c (ffffffff8151f0a6)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In block/blk-wbt.c (ffffffff815272de)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In lib/sbitmap.c (ffffffff8156a206)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/tty/tty_io.c (ffffffff816933df)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/char/random.c (ffffffff816cc443)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/power/wakeup.c (ffffffff81721674)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/net/tun.c (ffffffff817d01bb)
Location: include/linux/wait.h:124
Inline: True
```
```
In drivers/md/md.c (ffffffff82b03e5a)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
```
```
In drivers/md/dm.c (ffffffff818b89d6)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff818c7de4)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff8192702c)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81934de9)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81a479a5)
Location: include/linux/wait.h:124
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
</details>
</li>
</ul>

## Differences
