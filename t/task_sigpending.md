# Function: <code>task_sigpending</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067141)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068cd2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/mm/fault.c (ffffffff8108830e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810a199f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a8cac)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810b0507)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b63db)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In kernel/sched/core.c (ffffffff81c4140e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810fd961)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81c41f46)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810fe0c2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81c4205a)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81c426e4)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81c43772)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110c060)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In kernel/locking/rtmutex.c (ffffffff81c43fd8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff8112c19f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81132bc5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/entry/common.c (ffffffff8113b8c0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timer.c (ffffffff81141e43)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81c448db)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114ad9f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114fb99)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffff811578d2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff811666cf)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811a40e9)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b2f5e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff81213082)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff81252ed5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81258a8d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffffffff812646dc)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81271960)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
```
```
In mm/shmem.c (ffffffff8127bbd3)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff8128e9e0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff81293b59)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff812a8a07)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff812b998e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff812c1ef3)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812c9fe0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812d67ca)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff812defbd)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81c3b152)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/memcontrol.c (ffffffff81304e38)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81314c54)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81327abb)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff8132a224)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
```
```
In fs/ioctl.c (ffffffff81336dd3)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff81337d71)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff81339d7e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff8135e644)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/remap_range.c (ffffffff81366305)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff81367746)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813769ca)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137a127)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8137ba4f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff8137dc52)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff8137fa30)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff81381c3e)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8138447d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff8138aa65)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqpoll_wait_sq
  - fs/io_uring.c:io_uring_flush
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/io-wq.c (ffffffff8139c1d6)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/dax.c (ffffffff8139e0f0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff813a7c1a)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/coredump.c (ffffffff813b8dda)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/coredump.c:dump_skip
  - fs/coredump.c:dump_skip
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff813bd209)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff813ed388)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813fc41b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8141b882)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff81424df2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e0a7)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff81473a50)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8147eace)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff814a6dec)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814aa4d7)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff814b020d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff814d3901)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8153c0b3)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff81545e90)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff8156cc77)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-cgroup.c (ffffffff81584e95)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
```
In block/blk-iocost.c (ffffffff8159186a)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff81657f4b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8166dff2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff81752dd2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81756ff9)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff8175900e)
Location: include/linux/sched/signal.h:357
Inline: True
```
```
In drivers/tty/tty_port.c (ffffffff8175bf3c)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81762c49)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff81774cd1)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81789960)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff8178df68)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/hpet.c (ffffffff81792cc0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81793d6f)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff817e3c62)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837e61)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b2e0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81882f2d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff8189b9ec)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189f87d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio.c (ffffffff818ab4f2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/devio.c (ffffffff818d965b)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff819428e9)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81974f90)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff8197c4aa)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff819de8a3)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff819e54b5)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wait_for_wmem
```
```
In net/core/datagram.c (ffffffff819f5807)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819f6078)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81a833d0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81a88cc8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81a8b1e4)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafef0)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/tcp.c (ffffffff81ab6ae2)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ae07ae)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81af08c8)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/unix/af_unix.c (ffffffff81b3605d)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff81bb67a7)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bbde74)
Location: include/linux/sched/signal.h:357
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810676ac)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106932c)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/mm/fault.c (ffffffff81088e25)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810a2720)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a9c63)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810b1a87)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b56be)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:358
Inline: True
```
```
In kernel/sched/core.c (ffffffff81c33381)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810ffd41)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81c33eb6)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff811004a2)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81c33fca)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81c345a1)
Location: include/linux/sched/signal.h:358
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81c35501)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8110de94)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:358
Inline: True
```
```
In kernel/locking/rtmutex.c (ffffffff81c360f1)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff8112c6cf)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81133f55)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/entry/common.c (ffffffff8113cb95)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timer.c (ffffffff81142c43)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81c37b4b)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114c25c)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81150fda)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffff81158d22)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff8116746f)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811a4a07)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b37ee)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff81215532)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff81257215)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8125cf8d)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffffffff812688eb)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81276c50)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
```
```
In mm/shmem.c (ffffffff81280d3e)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff81294070)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff812994f6)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff812adeb4)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff812c217b)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81c2d7bf)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff812c8db2)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812d0a54)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812dd97d)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff812e67ad)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff8130be38)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff8131b347)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8132d8ab)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff813301d4)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
```
```
In fs/ioctl.c (ffffffff8133cf33)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff8133e4c2)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff81340336)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff813646d1)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/remap_range.c (ffffffff8136cd0c)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8136e186)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d223)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380d03)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff813821cf)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff813848d2)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff813866af)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff81388ca5)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8138b0cd)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff813a18df)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/io-wq.c (ffffffff813a31ff)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/dax.c (ffffffff813a51b6)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff813aec7c)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff813b058b)
Location: include/linux/sched/signal.h:358
Inline: True
```
```
In fs/coredump.c (ffffffff813bf06e)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff813c4359)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff813f39ee)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff81402ca1)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff81421a96)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff8142baf6)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff814734e8)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff8147949c)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81484652)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff814acd46)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814b0d70)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff814b605d)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff814da381)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff815447a3)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff8154e520)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff81574b17)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-cgroup.c (ffffffff8158db11)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff815986cb)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8163a76b)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81650542)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff81736d9f)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff8173a6d9)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173cf8e)
Location: include/linux/sched/signal.h:358
Inline: True
```
```
In drivers/tty/tty_port.c (ffffffff8173fddc)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81746906)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757d81)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff8176d200)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81770918)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/hpet.c (ffffffff817759e0)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff8177694c)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff817c80a2)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181b14c)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e4ea)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8186577b)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff8187f174)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8188230d)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818902ee)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/usb/core/devio.c (ffffffff818bc725)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81926109)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81958fc2)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff819606dd)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff819c4843)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff819cb54b)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819db9a7)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819dc0e7)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81a6c4a0)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81a70b85)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81a74513)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c044)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81aa1ca4)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81acc79a)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81adbf56)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81b23c3d)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff81ba57b4)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bae15d)
Location: include/linux/sched/signal.h:358
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071a4c)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8107366f)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/mm/fault.c (ffffffff81098294)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810b3e1d)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810bb791)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810c3b77)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810c7cbe)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:task_join_group_stop
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:356
Inline: True
```
```
In kernel/sched/core.c (ffffffff81d51cc8)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff8111be1e)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81d52858)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff8111c509)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81d52966)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81d52f20)
Location: include/linux/sched/signal.h:356
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81d53cfd)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8112d669)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:356
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d5495d)
Location: include/linux/sched/signal.h:356
Inline: True
```
```
In kernel/rcu/update.c (ffffffff8114d3cf)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81156427)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/entry/common.c (ffffffff8115fcb5)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timer.c (ffffffff81166143)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81d563c0)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81170023)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811753aa)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffff8117dbf2)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff8118cfdf)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811ce1ff)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811dd5be)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff8124bb24)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff81292fa5)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81298e9c)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/oom_kill.c (ffffffff812a3812)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff812a537d)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff812b4580)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
```
```
In mm/shmem.c (ffffffff812bf186)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff812d45ed)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff812d9e40)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff812ef609)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff81305af9)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81d4c095)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff8130ddd3)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8131612f)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81324b3d)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff8132e6cd)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff81357128)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81368237)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8137b0cb)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff8137d994)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
```
```
In fs/readdir.c (ffffffff8138be52)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff8138dd06)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff813b34c1)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/remap_range.c (ffffffff813bb9cc)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff813bd255)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca2a3)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cdcc6)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff813cf43f)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff813d1b72)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff813d3957)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813d5fb7)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff813d864d)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff813f02eb)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sqd_handle_event
  - fs/io_uring.c:io_sqd_handle_event
```
```
In fs/io-wq.c (ffffffff813f16ec)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/dax.c (ffffffff813f497b)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff813fe81c)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff8140017b)
Location: include/linux/sched/signal.h:356
Inline: True
```
```
In fs/coredump.c (ffffffff8140ee9e)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff81413988)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff81445ab1)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff81455371)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff814743ed)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff8147f996)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca0dd)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff814d0adb)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbcd2)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff81505232)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff815092a1)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8150e904)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff81533281)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff815a4f43)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff815aee70)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff815d9051)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-cgroup.c (ffffffff815f3580)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff815ffeb5)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff816ab2ae)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816c2282)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff817b7778)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff817bb669)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff817bd61e)
Location: include/linux/sched/signal.h:356
Inline: True
```
```
In drivers/tty/tty_port.c (ffffffff817c057c)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff817c78f6)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff817db5f0)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff817f2b90)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff817f6331)
Location: include/linux/sched/signal.h:356
Inline: True
```
```
In drivers/char/hpet.c (ffffffff817fb740)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff817fc90c)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81852592)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a55c1)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a8975)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff818f4b02)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff81911158)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81913cb5)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923ee1)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/usb/core/devio.c (ffffffff81952746)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff819c9079)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff819fe762)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81a0837d)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81a73ca3)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81a7abdb)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81a8bbf7)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81a8c327)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81b25afe)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81b2a4a5)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81b2e75a)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b578e4)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81b5e7b4)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81b8b02a)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81b9b185)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc809c)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81be807f)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff81c73313)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81c7b407)
Location: include/linux/sched/signal.h:356
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107fb1e)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081aca)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/mm/fault.c (ffffffff810aaeee)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810ca107)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810d21cf)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810db2b4)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810def95)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:386
Inline: True
```
```
In kernel/sched/core.c (ffffffff81f2222a)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff8114019d)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81f23b63)
Location: include/linux/sched/signal.h:386
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81f24d43)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff81f258c9)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:386
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f264eb)
Location: include/linux/sched/signal.h:386
Inline: True
```
```
In kernel/rcu/update.c (ffffffff8117404b)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
```
```
In kernel/rcu/tree.c (ffffffff8117d989)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/entry/common.c (ffffffff8118a1bd)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timer.c (ffffffff81199cc3)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81f2853a)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811a4563)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a9cf7)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex/requeue.c (ffffffff811b64e7)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/futex/waitwake.c (ffffffff811b76c3)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait
  - kernel/futex/waitwake.c:futex_wait_multiple
```
```
In kernel/kexec_core.c (ffffffff811bc22f)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff812024aa)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8121433c)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched/signal.h:386
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff81292cdd)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff812e8a1b)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff812ef760)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2_killable
```
```
In mm/oom_kill.c (ffffffff812fb74e)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff812fdec0)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8131055d)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/shmem.c (ffffffff8131ae44)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff813335a2)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff81339b6a)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff81352a80)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/vmalloc.c (ffffffff81360708)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_area_alloc_pages
```
```
In mm/page_alloc.c (ffffffff81371d3c)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff81f1ba09)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff81377162)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813812c4)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff813932d3)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff8139ea8d)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff813caa93)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff813e5bc7)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff813fb62f)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff813fe034)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
```
```
In fs/readdir.c (ffffffff8140d3e4)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff8140f083)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff81437ce2)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/remap_range.c (ffffffff81441c2d)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff81443481)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8145233b)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81455da5)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff81458221)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff8145abe0)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff8145ce41)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff8145dc97)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff81462b10)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/dax.c (ffffffff81467fd5)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81472339)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff81473f9e)
Location: include/linux/sched/signal.h:386
Inline: True
```
```
In fs/coredump.c (ffffffff814845ce)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8148b181)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff814c1af7)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff814d2bee)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff814f62d2)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff815029e9)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff81555df4)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff8155d665)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8156994c)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff81596bf2)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8159b00e)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff815a0b05)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff815c5604)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8164bb8d)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff81657540)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff8168bdca)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-cgroup.c (ffffffff816a4b07)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff816b255a)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff816d6ded)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_sqd_handle_event
  - io_uring/io_uring.c:io_sqd_handle_event
```
```
In io_uring/io-wq.c (ffffffff816da7d6)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wqe_worker
```
```
In drivers/pci/vpd.c (ffffffff817ce335)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff817e7bb2)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/pci/vgaarb.c (ffffffff817f4103)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_get
```
```
In drivers/tty/tty_io.c (ffffffff818f2a32)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff818f6626)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff818f9962)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
```
In drivers/tty/tty_port.c (ffffffff818fcd08)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81904a06)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191ac3f)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff819336e0)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81934322)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/char/hpet.c (ffffffff8193aba9)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff8193b68c)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81998462)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ef207)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f26c8)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/net/tun.c (ffffffff81a61586)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69222)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79871)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/usb/core/devio.c (ffffffff81aac371)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81b2a29f)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81b65d30)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81b70718)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81be6f27)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81beeaff)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81c01453)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81c01bc6)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81cae6a4)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81cb40a2)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81cb91f2)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce58c9)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81ced1a8)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81d1ae2c)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81d2cfdc)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5d6a9)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81d7f99c)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff81e17087)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81e20486)
Location: include/linux/sched/signal.h:386
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091c0e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810944ea)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/mm/fault.c (ffffffff810c4be4)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810e7771)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810f0c43)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810fb514)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810ffd35)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In kernel/sched/core.c (ffffffff820ccad6)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff8116c40d)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff820cf030)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff820d03ca)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff820d12af)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d1fcc)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811aa0b2)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
```
```
In kernel/rcu/tree.c (ffffffff811b85a7)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/entry/common.c (ffffffff811c66fd)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timer.c (ffffffff811d8363)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff820d41ba)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811e3e83)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e9c57)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex/requeue.c (ffffffff811f7627)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/futex/waitwake.c (ffffffff811f8853)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait
  - kernel/futex/waitwake.c:futex_wait_multiple
```
```
In kernel/kexec_core.c (ffffffff811fe45f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8124a08f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8125de4c)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff812ed768)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff8135277b)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8135a4c0)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/oom_kill.c (ffffffff8136585e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff81368884)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81383bcd)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/shmem.c (ffffffff8138ec0f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff813aa2a7)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff813b35c8)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff813ccbb6)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/vmalloc.c (ffffffff813e2883)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813ef51c)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff820c3999)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff813f4762)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813ffb07)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81411a64)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff8141dcb1)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff8144fad3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff8146d6c6)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff814856cf)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff81487c64)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
```
```
In fs/readdir.c (ffffffff81497ea4)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff81499c23)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff814c5b42)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/remap_range.c (ffffffff814d0f0d)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff814d2a31)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e10cf)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e4d35)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff814e7b51)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff814ea170)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff814ec50a)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff814ed6f3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff814f31a0)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/dax.c (ffffffff814f831b)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81503e31)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815061f0)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In fs/coredump.c (ffffffff81517aae)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8151f1b9)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff81559dae)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8156b79e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8159069f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff8159d4e9)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff815f74ec)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff815ff6b5)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d585)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff8163faf7)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8164435e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8164a488)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff816721f4)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff81704d8d)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff817119c0)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff81741c9e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_classic
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-cgroup.c (ffffffff81763897)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff81771a9f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff81791b7c)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/sqpoll.c (ffffffff8179ac46)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
```
```
In io_uring/io-wq.c (ffffffff817a68c6)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wqe_worker
```
```
In drivers/pci/vpd.c (ffffffff818edde5)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190d252)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/pci/vgaarb.c (ffffffff8191e7e3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_get
```
```
In drivers/tty/tty_io.c (ffffffff81a4affd)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81a4f049)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a52b8d)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
```
In drivers/tty/tty_port.c (ffffffff81a563d8)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81a5eaf6)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a769d5)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81a921fb)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81a93f52)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/char/hpet.c (ffffffff81a9afe9)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81a9bd4c)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81b09512)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c737)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b7059b)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/net/tun.c (ffffffff81bec8e6)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfbd42)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff81c3396e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81cbdf1f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81d00f1e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81d0d62d)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81d92f07)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81d9b14f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81db07a3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81db0f86)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81e6bce2)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81e72302)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81e78073)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8ac9)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81eb10d8)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ee23cc)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81ef4b22)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27da9)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81f4d68c)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff81feec3e)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff794d)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094b57)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109747a)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/mm/fault.c (ffffffff810c8174)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810f32f3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810fcbf3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff8110733c)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8110bdc5)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:unhandled_signal
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In kernel/vhost_task.c (ffffffff81139262)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_fn
```
```
In kernel/sched/core.c (ffffffff82150e5b)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff8117cb6d)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff821533ed)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff8215475a)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff82155614)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff821563ed)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811bbfe2)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
```
```
In kernel/rcu/tree.c (ffffffff811ca4d7)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/entry/common.c (ffffffff811d931d)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timer.c (ffffffff811ec793)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff821584a5)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811f84f3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fe347)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex/requeue.c (ffffffff8120bdc1)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/futex/waitwake.c (ffffffff8120d013)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait
  - kernel/futex/waitwake.c:futex_wait_multiple
```
```
In kernel/kexec_core.c (ffffffff81213729)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8126137f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff812750bc)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8131a0b8)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff8138398b)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8138bdd4)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/oom_kill.c (ffffffff81397cfe)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff8139aa24)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff813b567d)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/shmem.c (ffffffff813c1fe2)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff813dd542)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff813e2bae)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff8140149c)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/vmalloc.c (ffffffff81417440)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff81423095)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff8214777a)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff81427d2a)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81432997)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81444ef4)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff814526a9)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff81485503)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff814a21a7)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814ba72f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff814bcb24)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
```
```
In fs/readdir.c (ffffffff814ccdbe)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff814cecf3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff814fcb48)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/remap_range.c (ffffffff81507a3f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8150933e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8151796f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151bd85)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8151de04)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff81520f10)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/userfaultfd.c (ffffffff81524703)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff81529f5e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/dax.c (ffffffff8152fae3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff8153b8b7)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/read_metadata.c (ffffffff8153d522)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In fs/coredump.c (ffffffff8154f39e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff815572e4)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff81591bdc)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff815a364e)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff815c7852)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff815d3d35)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f572)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff81637695)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8164543f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff81677fcd)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8167c79c)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff816829ea)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff816aa739)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8173efad)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff8174c580)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e78f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - crypto/jitterentropy-testing.c:jent_raw_hires_read
```
```
In block/blk-mq.c (ffffffff8177d2dc)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/blk-cgroup.c (ffffffff817a2936)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff817b0d6a)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff817d0e16)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_run_task_work_sig
  - io_uring/io_uring.c:io_iopoll_check
```
```
In io_uring/sqpoll.c (ffffffff817dbcf6)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
```
```
In io_uring/io-wq.c (ffffffff817e783c)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_worker
```
```
In rust/helpers.c (ffffffff81805bd3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_signal_pending
```
```
In drivers/pci/vpd.c (ffffffff819312c5)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff819508d2)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/pci/vgaarb.c (ffffffff81961ec3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_get
```
```
In drivers/tty/tty_io.c (ffffffff81a9507b)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81a9925c)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a9cf14)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
```
In drivers/tty/tty_port.c (ffffffff81aa09b8)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81aa9196)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac1475)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81addaa3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81adea82)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/char/hpet.c (ffffffff81ae6879)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81ae76ac)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81b57522)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbfdc7)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc3e8f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/net/tun.c (ffffffff81c44de6)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61386)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff81c9a6bb)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81d2582f)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81d6a27b)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81d7654d)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81e0130b)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81e0a336)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81e20c63)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81e21473)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81ec7d42)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81ece472)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81ed41f3)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f07349)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81f0f768)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81f41ecc)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81f544eb)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87965)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81fad121)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff8206b685)
Location: include/linux/sched/signal.h:387
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82073de1)
Location: include/linux/sched/signal.h:387
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109c037)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e9ea)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/mm/fault.c (ffffffff810d064d)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810fc6a3)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff811071e0)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff81110c8c)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81115775)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:unhandled_signal
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched/signal.h:379
Inline: True
```
```
In kernel/vhost_task.c (ffffffff81144022)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_fn
```
```
In kernel/sched/core.c (ffffffff82233c70)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff8118a94d)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff8223622d)
Location: include/linux/sched/signal.h:379
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff8223759a)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff82238454)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched/signal.h:379
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff8223922d)
Location: include/linux/sched/signal.h:379
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811cc445)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
```
```
In kernel/rcu/tree.c (ffffffff811de492)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/entry/common.c (ffffffff811eec5d)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_trace_enter
```
```
In kernel/time/timer.c (ffffffff812027b3)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff8223b315)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8120e693)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812146d7)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex/requeue.c (ffffffff81223356)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/futex/waitwake.c (ffffffff812246f7)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:__futex_wait
  - kernel/futex/waitwake.c:futex_wait_multiple
```
```
In kernel/kexec_core.c (ffffffff8122b659)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8127b57f)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8128f9e3)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched/signal.h:379
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8133ba49)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff813acdeb)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff813b5944)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/oom_kill.c (ffffffff813c1b2e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff813c495f)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff813de66d)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/shmem.c (ffffffff813ecd57)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff814074a2)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff8140d3ee)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff8142dadb)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/vmalloc.c (ffffffff81443f50)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff8144ffc5)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff82229fb7)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff8146153b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8146bdb7)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8147550c)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff8148cca9)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff814b46e3)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff814d342b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814eccaf)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff814eefd4)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
```
```
In fs/readdir.c (ffffffff814ff3ae)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff81501633)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff81531778)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/remap_range.c (ffffffff8153c1c0)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8153e25e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154bd4f)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81550385)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff815523e4)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff81555550)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/userfaultfd.c (ffffffff8155b1f3)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8155ee2e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/dax.c (ffffffff815649c3)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81570b94)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/read_metadata.c (ffffffff81572982)
Location: include/linux/sched/signal.h:379
Inline: True
```
```
In fs/coredump.c (ffffffff815851de)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8158d814)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/task_mmu.c (ffffffff8159bd8f)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
```
```
In fs/ext4/dir.c (ffffffff815ca94c)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff815dc48e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff815f963e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_interrupted
```
```
In fs/ext4/namei.c (ffffffff8160c3a5)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff81668a7e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff81670b85)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8167e961)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff816b438d)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff816b8b6c)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff816bedea)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff816e778c)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8177fe2d)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff8178e490)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff817bf66c)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/blk-cgroup.c (ffffffff817e647b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff817f4b7a)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff8181396a)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_run_task_work_sig
  - io_uring/io_uring.c:io_iopoll_check
```
```
In io_uring/sqpoll.c (ffffffff81820076)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
```
```
In io_uring/io-wq.c (ffffffff8182d64b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_worker
```
```
In rust/helpers.c (ffffffff81842943)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_signal_pending
```
```
In drivers/pci/vpd.c (ffffffff81979de5)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81999d32)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/pci/vgaarb.c (ffffffff819ab503)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_get
```
```
In drivers/tty/tty_io.c (ffffffff81ae7a6b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:iterate_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81aebead)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81aef9e4)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
```
In drivers/tty/tty_port.c (ffffffff81af3418)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81afbc56)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b142b5)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81b30e93)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81b31ea2)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/char/hpet.c (ffffffff81b39c09)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81b3aaac)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81bafb12)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c14547)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c186af)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb0a8b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
```
```
In drivers/net/tun.c (ffffffff81cfa946)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d17d66)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff81d4f28b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81ddb59f)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81e20f2a)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81e2d77d)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81ebdcbb)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81ec6d28)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81edeb33)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81edf20b)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81f8b154)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81f91ca2)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81f97c03)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb68e)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81fd3958)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff82007d5c)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff8201a729)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204f002)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff8207b590)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff8213e06e)
Location: include/linux/sched/signal.h:379
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82148310)
Location: include/linux/sched/signal.h:379
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
