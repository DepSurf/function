# Function: <code>test_tsk_thread_flag</code>

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
In arch/x86/entry/common.c (ffffffff81003598)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
```
```
In arch/x86/kernel/process_64.c (ffffffff8102db43)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff8103934d)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103b89c)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
```
In arch/x86/kernel/step.c (ffffffff8103dcdf)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff81065e4d)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81066265)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff8106b25b)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In kernel/fork.c (ffffffff8107f247)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810835bc)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff8108b3a9)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8108d9b2)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/signal.c:task_set_jobctl_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:sys_pause
```
```
In kernel/kthread.c (ffffffff810a03f4)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff810aa2d5)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffffffff810b4f21)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810befdc)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c1377)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810c38e3)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:bit_wait
  - kernel/sched/wait.c:bit_wait_io
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:bit_wait_io_timeout
```
```
In kernel/sched/completion.c (ffffffff81821224)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_killable
```
```
In kernel/locking/mutex.c (ffffffff81821aef)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
```
```
In kernel/locking/semaphore.c (ffffffff818226b8)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down_killable
```
```
In kernel/locking/rtmutex.c (ffffffff81822aa9)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/tree.c (ffffffff810e6feb)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/time/timer.c (ffffffff810ec6c7)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff818236d1)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f3538)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff810fb429)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff8110048f)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/seccomp.c (ffffffff8113bf78)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_phase2
```
```
In kernel/trace/ring_buffer.c (ffffffff8114a506)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/events/uprobes.c (ffffffff8118852e)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (ffffffff8118d4a6)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
```
```
In mm/oom_kill.c (ffffffff811909a9)
Location: include/linux/sched.h:2874
Inline: True
```
```
In mm/page_alloc.c (ffffffff81197896)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff81199852)
Location: include/linux/sched.h:2874
Inline: True
```
```
In mm/vmscan.c (ffffffff811a0e3b)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff811aa69d)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff811b569b)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:compact_zone
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/gup.c (ffffffff811bab76)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff811c833a)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/swapfile.c (ffffffff811d5583)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff811dbefc)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/ksm.c (ffffffff811e42eb)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff8181a3c6)
Location: include/linux/sched.h:2874
Inline: True
```
```
In mm/memcontrol.c (ffffffff811f9c2d)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_resize_limit
  - mm/memcontrol.c:mem_cgroup_resize_memsw_limit
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81207b5e)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/exec.c (ffffffff81212db1)
Location: include/linux/sched.h:2874
Inline: True
```
```
In fs/pipe.c (ffffffff81214dc1)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff8121fbb6)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/select.c (ffffffff812214e1)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_sys_poll
```
```
In fs/splice.c (ffffffff8123d930)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/splice.c:splice_to_pipe
```
```
In fs/buffer.c (ffffffff812457af)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81251e24)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812533d6)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff812556bb)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff8125750c)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/timerfd.c (ffffffff81258408)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81259588)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff81259c71)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8125bf0d)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In fs/compat.c (ffffffff81265303)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/compat.c:compat_core_sys_select
```
```
In fs/coredump.c (ffffffff8126eeb1)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/mballoc.c (ffffffff812d5953)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/hugetlbfs/inode.c (ffffffff812f4c7d)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/ecryptfs/read_write.c (ffffffff81304a63)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81310cfa)
Location: include/linux/sched.h:2874
Inline: True
```
```
In ipc/msg.c (ffffffff81326351)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
```
```
In ipc/sem.c (ffffffff81328b19)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In ipc/mqueue.c (ffffffff8132cd70)
Location: include/linux/sched.h:2874
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81345392)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8139c3a1)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/ablkcipher.c (ffffffff813a07ba)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - crypto/ablkcipher.c:crypto_alloc_ablkcipher
```
```
In crypto/algboss.c (ffffffff813a45f3)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-core.c (ffffffff813bbc6b)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - block/blk-core.c:blk_poll
```
```
In lib/percpu_ida.c (ffffffff813ff9c2)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/pci/access.c (ffffffff8142e897)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_pci22_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144d70c)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff814dff3f)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
```
In drivers/tty/n_tty.c (ffffffff814e5736)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff814e8ad4)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff814eb5c9)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/serial/serial_core.c (ffffffff81500643)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81510fd1)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
```
```
In drivers/char/random.c (ffffffff815135ca)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/char/random.c:extract_entropy_user
  - drivers/char/random.c:SyS_getrandom
```
```
In drivers/char/hpet.c (ffffffff81519487)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff8151a6e5)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8153fb8e)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/base/power/wakeup.c (ffffffff8155c7db)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/fence.c (ffffffff815a462c)
Location: include/linux/sched.h:2874
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f56dd)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff81619ea3)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/rtc/rtc-dev.c (ffffffff81675a5f)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff8168f542)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff816a038f)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm.c:dm_wait_for_completion
```
```
In net/socket.c (ffffffff816fdfa5)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81702731)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8170cc31)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/core/stream.c (ffffffff8170dea4)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/ethtool.c (ffffffff81721e2e)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff8174e426)
Location: include/linux/sched.h:2874
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8176502a)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81766374)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/af_inet.c (ffffffff817936fc)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff817bfaa4)
Location: include/linux/sched.h:2874
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In arch/x86/entry/common.c (ffffffff8100347b)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ce5c)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff810383a5)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cc1a)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103dcb5)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff81065b3d)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81065ff5)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff8106b5d3)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810813fd)
Location: include/linux/sched.h:3151
Inline: True
```
```
In kernel/exit.c (ffffffff81086655)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff8108e419)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81093bdd)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810a3aec)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff8189a593)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810b7a47)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810c28dc)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c4e37)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff8189b19e)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_wait_io_timeout
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:bit_wait_io
  - kernel/sched/wait.c:bit_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810c75f3)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff8189b534)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff8189bef8)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
```
```
In kernel/locking/semaphore.c (ffffffff8189cc68)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rtmutex.c (ffffffff8189cff0)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8189db09)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
```
```
In kernel/rcu/update.c (ffffffff810e9730)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff810ed21f)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/freezer.c (ffffffff810f07fe)
Location: include/linux/sched.h:3151
Inline: True
```
```
In kernel/time/timer.c (ffffffff810f3d57)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff8189e341)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810fa653)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81102739)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff81107dcf)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/seccomp.c (ffffffff81143d3b)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81152f72)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/events/uprobes.c (ffffffff8119b195)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811a0085)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
```
```
In mm/page_alloc.c (ffffffff811ac7df)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff811ae1ba)
Location: include/linux/sched.h:3151
Inline: True
```
```
In mm/vmscan.c (ffffffff811b840b)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff811c2de5)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff811d21ee)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff811d53e4)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff811e447f)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/swapfile.c (ffffffff811f3577)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff811fda6d)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff812034db)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81893e60)
Location: include/linux/sched.h:3151
Inline: True
```
```
In mm/memcontrol.c (ffffffff81222a8d)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff8122d8fe)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff8123209f)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff81239bdf)
Location: include/linux/sched.h:3151
Inline: True
```
```
In fs/pipe.c (ffffffff8123bc51)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff81247421)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff8124802a)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff81249e2b)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff812659fd)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/splice.c:splice_to_pipe
```
```
In fs/buffer.c (ffffffff8126e544)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127a551)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127b841)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8127d9ee)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff8127fe0e)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/timerfd.c (ffffffff81280d0f)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81281f5e)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff8128268c)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff812849bd)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In fs/compat.c (ffffffff81291621)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir
```
```
In fs/coredump.c (ffffffff8129a681)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/dir.c (ffffffff812be355)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/namei.c (ffffffff812d2a2c)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/mballoc.c (ffffffff81305607)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/hugetlbfs/inode.c (ffffffff8132870e)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/ecryptfs/read_write.c (ffffffff81338ba8)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8134514f)
Location: include/linux/sched.h:3151
Inline: True
```
```
In ipc/msg.c (ffffffff8135b6d3)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8135d771)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In ipc/mqueue.c (ffffffff813619df)
Location: include/linux/sched.h:3151
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8137ac32)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff813d92c6)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff813e1db3)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-core.c (ffffffff813ffa83)
Location: include/linux/sched.h:3151
Inline: True
```
```
In lib/percpu_ida.c (ffffffff814470b2)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/pci/access.c (ffffffff81479e77)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81499e4c)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff81533bb0)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81536987)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81539bf4)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff8153c7ae)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/serial/serial_core.c (ffffffff81553c50)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81563551)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
```
```
In drivers/char/random.c (ffffffff8156821a)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/char/random.c:SyS_getrandom
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff8156c196)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff8156d400)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff815aeaa2)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/fence.c (ffffffff815fb70b)
Location: include/linux/sched.h:3151
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8164093d)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff8164eb87)
Location: include/linux/sched.h:3151
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81655419)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff8167d238)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/rtc-dev.c (ffffffff816d62f3)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff816f390d)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff817025c9)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/socket.c (ffffffff81763535)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81769979)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81774481)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81775c0e)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff8178ba2d)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff817ba5d1)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d15aa)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff817d36a1)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81800f01)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8182c9b2)
Location: include/linux/sched.h:3151
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff8100344e)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cd36)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff81037e41)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103bf42)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103d585)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff8106906d)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81069525)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff8106f211)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81085e5c)
Location: include/linux/sched.h:3307
Inline: True
```
```
In kernel/exit.c (ffffffff8108b5c6)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff81092fc9)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81098bdd)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810a8bc1)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff818cebb4)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810bfd57)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810c895c)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cae87)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff818cf71e)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_wait_io_timeout
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:bit_wait_io
  - kernel/sched/wait.c:bit_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810cd4c3)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff818cfb55)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff818d1532)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
```
```
In kernel/locking/semaphore.c (ffffffff818d1b48)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rtmutex.c (ffffffff818d1ed1)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff818d29be)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
```
```
In kernel/rcu/update.c (ffffffff810f05e3)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff810f419a)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/freezer.c (ffffffff810f795e)
Location: include/linux/sched.h:3307
Inline: True
```
```
In kernel/time/timer.c (ffffffff810faf08)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff818d31e2)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8110505a)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81107fd3)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffff8110f5bf)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/seccomp.c (ffffffff8114dc0b)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8115cf62)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/events/uprobes.c (ffffffff811aaba5)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811af925)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page_alloc.c (ffffffff811bcdb5)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff811be879)
Location: include/linux/sched.h:3307
Inline: True
```
```
In mm/vmscan.c (ffffffff811c8a4b)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff811d2e45)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff811e20f6)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff811e53f4)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff811f44bf)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/swapfile.c (ffffffff81204039)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8120e566)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff812154fb)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff818c8559)
Location: include/linux/sched.h:3307
Inline: True
```
```
In mm/memcontrol.c (ffffffff8123184d)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff8123fe39)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81244414)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff8124c921)
Location: include/linux/sched.h:3307
Inline: True
```
```
In fs/pipe.c (ffffffff8124e9f1)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff8125a407)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff8125b06a)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff8125cdf2)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff8127a44d)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff8128176a)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128e106)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8128f6bf)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8129151b)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff8129397d)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/timerfd.c (ffffffff81294850)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81295a90)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff812961ad)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8129866d)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In fs/dax.c (ffffffff8129ab34)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/compat.c (ffffffff812a63b1)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir
```
```
In fs/coredump.c (ffffffff812af211)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff812b0962)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff812d39a6)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/namei.c (ffffffff812e876e)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/mballoc.c (ffffffff8131b5ce)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e45b)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/ecryptfs/read_write.c (ffffffff8134e948)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8135af0e)
Location: include/linux/sched.h:3307
Inline: True
```
```
In ipc/msg.c (ffffffff81371ccc)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81373e36)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In ipc/mqueue.c (ffffffff813781e0)
Location: include/linux/sched.h:3307
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81391082)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff813f0bd6)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff813fae23)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff81421f60)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid_sleep
```
```
In lib/percpu_ida.c (ffffffff814658d8)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/pci/access.c (ffffffff8149b303)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bba3c)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff815602e0)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff815630a7)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff815662d4)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff81568e0e)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/serial/serial_core.c (ffffffff8158092e)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff8158fcc1)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
```
```
In drivers/char/random.c (ffffffff8159493a)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/char/random.c:SyS_getrandom
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff8159890b)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81599b68)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff815dd8a7)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816292f1)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81671a7e)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff81680899)
Location: include/linux/sched.h:3307
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816830f9)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff816aafbb)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/rtc-dev.c (ffffffff81705fd3)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81725061)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff8173448c)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/socket.c (ffffffff81790583)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81796894)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff817a1750)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff817a2dd2)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff817b931e)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff817e9f73)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8180146b)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818033f8)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81831e37)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8185e466)
Location: include/linux/sched.h:3307
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff810032f8)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/kernel/process_64.c (ffffffff8102af36)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff81035f9f)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff81039f7e)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103b5d5)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff8106834d)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81068795)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff8106e96e)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81082849)
Location: include/linux/sched.h:1502
Inline: True
```
```
In kernel/exit.c (ffffffff81088345)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff8108fff1)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81095e6d)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810a59a1)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81905fe4)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810bb787)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810c3924)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c52a7)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810c9a48)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81906b5e)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810c9e43)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff819072c4)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/sched/idle.c (ffffffff810ca462)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/locking/mutex.c (ffffffff81907cdf)
Location: include/linux/sched.h:1502
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81908d17)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rtmutex.c (ffffffff819090c1)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8190989d)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
```
```
In kernel/rcu/update.c (ffffffff810f05f7)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff810f50a4)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (ffffffff810f8d2a)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff810f982e)
Location: include/linux/sched.h:1502
Inline: True
```
```
In kernel/time/timer.c (ffffffff810fdfb8)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff8190a365)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81106f67)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110a238)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffff81110758)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/seccomp.c (ffffffff81150166)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8115ff69)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/events/uprobes.c (ffffffff811b20e5)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811b680a)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page_alloc.c (ffffffff811c4fc9)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff811c6760)
Location: include/linux/sched.h:1502
Inline: True
```
```
In mm/vmscan.c (ffffffff811d11d7)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff811db919)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff811ebec3)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff811efb7c)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff811ff43f)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/vmalloc.c (ffffffff812082a1)
Location: include/linux/sched.h:1502
Inline: True
```
```
In mm/swapfile.c (ffffffff8120f6d8)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81219f2b)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff81220b1b)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff818ffb37)
Location: include/linux/sched.h:1502
Inline: True
```
```
In mm/memcontrol.c (ffffffff8123d085)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff8124bd32)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff8124fb9b)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812589ed)
Location: include/linux/sched.h:1502
Inline: True
```
```
In fs/pipe.c (ffffffff8125a921)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff81266db8)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff81267f03)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff812695d1)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff8128791f)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff8128ef7e)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8129b089)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129c518)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8129e431)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff812a0c6f)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffff812a2c49)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff812a354e)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff812a616b)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In fs/dax.c (ffffffff812a9753)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/coredump.c (ffffffff812bc641)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff812be5e9)
Location: include/linux/sched.h:1502
Inline: True
```
```
In fs/ext4/dir.c (ffffffff812e5350)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff812f209a)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813129b6)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/namei.c (ffffffff81317f33)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff8135305a)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/ecryptfs/read_write.c (ffffffff81363455)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff813850c0)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff813876bb)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In ipc/mqueue.c (ffffffff8138bbf4)
Location: include/linux/sched.h:1502
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813a77d6)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff813fce70)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff81407845)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff81430778)
Location: include/linux/sched.h:1502
Inline: True
```
```
In lib/percpu_ida.c (ffffffff8146a6ad)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/pci/access.c (ffffffff814a54b3)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c623c)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff81573e40)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff815761e7)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff815798d1)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff8157c4d6)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/serial/serial_core.c (ffffffff81594846)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff815a3d91)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
```
```
In drivers/char/random.c (ffffffff815a8751)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff815ac8e4)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff815adb99)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff815f2517)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8163f827)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff816860ce)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff81695b58)
Location: include/linux/sched.h:1502
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169856d)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff816c00ab)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/rtc-dev.c (ffffffff8171bc83)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff8173caf2)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff8174d86e)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/socket.c (ffffffff817adb47)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff817b4c0c)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff817c0757)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff817c0e62)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff817d7bc4)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff81809c39)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff8180c6fa)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8182193d)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81823fd6)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81845c70)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff818533a6)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8188382a)
Location: include/linux/sched.h:1502
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff81003245)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/kernel/process_64.c (ffffffff8102bc64)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff810382ff)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c98d)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103dff5)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff8106c630)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8106ca75)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff81073a18)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81089685)
Location: include/linux/sched.h:1536
Inline: True
```
```
In kernel/exit.c (ffffffff8108f0cf)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff81096e7a)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8109ccbd)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810ac0b1)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff8199005e)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810c34e7)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810cb0e4)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cc9c7)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810d1268)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81990bce)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:atomic_t_wait
```
```
In kernel/sched/swait.c (ffffffff810d166a)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff819914df)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/sched/idle.c (ffffffff810d1c7d)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/locking/mutex.c (ffffffff81991dd1)
Location: include/linux/sched.h:1536
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81992be2)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rtmutex.c (ffffffff819931d6)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819937d5)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In kernel/rcu/update.c (ffffffff810fa2c7)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff810fef67)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (ffffffff811032e5)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff811042de)
Location: include/linux/sched.h:1536
Inline: True
```
```
In kernel/time/timer.c (ffffffff81108851)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff819946ba)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81112083)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811153f7)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffff8111bf00)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/seccomp.c (ffffffff8115cf26)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8116d040)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/events/uprobes.c (ffffffff811c5cf5)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811cab45)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page_alloc.c (ffffffff811d9d88)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff811db572)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff811e66a7)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff811f1719)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff81202230)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81206f21)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff81217a49)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/swapfile.c (ffffffff8122af4a)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81234fe7)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff8123bda9)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81989b22)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff8125cc08)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff8126bf9a)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81271aec)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff8127ab79)
Location: include/linux/sched.h:1536
Inline: True
```
```
In fs/pipe.c (ffffffff8127ccaf)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff81289651)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff8128a7b3)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff8128be81)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff812aa44f)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff812b1b7e)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812be49b)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812bf999)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff812c191c)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff812c3fc4)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffff812c5f75)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff812c6ae9)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff812c9625)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In fs/dax.c (ffffffff812ccd40)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/coredump.c (ffffffff812dff2f)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff812e1f89)
Location: include/linux/sched.h:1536
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81309d79)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8131661a)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff81337181)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/namei.c (ffffffff8133c79c)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff81377bce)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/ecryptfs/read_write.c (ffffffff81388132)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff813a9398)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff813abf17)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff813b0f99)
Location: include/linux/sched.h:1536
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813ccfa6)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814253d2)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff81430196)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff8145bc60)
Location: include/linux/sched.h:1536
Inline: True
```
```
In lib/percpu_ida.c (ffffffff8149699b)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/pci/access.c (ffffffff814e42f1)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815067eb)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff815d8330)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff815dab57)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff815de287)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff815e0f15)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f93aa)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff8160a672)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
```
```
In drivers/char/random.c (ffffffff8160f054)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff816132ac)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81614591)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81659ac7)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816a8421)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff816ef929)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff817006ab)
Location: include/linux/sched.h:1536
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8170344a)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff8172badb)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/rtc-dev.c (ffffffff8178cef3)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff817ae6b7)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff817bf96a)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/socket.c (ffffffff81825af7)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff8182ce53)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8183a183)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff8183a87e)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff81852290)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff81888b95)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff8188b6e2)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a06cd)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818a5a6f)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff818c56b2)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff818d31f9)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81903f3d)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff8100393c)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cc84)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff81039698)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103df1b)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103f5a5)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff8106f4c0)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8106f915)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff81076374)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff8108b8fd)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
```
In kernel/exit.c (ffffffff81092bdf)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff8109a2b7)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810a127d)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__x64_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810b3334)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff819ec4b8)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c439b)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810c99e7)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810d27de)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d492f)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810d97b3)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff819ed4c9)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810d9bba)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff819ed84b)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff819ee496)
Location: include/linux/sched.h:1658
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff819ef375)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rtmutex.c (ffffffff819ef76c)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819efd6b)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In kernel/rcu/update.c (ffffffff81102584)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81107b13)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (ffffffff8110c473)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff8110f0de)
Location: include/linux/sched.h:1658
Inline: True
```
```
In kernel/time/timer.c (ffffffff81113b31)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff819f0c47)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8111d912)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81121b7c)
Location: include/linux/sched.h:1658
Inline: True
```
```
In kernel/futex.c (ffffffff811291c7)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/seccomp.c (ffffffff8116b632)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8117a1a4)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/events/uprobes.c (ffffffff811e61d5)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811ebbf8)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page_alloc.c (ffffffff811fa61a)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff811fcfef)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81207c67)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff81213243)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff812235f0)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81227ca2)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff81238da9)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/swapfile.c (ffffffff8124c1cf)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81257f3b)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff8125f300)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff819e641a)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff81280c91)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff81290bd8)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81297969)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812a16d5)
Location: include/linux/sched.h:1658
Inline: True
```
```
In fs/pipe.c (ffffffff812a3c38)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff812afa3e)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812b1393)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff812b267e)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff812d1afb)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff812d9ab9)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e796d)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e94d6)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff812ea735)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff812ed189)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffff812ef219)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff812f0eae)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff812f3904)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_getevents
  - fs/aio.c:__ia32_compat_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/dax.c (ffffffff812f6f53)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/coredump.c (ffffffff8130bebf)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff8130ea36)
Location: include/linux/sched.h:1658
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81337d07)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813444a6)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff81365800)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/namei.c (ffffffff8136ad1b)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff813a65b6)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/ecryptfs/read_write.c (ffffffff813b6f2c)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff813d8a3a)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff813dc0a0)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff813e1d4c)
Location: include/linux/sched.h:1658
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813fae05)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff81458bf0)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff81462ce4)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff8148f3ec)
Location: include/linux/sched.h:1658
Inline: True
```
```
In lib/percpu_ida.c (ffffffff814cbd28)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/pci/vpd.c (ffffffff81525692)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81537667)
Location: include/linux/sched.h:1658
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81611d18)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81613c77)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff816175c7)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff8161a1b6)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/serial/serial_core.c (ffffffff81632af6)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81643fb2)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
```
```
In drivers/char/random.c (ffffffff81648acf)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff8164d020)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff8164e23c)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff816956e3)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e46fd)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8172c3d8)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff817400a0)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81741d8a)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff8176aef2)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/rtc-dev.c (ffffffff817cf490)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff817f9014)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff818079e2)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff818706ff)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/socket.c:sock_poll
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81876c47)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81884914)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81884ff7)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff8189d957)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff818dc5d4)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff818df131)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f5499)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff818f710d)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff8191d118)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff819295d0)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8195c06e)
Location: include/linux/sched.h:1658
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff81003a1e)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ded4)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff8103a999)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103f4eb)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81040ba5)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff81075530)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81075975)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff8107c641)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81093b48)
Location: include/linux/sched.h:1671
Inline: True
```
```
In kernel/exit.c (ffffffff8109aecf)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810a2632)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810a97fd)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__x64_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810bc474)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81a27704)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810cd65b)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810d43d7)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810dc14e)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810de35f)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810e32b3)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a286f9)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810e36d5)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81a28a5b)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81a2973e)
Location: include/linux/sched.h:1671
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81a2a6b5)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rtmutex.c (ffffffff81a2aabc)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b79b)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In kernel/rcu/update.c (ffffffff8110df74)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81112bf2)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (ffffffff81117c63)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff8111a71e)
Location: include/linux/sched.h:1671
Inline: True
```
```
In kernel/time/timer.c (ffffffff81120391)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81a2bfc7)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81129212)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d29c)
Location: include/linux/sched.h:1671
Inline: True
```
```
In kernel/futex.c (ffffffff811346b7)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/seccomp.c (ffffffff81178cba)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81187174)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff811cd98f)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff811f6d25)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff811fc7a8)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page_alloc.c (ffffffff8120cd5e)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/page-writeback.c (ffffffff8120fb0c)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8121a7e7)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff81224cf3)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff81236650)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8123b482)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff8124c769)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/swapfile.c (ffffffff812606d5)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8126c5f7)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff81273a40)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81a21861)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff81295831)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (ffffffff812a5bfa)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812ac775)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812b6425)
Location: include/linux/sched.h:1671
Inline: True
```
```
In fs/pipe.c (ffffffff812b8d88)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff812c4bfe)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812c65b3)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff812c778e)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff812e6edb)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff812eefa6)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fbf7d)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fd5df)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8130080c)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff81301ed4)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffff81303ba9)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813045c7)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81308a94)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_getevents
  - fs/aio.c:__ia32_compat_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/dax.c (ffffffff8130c003)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/coredump.c (ffffffff8132171f)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff81325366)
Location: include/linux/sched.h:1671
Inline: True
```
```
In fs/ext4/dir.c (ffffffff8134ef87)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8135c5f6)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8137dbc0)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/namei.c (ffffffff813831db)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf396)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff813c51b8)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff813d047c)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff813f28ba)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff813f671a)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff813fbd3c)
Location: include/linux/sched.h:1671
Inline: True
```
```
In security/selinux/hooks.c (ffffffff814173ec)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff81475e10)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff81480964)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff814a8eb8)
Location: include/linux/sched.h:1671
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814c3361)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In drivers/pci/vpd.c (ffffffff8153b512)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154ed47)
Location: include/linux/sched.h:1671
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162ea8d)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81630d47)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff816347c7)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff81637436)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/serial/serial_core.c (ffffffff81650b96)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81662282)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
```
```
In drivers/char/random.c (ffffffff81666cef)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff8166b1a0)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff8166c3bc)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff816b5d53)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81707a92)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8174eb78)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff817640a9)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81765e9a)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff8178f482)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff817f6600)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff818298bd)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81833e5b)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81890200)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81897417)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818a4b74)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818a55f9)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff818c0205)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff81908fb4)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff8190bb70)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922dd9)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81925774)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff8194b6c8)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81958780)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8199087d)
Location: include/linux/sched.h:1671
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff810042c1)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fc47)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff8103cf9a)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041227)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81043285)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff810790c0)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81079565)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff8107fba1)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810982ec)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff8109f527)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810a72bc)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810ac08d)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__x64_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810c1c12)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81a97fca)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d5a46)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810db28c)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810e311c)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e5444)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810e9eb7)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a98ee9)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ea358)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81a99492)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81a99d88)
Location: include/linux/sched.h:1744
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81a9acad)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff810f8445)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff81a9b805)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff81117656)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8111c524)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (ffffffff81121a9f)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff81124e39)
Location: include/linux/sched.h:1744
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112ac98)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81a9c175)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81133c66)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81137d22)
Location: include/linux/sched.h:1744
Inline: True
```
```
In kernel/futex.c (ffffffff8113f6ce)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/seccomp.c (ffffffff81185beb)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81194590)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff811e2caa)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff8120eaf5)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8121407d)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page-writeback.c (ffffffff8121f02a)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8122a03b)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff812357dc)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff81247b75)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8124c999)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff8125eb9a)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff8127317e)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/swapfile.c (ffffffff8127b70e)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812879a5)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff8128f58f)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81a921db)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff812b17b8)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812c12bc)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812c8ed5)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812d3185)
Location: include/linux/sched.h:1744
Inline: True
```
```
In fs/pipe.c (ffffffff812d5981)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff812e160e)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812e3073)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff812e4320)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff813041f3)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff813107cb)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131c969)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131f26d)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff81321ae3)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff813234c2)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffff813251ac)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff81326450)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8132a71f)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff81330d88)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
```
```
In fs/dax.c (ffffffff813335b1)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/coredump.c (ffffffff81349002)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8134c02e)
Location: include/linux/sched.h:1744
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81377fc4)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8138574a)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813a4395)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813ac60d)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9c1b)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff813efa53)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb0ee)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff8141f96e)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81422ac1)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff81427edd)
Location: include/linux/sched.h:1744
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81444fc5)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814a3e3f)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff814af096)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff814d684c)
Location: include/linux/sched.h:1744
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f1a42)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In drivers/pci/vpd.c (ffffffff8156af1b)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157ec6c)
Location: include/linux/sched.h:1744
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81662675)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81664d06)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81668895)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff8166b68b)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/serial/serial_core.c (ffffffff816856dd)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81697e31)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
```
```
In drivers/char/random.c (ffffffff8169cb3a)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff816a0d94)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff816a1fdd)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff816efb8c)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81742ced)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8178a693)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff817a1e00)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a3f70)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff817cd2e8)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81837365)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff8186bd2f)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81875c4c)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff818da079)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff818e18ac)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818f028c)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818f091f)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff8190ca51)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff8196a319)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff8196dd33)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985788)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8198930a)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819afca6)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff819bd2d0)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff819fbf61)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff810042c1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/kernel/process_64.c (ffffffff810305a7)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff8103d75a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff810419b7)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810439e5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff8107a110)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8107a5b5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff81080c31)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff8109e8c0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a5ab7)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810ad8dc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b269d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__x64_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810c8162)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81acf89b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e0056)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810e519c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810ed488)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f0864)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810f5887)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81ad0839)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810f5d28)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81ad0de2)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81ad16d8)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81ad25fd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110427f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff81ad3155)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff81123a26)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81128c8e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (ffffffff8112e0bf)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff81130df9)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/time/timer.c (ffffffff81136c38)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81ad3a4c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8113fc36)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81143d2d)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/futex.c (ffffffff8114b17e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff8115914f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff81191b65)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811a0050)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff811ef527)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff8121c135)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff812218ad)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page-writeback.c (ffffffff8122caca)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81237ebb)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff81243a1c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff81255fd5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125aec9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff8126d3aa)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff81281fee)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff81284dd5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8128b1ee)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812975b5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff8129f30f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81ac996b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff812c31a8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812d320c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812da8e5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812e4d15)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/pipe.c (ffffffff812e74f1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff812f30de)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812f3de3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff812f5d60)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff81317273)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff813237ab)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f834)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8133201d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff81334046)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff81336222)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffff81337f3c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813391e0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8133d426)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff8134051c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
```
```
In fs/dax.c (ffffffff81347171)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff8134f76b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/coredump.c (ffffffff813612a2)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff813642fe)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81390364)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8139e19a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813bd205)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813c553d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff81403cbb)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff81409ac3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81414fbe)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff8143978e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8143c845)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff81441c0d)
Location: include/linux/sched.h:1737
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8145eb35)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814bea6f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff814c9d26)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff814efba5)
Location: include/linux/sched.h:1737
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8150affe)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff81513789)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8158beeb)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815a06ac)
Location: include/linux/sched.h:1737
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81684ce5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81687356)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff8168afe5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff8168dd2b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81694828)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a7d9d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff816ba9b1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff816bf8aa)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff816c3b34)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff816c4d4e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81713bbc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81766cc0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817ae2b3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff817c2ad0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c79c0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio.c (ffffffff817d1c96)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/devio.c (ffffffff817fdf5f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81868cd5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff8189db41)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff818a7a4c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff8190c059)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81913aa0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8192226c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81922871)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff8193f15e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff819a0d89)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff819a4710)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bc47f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819c0770)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819e6936)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff819f3ee0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81a32bf1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff810052cf)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__syscall_return_slowpath
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/kernel/process.c (ffffffff8104086f)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:copy_thread_tls
```
```
In arch/x86/kernel/ptrace.c (ffffffff81045432)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81047285)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff81081570)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81081a05)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff81087be0)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810a5fb8)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810ad5d2)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810b5310)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810bb11d)
Location: include/linux/sched.h:1787
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
Location: include/linux/sched.h:1787
Inline: True
```
```
In kernel/kthread.c (ffffffff810d0d62)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81bc861e)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e84a0)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810ee705)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810f9489)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa204)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810feef7)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81bc912c)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ff557)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81bc9225)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81bc989d)
Location: include/linux/sched.h:1787
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81bca631)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110ee79)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:1787
Inline: True
```
```
In kernel/locking/rtmutex.c (ffffffff81bcb13d)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff81130352)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8113758d)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/livepatch/transition.c (ffffffff8113c4dd)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff811401a1)
Location: include/linux/sched.h:1787
Inline: True
```
```
In kernel/time/timer.c (ffffffff81144a98)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81bcba50)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114eb24)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811537a1)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffff8115bce1)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff81169f8f)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811a6a6c)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b5680)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff81212333)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff812487c5)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8124e49d)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffffffff8125a558)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81266f10)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff81270b19)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff812846bd)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff81289e64)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff8129d5aa)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff812adf54)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff812b6fb3)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812be3bf)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812cabaa)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff812d361f)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81bc2065)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff812f8f28)
Location: include/linux/sched.h:1787
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
In mm/userfaultfd.c (ffffffff81308ef3)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81310e34)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff8131d964)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/pipe.c (ffffffff8131ecf5)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
```
```
In fs/ioctl.c (ffffffff8132b813)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff8132c73c)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff8132e4ed)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff813503f5)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/splice.c:wait_for_space
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff8135a773)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813696d9)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136c800)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8136e40f)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff8136ff49)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff81371c83)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff81373d2f)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813767f6)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff81386032)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_flush
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
```
```
In fs/io-wq.c (ffffffff8138af7e)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_assign_current_work
```
```
In fs/dax.c (ffffffff8138c960)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff81395efa)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/coredump.c (ffffffff813a7574)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/coredump.c:dump_skip
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff813abd39)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff813db923)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813ea03b)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8140937b)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff81411942)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff81451b17)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff81457690)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8146327e)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff814897b3)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8148ced6)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff81492961)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff814b5c21)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8151f22c)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff81528ee2)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff8154f07e)
Location: include/linux/sched.h:1787
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156a433)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
```
In block/blk-iocost.c (ffffffff81574b36)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff81632dfb)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81648f2c)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff81736284)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff8173aea6)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173cf55)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff81740004)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff817472fb)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175974d)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff8176f081)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81772f67)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/hpet.c (ffffffff81778244)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff817795f3)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff817cf68c)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818273b7)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8182a8f4)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81874383)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff8188ed62)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818916d6)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio.c (ffffffff8189c8c0)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/devio.c (ffffffff818ce6dc)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff8193c935)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff8196de41)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81977818)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff819df004)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff819e60d1)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wait_for_wmem
```
```
In net/core/datagram.c (ffffffff819f5d2e)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819f6413)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81a7a565)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81a7f281)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81a815db)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa58dc)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/tcp.c (ffffffff81aab28d)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ad4260)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81ae34c9)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/unix/af_unix.c (ffffffff81b27771)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/mptcp/protocol.c (ffffffff81bac384)
Location: include/linux/sched.h:1787
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/process.c (ffffffff810407bf)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff81044e92)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81046ad5)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067133)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068cc8)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/kernel/uprobes.c (ffffffff81081010)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/mm/fault.c (ffffffff8108830e)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810a1991)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a8ca2)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810b0500)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b63cd)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched.h:1848
Inline: True
```
```
In kernel/kthread.c (ffffffff810cb818)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81c41403)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e6090)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810ec545)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810f7779)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f8654)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810fd957)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81c41f3c)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810fe0b7)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81c42050)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81c426d9)
Location: include/linux/sched.h:1848
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81c43768)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110c056)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:1848
Inline: True
```
```
In kernel/locking/rtmutex.c (ffffffff81c43fcd)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff8112c194)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81132bbb)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/livepatch/transition.c (ffffffff81136bed)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/entry/common.c (ffffffff8113b8c0)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/freezer.c (ffffffff8113c511)
Location: include/linux/sched.h:1848
Inline: True
```
```
In kernel/time/timer.c (ffffffff81141e43)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81c448d0)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114ad94)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114fb91)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffff811578c1)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff811666cf)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811a40e9)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b2f5e)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff81213073)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff81252ed5)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81258a8d)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffffffff812646dc)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81271960)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
```
```
In mm/shmem.c (ffffffff8127bbc5)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff8128e9e0)
Location: include/linux/sched.h:1848
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
Location: include/linux/sched.h:1848
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
In mm/mmap.c (ffffffff812a89f9)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff812b998e)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff812c1ef3)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812c9fe0)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812d67ca)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff812defb3)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81c3b146)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/memcontrol.c (ffffffff81304e28)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81314c54)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81327abb)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff8132a215)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/ioctl.c (ffffffff81336dd3)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff81337d66)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff81339d73)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff8135e62f)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
```
```
In fs/remap_range.c (ffffffff81366305)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff81367746)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813769b9)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137a115)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8137ba41)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff8137dc52)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff8137fa30)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff81381c3e)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff81384473)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff8138aa5a)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqpoll_wait_sq
  - fs/io_uring.c:io_sqpoll_wait_sq
  - fs/io_uring.c:io_uring_flush
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/io-wq.c (ffffffff8139c1cc)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/dax.c (ffffffff8139e0f0)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff813a7c1a)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/coredump.c (ffffffff813b8dcb)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/coredump.c:dump_skip
  - fs/coredump.c:dump_skip
  - fs/coredump.c:dump_skip
  - fs/coredump.c:dump_skip
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff813bd209)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff813ed388)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813fc41b)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8141b882)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff81424df2)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e094)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff81473a50)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8147eace)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff814a6ddd)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814aa4c8)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff814b020d)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff814d3901)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8153c0b3)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff81545e90)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff8156cc77)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-cgroup.c (ffffffff81584e95)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
```
In block/blk-iocost.c (ffffffff8159186a)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff81657f4b)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8166dfe8)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff81752dc7)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81756fe2)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81759003)
Location: include/linux/sched.h:1848
Inline: True
```
```
In drivers/tty/tty_port.c (ffffffff8175bf2d)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81762c3b)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff81774cd1)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81789959)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff8178df57)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/hpet.c (ffffffff81792cc0)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81793d64)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff817e3c62)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837e57)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b2e0)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81882f23)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff8189b9e2)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189f86f)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio.c (ffffffff818ab4dd)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/devio.c (ffffffff818d964d)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff819428e9)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81974f81)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff8197c49c)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff819de898)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/socket.c:sock_poll
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff819e54a7)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/sock.c:sock_wait_for_wmem
```
```
In net/core/datagram.c (ffffffff819f57f9)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819f6065)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81a833c5)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81a88cc8)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81a8b1da)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafee9)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
```
```
In net/ipv4/tcp.c (ffffffff81ab6ad3)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ae07a0)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81af08b9)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/unix/af_unix.c (ffffffff81b3604f)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff81bb679c)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bbde66)
Location: include/linux/sched.h:1848
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/process.c (ffffffff810421af)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff81046e69)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81048505)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810676a2)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81069322)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/kernel/uprobes.c (ffffffff81081e30)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/mm/fault.c (ffffffff81088e25)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810a2720)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a9c54)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810b1a80)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b56b0)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__do_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched.h:1870
Inline: True
```
```
In kernel/kthread.c (ffffffff810cd098)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81c33376)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e805a)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810eeee8)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810f9c89)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa7b4)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810ffd37)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81c33eac)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff81100497)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81c33fc0)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81c34597)
Location: include/linux/sched.h:1870
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81c354f7)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8110de8a)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:1870
Inline: True
```
```
In kernel/locking/rtmutex.c (ffffffff81c360e6)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff8112c6c4)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81133f4b)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/livepatch/transition.c (ffffffff81137e6f)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/entry/common.c (ffffffff8113cb95)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/freezer.c (ffffffff8113d771)
Location: include/linux/sched.h:1870
Inline: True
```
```
In kernel/time/timer.c (ffffffff81142c43)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81c37b40)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114c251)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81150fd2)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffff81158d11)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff8116746f)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811a4a07)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b37ee)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff81215523)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff81257215)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8125cf8d)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffffffff812688eb)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81276c50)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
```
```
In mm/shmem.c (ffffffff81280d2f)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff81294070)
Location: include/linux/sched.h:1870
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
Location: include/linux/sched.h:1870
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
In mm/mmap.c (ffffffff812adea6)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff812c217b)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81c2d7b0)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff812c8db2)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812d0a42)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812dd97d)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff812e67a3)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff8130be28)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff8131b347)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8132d8ab)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff813301c5)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/ioctl.c (ffffffff8133cf33)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff8133e4b7)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff8134032b)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff813646bc)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
```
```
In fs/remap_range.c (ffffffff8136cd0c)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8136e186)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d212)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380cf1)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff813821c1)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff813848d2)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff813866af)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff81388ca5)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8138b0c3)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff813a18df)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/io-wq.c (ffffffff813a31ef)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/dax.c (ffffffff813a51b6)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff813aec7c)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff813b058b)
Location: include/linux/sched.h:1870
Inline: True
```
```
In fs/coredump.c (ffffffff813bf06e)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff813c4359)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff813f39ee)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff81402ca1)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff81421a96)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff8142baf6)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff814734d5)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff8147949c)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81484652)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff814acd37)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814b0d61)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff814b605d)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff814da381)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff815447a3)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff8154e520)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff81574b17)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-cgroup.c (ffffffff8158db11)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff815986cb)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8163a76b)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81650538)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff81736d94)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff8173a6c2)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173cf83)
Location: include/linux/sched.h:1870
Inline: True
```
```
In drivers/tty/tty_port.c (ffffffff8173fdcd)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff817468f8)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757d81)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff8176d1f9)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81770907)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/char/hpet.c (ffffffff817759e0)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81776941)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff817c80a2)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181b142)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e4ea)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81865771)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff8187f166)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818822ff)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818902ee)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/usb/core/devio.c (ffffffff818bc716)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81926109)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81958fb3)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff819606dd)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff819c4838)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/socket.c:sock_poll
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff819cb54b)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819db999)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819dc0d4)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81a6c495)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81a70b7a)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81a74509)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c038)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81aa1c95)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81acc78c)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81adbf56)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81b23c2f)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff81ba57a5)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bae14c)
Location: include/linux/sched.h:1870
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/process.c (ffffffff810484ff)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104d281)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8104ee45)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071a42)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073665)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/kernel/uprobes.c (ffffffff81090e90)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/mm/fault.c (ffffffff81098294)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810b3e1d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810bb782)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810c3b70)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810c7cb0)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
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
Location: include/linux/sched.h:1987
Inline: True
```
```
In kernel/kthread.c (ffffffff810e0268)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81d51cbc)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810ff71a)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff81109675)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff81112bd9)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff81115564)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff8111be13)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81d5284d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff8111c4fe)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81d5295c)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81d52f15)
Location: include/linux/sched.h:1987
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81d53cf3)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8112d65f)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:1987
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d54953)
Location: include/linux/sched.h:1987
Inline: True
```
```
In kernel/rcu/update.c (ffffffff8114d3c4)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8115641d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/livepatch/transition.c (ffffffff8115abc2)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/entry/common.c (ffffffff8115fcb5)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/freezer.c (ffffffff811608fe)
Location: include/linux/sched.h:1987
Inline: True
```
```
In kernel/time/timer.c (ffffffff81166143)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81d563b5)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81170018)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811753a2)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffff8117dbe1)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff8118cfdf)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811ce1ff)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811dd5be)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff8124bb15)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff81292fa5)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81298e9c)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/oom_kill.c (ffffffff812a3812)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff812a537d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff812b4580)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
```
```
In mm/shmem.c (ffffffff812bf177)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff812d45ed)
Location: include/linux/sched.h:1987
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
Location: include/linux/sched.h:1987
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
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff81305af9)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81d4c086)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff8130ddd3)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8131611d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81324b3d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff8132e6c3)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff81357118)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81368237)
Location: include/linux/sched.h:1987
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
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff8137d985)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/readdir.c (ffffffff8138be47)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff8138dcfb)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff813b34ac)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
```
```
In fs/remap_range.c (ffffffff813bb9cc)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff813bd255)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca292)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cdcb4)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff813cf431)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff813d1b72)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff813d3957)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813d5fb7)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff813d8643)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff813f02eb)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sqd_handle_event
  - fs/io_uring.c:io_sqd_handle_event
  - fs/io_uring.c:io_sqd_handle_event
  - fs/io_uring.c:io_sqd_handle_event
```
```
In fs/io-wq.c (ffffffff813f16ec)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/dax.c (ffffffff813f497b)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff813fe81c)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff8140017b)
Location: include/linux/sched.h:1987
Inline: True
```
```
In fs/coredump.c (ffffffff8140ee9e)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff81413988)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff81445ab1)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff81455371)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff814743ed)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff8147f996)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca0ca)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff814d0adb)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbcd2)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff81505224)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81509293)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8150e904)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff81533281)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff815a4f43)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff815aee70)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff815d9051)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-cgroup.c (ffffffff815f3580)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff815ffeb5)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff816ab2ae)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816c2278)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/tty/tty_io.c (ffffffff817b776d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff817bb652)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff817bd613)
Location: include/linux/sched.h:1987
Inline: True
```
```
In drivers/tty/tty_port.c (ffffffff817c056d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff817c78e8)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff817db5f0)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff817f2b89)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff817f6320)
Location: include/linux/sched.h:1987
Inline: True
```
```
In drivers/char/hpet.c (ffffffff817fb740)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff817fc901)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81852592)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a55b7)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a8975)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff818f4af8)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff8191114a)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81913ca6)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923ee1)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/usb/core/devio.c (ffffffff81952737)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff819c9079)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff819fe753)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81a0837d)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81a73c98)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/socket.c:sock_poll
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81a7abdb)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81a8bbe9)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81a8c314)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81b25af3)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81b2a49a)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81b2e750)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b578d8)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81b5e7a5)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81b8b01c)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81b9b185)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc808a)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81be8071)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff81c73308)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81c7b3f6)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/process.c (ffffffff8105183e)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff81058431)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8105a095)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107fb14)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081abf)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/kernel/uprobes.c (ffffffff810a1f20)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/mm/fault.c (ffffffff810aaeee)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810ca107)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810d21c1)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810db2a6)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810def87)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
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
Location: include/linux/sched.h:2009
Inline: True
```
```
In kernel/kthread.c (ffffffff810f9eb0)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81f2221f)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff8112503c)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/build_policy.c (ffffffff81134e1b)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:check_preempt_curr_rt
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/sched/build_utility.c (ffffffff81140192)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:__wait_for_common
  - kernel/sched/build_utility.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81f23b59)
Location: include/linux/sched.h:2009
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81f24d39)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff81f258be)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:2009
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f264e0)
Location: include/linux/sched.h:2009
Inline: True
```
```
In kernel/rcu/update.c (ffffffff81174036)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_wait_gp
```
```
In kernel/rcu/tree.c (ffffffff8117d97f)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/livepatch/transition.c (ffffffff81184489)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/entry/common.c (ffffffff8118a1bd)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/freezer.c (ffffffff81193676)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/freezer.c:freezing_slow_path
```
```
In kernel/time/timer.c (ffffffff81199cc3)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81f2852f)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811a4558)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a9cef)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex/requeue.c (ffffffff811b64d8)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/futex/waitwake.c (ffffffff811b76c3)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait
  - kernel/futex/waitwake.c:futex_wait
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_multiple
```
```
In kernel/kexec_core.c (ffffffff811bc22f)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff812024aa)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8121433c)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched.h:2009
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff81292ccf)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff812e8a1b)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff812ef760)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2_killable
  - mm/filemap.c:folio_wait_private_2_killable
```
```
In mm/oom_kill.c (ffffffff812fb74e)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff812fdec0)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8131055d)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/shmem.c (ffffffff8131ae36)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff813335a2)
Location: include/linux/sched.h:2009
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
Location: include/linux/sched.h:2009
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
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/vmalloc.c (ffffffff81360708)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_area_alloc_pages
```
```
In mm/page_alloc.c (ffffffff81371d3c)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff81f1b9f6)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff81377162)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813812b6)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff813932d3)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff8139ea82)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff813caa89)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff813e5bc7)
Location: include/linux/sched.h:2009
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
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff813fe025)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/readdir.c (ffffffff8140d3d9)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff8140f078)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff81437cc6)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/remap_range.c (ffffffff81441c2d)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff81443481)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8145232c)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81455d9a)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff81458212)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff8145abe0)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff8145ce41)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff8145dc97)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff81462b06)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/dax.c (ffffffff81467fd5)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81472339)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff81473f9e)
Location: include/linux/sched.h:2009
Inline: True
```
```
In fs/coredump.c (ffffffff814845ce)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8148b181)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff814c1af7)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff814d2bee)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff814f62d2)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff815029e9)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff81555de6)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff8155d665)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8156994c)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff81596be3)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8159afff)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff815a0b05)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff815c5604)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8164bb8d)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff81657540)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff8168bdbe)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll
  - block/blk-mq.c:blk_mq_poll
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-cgroup.c (ffffffff816a4b07)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff816b255a)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff816d6ded)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_sqd_handle_event
  - io_uring/io_uring.c:io_sqd_handle_event
  - io_uring/io_uring.c:io_sqd_handle_event
  - io_uring/io_uring.c:io_sqd_handle_event
```
```
In io_uring/io-wq.c (ffffffff816da7d6)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_wqe_worker
```
```
In drivers/pci/vpd.c (ffffffff817ce335)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff817e7ba8)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/pci/vgaarb.c (ffffffff817f40f9)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_get
  - drivers/pci/vgaarb.c:vga_get
```
```
In drivers/tty/tty_io.c (ffffffff818f2a27)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff818f6613)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff818f9953)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:set_termios
```
```
In drivers/tty/tty_port.c (ffffffff818fccf9)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff819049f8)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191ac3f)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff819336d9)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81934314)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/char/hpet.c (ffffffff8193aba9)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff8193b681)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81998462)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ef1fd)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f26c8)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/net/tun.c (ffffffff81a6157b)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69214)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79871)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/usb/core/devio.c (ffffffff81aac363)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81b2a29f)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81b65d21)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81b70718)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81be6f1c)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/socket.c:sock_poll
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81beeaff)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81c01445)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81c01bb3)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81cae699)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81cb4097)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81cb91e8)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce58bd)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81ced199)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81d1ae1e)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81d2cfdc)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5d69a)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81d7f991)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff81e17078)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81e20471)
Location: include/linux/sched.h:2009
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/process.c (ffffffff8105eebe)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106525e)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:get_flags
```
```
In arch/x86/kernel/step.c (ffffffff81067aa5)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091c04)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810944df)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/kernel/uprobes.c (ffffffff810ba010)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/mm/fault.c (ffffffff810c4be4)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810e7771)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810f0c35)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810fb506)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810ffd27)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
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
Location: include/linux/sched.h:2036
Inline: True
```
```
In kernel/kthread.c (ffffffff8111cc00)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff820ccacb)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff8114e2ac)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/build_policy.c (ffffffff8115f33b)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:check_preempt_curr_rt
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/sched/build_utility.c (ffffffff8116c402)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff820cf026)
Location: include/linux/sched.h:2036
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff820d03c0)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff820d12a4)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:2036
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d1fc1)
Location: include/linux/sched.h:2036
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811aa09d)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_wait_gp
```
```
In kernel/rcu/tree.c (ffffffff811b859d)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/livepatch/transition.c (ffffffff811bfd5f)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/entry/common.c (ffffffff811c66fd)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/freezer.c (ffffffff811d0fe6)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/freezer.c:freezing_slow_path
```
```
In kernel/time/timer.c (ffffffff811d8363)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff820d41af)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811e3e78)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e9c4f)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex/requeue.c (ffffffff811f7618)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/futex/waitwake.c (ffffffff811f8853)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait
  - kernel/futex/waitwake.c:futex_wait
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_multiple
```
```
In kernel/kexec_core.c (ffffffff811fe45f)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8124a08f)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8125de4c)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched.h:2036
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff812ed756)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff8135277b)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8135a4c0)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/oom_kill.c (ffffffff8136585e)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff81368884)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81383bcd)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/shmem.c (ffffffff8138ec01)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff813aa2a7)
Location: include/linux/sched.h:2036
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
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff813ccba6)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/vmalloc.c (ffffffff813e2883)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813ef51c)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff820c3986)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff813f4762)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813ffaf9)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81411a64)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff8141dca6)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff8144fac9)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff8146d6c6)
Location: include/linux/sched.h:2036
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
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff81487c55)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/readdir.c (ffffffff81497e99)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff81499c18)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff814c5b26)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/remap_range.c (ffffffff814d0f0d)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff814d2a31)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e10c4)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e4d2a)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff814e7b42)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff814ea170)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/eventfd.c (ffffffff814ec50a)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff814ed6f3)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff814f3196)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/dax.c (ffffffff814f831b)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81503e31)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815061f0)
Location: include/linux/sched.h:2036
Inline: True
```
```
In fs/coredump.c (ffffffff81517aae)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8151f1b9)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff81559dae)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8156b79e)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8159069f)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff8159d4e9)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff815f74de)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff815ff6b5)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d585)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff8163fae8)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8164434f)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8164a488)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff816721f4)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff81704d8d)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff817119c0)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff81741c93)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_classic
  - block/blk-mq.c:blk_mq_poll_classic
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq.c:blk_mq_poll_hybrid
```
```
In block/blk-cgroup.c (ffffffff81763897)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff81771a9f)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff81791b71)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/sqpoll.c (ffffffff8179ac46)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
```
```
In io_uring/io-wq.c (ffffffff817a68c6)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_wqe_worker
```
```
In drivers/pci/vpd.c (ffffffff818edde5)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190d248)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/pci/vgaarb.c (ffffffff8191e7d8)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_get
  - drivers/pci/vgaarb.c:vga_get
```
```
In drivers/tty/tty_io.c (ffffffff81a4aff2)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81a4f032)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a52b82)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:set_termios
```
```
In drivers/tty/tty_port.c (ffffffff81a563c9)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81a5eae8)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a769d5)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81a921f4)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81a93f44)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/char/hpet.c (ffffffff81a9afe9)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81a9bd41)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81b09512)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c72d)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b7059b)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/net/tun.c (ffffffff81bec8db)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfbd34)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff81c33960)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81cbdf1f)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81d00f0f)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81d0d623)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81d92efc)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/socket.c:sock_poll
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81d9b14f)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81db0795)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81db0f73)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81e6bcd7)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81e722f7)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81e78069)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8abd)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81eb10c9)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81ee23be)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81ef4b13)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27d9a)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81f4d681)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff81feec33)
Location: include/linux/sched.h:2036
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff793c)
Location: include/linux/sched.h:2036
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/process.c (ffffffff810605be)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff81066aac)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:get_flags
```
```
In arch/x86/kernel/step.c (ffffffff81069355)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094b4d)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109746f)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/kernel/uprobes.c (ffffffff810bd1e0)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/mm/fault.c (ffffffff810c8174)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810f32f3)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810fcbe5)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff8110732d)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8110bdb7)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
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
Location: include/linux/sched.h:2044
Inline: True
```
```
In kernel/kthread.c (ffffffff81129d25)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/vhost_task.c (ffffffff81139258)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_fn
  - kernel/vhost_task.c:vhost_task_fn
```
```
In kernel/sched/core.c (ffffffff82150e50)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff8115cb5f)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/build_policy.c (ffffffff8116fa2b)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:check_preempt_curr_rt
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/sched/build_utility.c (ffffffff8117cb62)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff821533e3)
Location: include/linux/sched.h:2044
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff82154750)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff82155609)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:2044
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff821563e2)
Location: include/linux/sched.h:2044
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811bbfcd)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_wait_gp
```
```
In kernel/rcu/tree.c (ffffffff811ca4cd)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/livepatch/transition.c (ffffffff811d283f)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/entry/common.c (ffffffff811d931d)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/freezer.c (ffffffff811e5256)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/freezer.c:freezing_slow_path
```
```
In kernel/time/timer.c (ffffffff811ec793)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff8215849a)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811f84e8)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fe33f)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex/requeue.c (ffffffff8120bdb2)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/futex/waitwake.c (ffffffff8120d013)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait
  - kernel/futex/waitwake.c:futex_wait
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_multiple
```
```
In kernel/kexec_core.c (ffffffff81213729)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8126137f)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff812750bc)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched.h:2044
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8131a0a6)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff8138398b)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8138bdd4)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/oom_kill.c (ffffffff81397cfe)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff8139aa24)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff813b567d)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/shmem.c (ffffffff813c1fd4)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff813dd542)
Location: include/linux/sched.h:2044
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
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff8140148e)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/vmalloc.c (ffffffff81417440)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff81423095)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff8214776b)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff81427d2a)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81432989)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81444ef4)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff8145269e)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff814854f9)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff814a21a7)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814ba72f)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff814bcb15)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/readdir.c (ffffffff814ccdb3)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff814cece8)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff814fcb3a)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/remap_range.c (ffffffff81507a3f)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8150933e)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81517964)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151bd7a)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8151ddf5)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff81520f10)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/userfaultfd.c (ffffffff81524703)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff81529f53)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/dax.c (ffffffff8152fae3)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff8153b8b7)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/read_metadata.c (ffffffff8153d522)
Location: include/linux/sched.h:2044
Inline: True
```
```
In fs/coredump.c (ffffffff8154f39e)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff815572e4)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/ext4/dir.c (ffffffff81591bdc)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff815a364e)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff815c7852)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff815d3d35)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f567)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff81637695)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8164543f)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff81677fbe)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8167c78e)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff816829ea)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff816aa739)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8173efad)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff8174c580)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e781)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - crypto/jitterentropy-testing.c:jent_raw_hires_read
  - crypto/jitterentropy-testing.c:jent_raw_hires_read
```
```
In block/blk-mq.c (ffffffff8177d2d1)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/blk-cgroup.c (ffffffff817a2936)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff817b0d6a)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff817d0e16)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_run_task_work_sig
  - io_uring/io_uring.c:io_iopoll_check
```
```
In io_uring/sqpoll.c (ffffffff817dbcf6)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
```
```
In io_uring/io-wq.c (ffffffff817e783c)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_wq_worker
```
```
In rust/helpers.c (ffffffff81805bc5)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_signal_pending
  - rust/helpers.c:rust_helper_signal_pending
```
```
In drivers/pci/vpd.c (ffffffff819312c5)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff819508c8)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/pci/vgaarb.c (ffffffff81961eb8)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_get
  - drivers/pci/vgaarb.c:vga_get
```
```
In drivers/tty/tty_io.c (ffffffff81a95070)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81a99245)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a9cf05)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:set_termios
```
```
In drivers/tty/tty_port.c (ffffffff81aa09a9)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81aa9188)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac1475)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81adda9c)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81adea74)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/char/hpet.c (ffffffff81ae6879)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81ae76a1)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81b57522)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbfdbd)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc3e8f)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/net/tun.c (ffffffff81c44ddb)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6137c)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff81c9a6ac)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81d2582f)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81d6a26c)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81d76543)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81e01300)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/socket.c:sock_poll
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81e0a336)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81e20c55)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81e21460)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81ec7d37)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81ece467)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81ed41e9)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f0733d)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81f0f759)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81f41ebe)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81f544dc)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87956)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff81fad116)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff8206b676)
Location: include/linux/sched.h:2044
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82073dcc)
Location: include/linux/sched.h:2044
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/x86/kernel/process.c (ffffffff8106763f)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106df2c)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:get_flags
```
```
In arch/x86/kernel/step.c (ffffffff810707c5)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:user_enable_block_step
  - arch/x86/kernel/step.c:user_enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109c02d)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e9df)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
```
In arch/x86/kernel/uprobes.c (ffffffff810c4360)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/mm/fault.c (ffffffff810d064d)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810fc6a3)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff811071e0)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff81110c7d)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81115767)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__do_sys_pause
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
Location: include/linux/sched.h:1946
Inline: True
```
```
In kernel/kthread.c (ffffffff81134394)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/vhost_task.c (ffffffff81144018)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_fn
  - kernel/vhost_task.c:vhost_task_fn
```
```
In kernel/sched/core.c (ffffffff82233c65)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wakeup_preempt
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff81167fa8)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup_fair
```
```
In kernel/sched/build_policy.c (ffffffff8117cf7b)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:wakeup_preempt_dl
  - kernel/sched/build_policy.c:wakeup_preempt_rt
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/sched/build_utility.c (ffffffff8118a942)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr_irq
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:do_wait_intr
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff82236223)
Location: include/linux/sched.h:1946
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff82237590)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff82238449)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/sched.h:1946
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff82239222)
Location: include/linux/sched.h:1946
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811cc430)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_wait_gp
```
```
In kernel/rcu/tree.c (ffffffff811de488)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
```
```
In kernel/livepatch/transition.c (ffffffff811e74bf)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_copy_process
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/entry/common.c (ffffffff811eec5d)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_trace_enter
```
```
In kernel/freezer.c (ffffffff811fafe6)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/freezer.c:freezing_slow_path
```
```
In kernel/time/timer.c (ffffffff812027b3)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff8223b30a)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8120e688)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812146cf)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex/requeue.c (ffffffff81223347)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/futex/waitwake.c (ffffffff812246f7)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:__futex_wait
  - kernel/futex/waitwake.c:__futex_wait
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_multiple
```
```
In kernel/kexec_core.c (ffffffff8122b659)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8127b57f)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8128f9e3)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/irq_work.c (0)
Location: include/linux/sched.h:1946
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8133ba3a)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff813acdeb)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff813b5944)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/oom_kill.c (ffffffff813c1b2e)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff813c495f)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff813de66d)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/shmem.c (ffffffff813ecd49)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff814074a2)
Location: include/linux/sched.h:1946
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
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff8142dacd)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/vmalloc.c (ffffffff81443f50)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff8144ffc5)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff82229fa7)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff8146153b)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8146bda9)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8147550c)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffffffff8148cc9e)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffff814b46d9)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff814d342b)
Location: include/linux/sched.h:1946
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
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/pipe.c (ffffffff814eefc5)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/readdir.c (ffffffff814ff3a3)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff81501628)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/splice.c (ffffffff8153176a)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:splice_from_pipe_next
```
```
In fs/remap_range.c (ffffffff8153c1c0)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8153e25e)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154bd44)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8155037a)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff815523d5)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
```
```
In fs/signalfd.c (ffffffff81555550)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_dequeue
  - fs/signalfd.c:signalfd_dequeue
```
```
In fs/userfaultfd.c (ffffffff8155b1f3)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8155ee23)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/dax.c (ffffffff815649c3)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81570b94)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/read_metadata.c (ffffffff81572982)
Location: include/linux/sched.h:1946
Inline: True
```
```
In fs/coredump.c (ffffffff815851de)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8158d814)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/task_mmu.c (ffffffff8159bd8f)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
```
```
In fs/ext4/dir.c (ffffffff815ca94c)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff815dc48e)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff815f963e)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_interrupted
```
```
In fs/ext4/namei.c (ffffffff8160c3a5)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff81668a74)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff81670b85)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8167e961)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff816b437e)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff816b8b5e)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff816bedea)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - ipc/mqueue.c:wq_sleep
  - ipc/mqueue.c:wq_sleep
```
```
In security/selinux/hooks.c (ffffffff816e778c)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8177fe2d)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff8178e490)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff817bf661)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/blk-cgroup.c (ffffffff817e647b)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff817f4b7a)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff8181396a)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_run_task_work_sig
  - io_uring/io_uring.c:io_iopoll_check
```
```
In io_uring/sqpoll.c (ffffffff81820076)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
  - io_uring/sqpoll.c:io_sqd_handle_event
```
```
In io_uring/io-wq.c (ffffffff8182d64b)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_wq_worker
```
```
In rust/helpers.c (ffffffff81842935)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_signal_pending
  - rust/helpers.c:rust_helper_signal_pending
```
```
In drivers/pci/vpd.c (ffffffff81979de5)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81999d28)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
```
```
In drivers/pci/vgaarb.c (ffffffff819ab4f8)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_get
  - drivers/pci/vgaarb.c:vga_get
```
```
In drivers/tty/tty_io.c (ffffffff81ae7a60)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:iterate_tty_write
  - drivers/tty/tty_io.c:iterate_tty_write
```
```
In drivers/tty/n_tty.c (ffffffff81aebe96)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81aef9d5)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:set_termios
```
```
In drivers/tty/tty_port.c (ffffffff81af3409)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81afbc48)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b142b5)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81b30e8c)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81b31e94)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/char/hpet.c (ffffffff81b39c09)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff81b3aaa2)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff81bafb12)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c1453d)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c186af)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb0a8b)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
```
```
In drivers/net/tun.c (ffffffff81cfa93b)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/tun.c:tun_ring_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d17d5c)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff81d4f27c)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff81ddb59f)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81e20f1b)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81e2d773)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81ebdcb0)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/socket.c:sock_poll
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81ec6d28)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff81edeb25)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81edf1f8)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/netlink/af_netlink.c (ffffffff81f8b149)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81f91c97)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ethtool/ioctl.c (ffffffff81f97bf9)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb682)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81fd3949)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff82007d4e)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff8201a71a)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/af_inet.c:inet_wait_for_connect
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204eff3)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/unix/af_unix.c (ffffffff8207b585)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/xdp/xsk.c (ffffffff8213e063)
Location: include/linux/sched.h:1946
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff821482ff)
Location: include/linux/sched.h:1946
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
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
In arch/arm64/kernel/fpsimd.c (ffff800010087948)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:sve_sync_from_fpsimd_zeropad
  - arch/arm64/kernel/fpsimd.c:sve_sync_to_fpsimd
  - arch/arm64/kernel/fpsimd.c:fpsimd_sync_to_sve
  - arch/arm64/kernel/fpsimd.c:sve_free
```
```
In arch/arm64/kernel/process.c (ffff800010089524)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:__switch_to
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008efc4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
  - arch/arm64/kernel/ptrace.c:sve_init_header_from_task
  - arch/arm64/kernel/ptrace.c:sve_init_header_from_task
```
```
In arch/arm64/kernel/sys_compat.c (ffff8000100a16a8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/arm64/kernel/sys_compat.c:compat_arm_syscall
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff8000100a8a0c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:emulate_swpX
```
```
In arch/arm64/mm/fault.c (ffff800010da9128)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_page_fault
```
```
In virt/kvm/kvm_main.c (ffff8000100b7414)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_check_block
```
```
In virt/kvm/arm/arm.c (ffff8000100c6ae4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
```
In kernel/fork.c (ffff8000100f36f0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffff8000100fbbac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffff800010109470)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffff80001010e4d8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__arm64_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffff800010127d28)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffff800010da1784)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffff800010144d20)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffff80001014e0c8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffff800010152464)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffff800010158510)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffff800010da278c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffff8000101593a0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffff800010da28cc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffff800010da320c)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/locking/semaphore.c (ffff800010da4b68)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffff800010169b54)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex.c (ffff800010da5938)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffff800010188cb8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffff80001018e91c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/freezer.c (ffff800010197fd4)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/time/timer.c (ffff80001019f180)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffff800010da65e8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffff8000101a984c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae188)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/futex.c (ffff8000101b9440)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffff8000101c8780)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffff80001020956c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffff800010217884)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffff800010272d20)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffff8000102a7a8c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffff8000102ae2f8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffff8000102bb6ac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffff8000102c8c2c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffff8000102d5c30)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffff8000102ed578)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffff8000102f25e4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffff8000103044ac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffff80001031a744)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffff80001031f14c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffff8000103265c4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffff800010335400)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/ksm.c (ffff80001033e97c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffff800010365d28)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffff800010378d00)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffff80001037ff44)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffff80001038d7c8)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/pipe.c (ffff800010390210)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffff80001039de34)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffff8000103a0088)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffff8000103a2ebc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffff8000103cf638)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffff8000103dcafc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ec15c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ef744)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffff8000103f27d0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffff8000103f4088)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffff8000103f6480)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffff8000103f721c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffff8000103fcd98)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_getevents_time32
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_getevents
```
```
In fs/io_uring.c (ffff800010405cf4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
```
In fs/dax.c (ffff80001040746c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffff800010411170)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/coredump.c (ffff800010427874)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffff80001042b5f8)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/ext4/dir.c (ffff800010462c70)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffff800010471768)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffff800010493f10)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffff80001049d0a0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2470)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffff8000104e9f68)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffff8000104f6600)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffff80001051fcc8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffff80001052460c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffff80001052a45c)
Location: include/linux/sched.h:1737
Inline: True
```
```
In security/selinux/hooks.c (ffff80001055411c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffff8000105b7ae0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffff8000105c590c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffff8000105ed97c)
Location: include/linux/sched.h:1737
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060e984)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffff800010617cb0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffff8000106f0f8c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010708f5c)
Location: include/linux/sched.h:1737
Inline: True
```
```
In drivers/tty/tty_io.c (ffff80001085217c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffff800010856ff8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffff8000108599e0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffff80001085ecfc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffff800010868b30)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffff80001087f194)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffff8000108aacfc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffff8000108b0d34)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffff8000108b789c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffff800010905208)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/misc/vexpress-syscfg.c (ffff80001092be8c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/dma-buf/dma-fence.c (ffff80001096747c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffff8000109c0448)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffff8000109dd690)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a00108)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffff800010a31874)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffff800010aaa7ec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffff800010aecdc8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffff800010afc880)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffff800010ba1110)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffff800010bab504)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffff800010bbcd88)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffff800010bbd5d4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffff800010bde2a4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffff800010c4f488)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffff800010c53a70)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6de24)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffff800010c70bec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffff800010c99e90)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffff800010cab3f0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffff800010cf2380)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/arm/kernel/ptrace.c (c030d184)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
```
```
In arch/arm/kernel/traps.c (c030fb64)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:arm_syscall
```
```
In arch/arm/kernel/swp_emulate.c (c0315fac)
Location: include/linux/sched.h:1737
Inline: True
```
```
In arch/arm/mm/fault.c (c0e9f998)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_page_fault
```
```
In arch/arm/common/bL_switcher.c (c0326ebc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
```
```
In kernel/fork.c (c0351d18)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (c0359af0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (c0362f94)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (c03665d0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (c037b098)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (c0e99858)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (c0392ae4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (c039ca60)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (c039f240)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (c03a60bc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (c0e9a844)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (c03a68ac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (c0e9aad4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (c0e9b99c)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/locking/semaphore.c (c0e9cd40)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (c03b5ddc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex.c (c0e9d814)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (c03d751c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (c03dcf00)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/freezer.c (c03e303c)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/time/timer.c (c03e9054)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (c0e9e3ec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (c03f5200)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (c03f90f8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (c0402658)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (c040f6fc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (c0448350)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (c045b790)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (c04a53ec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (c04d6b7c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (c04db868)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page-writeback.c (c04e7fe4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (c04f7054)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (c04fdee0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (c0511494)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:compact_unlock_should_abort
```
```
In mm/gup.c (c05147a0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (c0522bec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (c0534d20)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (c0537a50)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c053e044)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/ksm.c (c0544d84)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (c055770c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (c05641f4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (c056abb8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (c0574a38)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
```
```
In fs/pipe.c (c0576c9c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (c058313c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (c05846f4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (c0585bcc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (c05a94d8)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/buffer.c (c05b5f64)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (c05c333c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (c05c4ff4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (c05c66b4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/signalfd.c (c05c8ea4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (c05caf68)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (c05cb7f4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (c05d1c5c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_getevents_time32
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
```
```
In fs/io_uring.c (c05d74c8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
```
In fs/verity/enable.c (c05dd7cc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/coredump.c (c05f06fc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (c05f40a4)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/ext4/dir.c (c0622ec0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (c0632630)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (c0655548)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (c065eec0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (c06a7ef8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (c06b411c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (c06dbab4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (c06df3d4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (c06e3154)
Location: include/linux/sched.h:1737
Inline: True
```
```
In security/selinux/hooks.c (c07072e8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (c076669c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (c0772738)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (c079b2b8)
Location: include/linux/sched.h:1737
Inline: True
```
```
In block/blk-cgroup.c (c07b9198)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (c07c3014)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (c088b9c0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/tty/tty_io.c (c095ce70)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (c095f3a0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (c09632c0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (c0966040)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (c096de2c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (c0982a5c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (c09a7090)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (c09aa5cc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (c09b0ab4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (c09eeffc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/misc/vexpress-syscfg.c (c0a0a530)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/dma-buf/dma-fence.c (c0a3de30)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (c0a8d66c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (c0ac5e0c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (c0adcd2c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (c0b05450)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/rtc/dev.c (c0b892b8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (c0bd3988)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (c0bdd1fc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In sound/core/control.c (c0c8767c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_read
```
```
In sound/core/timer.c (c0c8e4b0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - sound/core/timer.c:snd_timer_user_read
```
```
In sound/core/pcm_native.c (c0c929f4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_drain
```
```
In sound/core/pcm_lib.c (c0c9a35c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
```
```
In net/socket.c (c0cc347c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (c0cca0e4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (c0cd8ee0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c0cd9604)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (c0cf8d54)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (c0d5f5d8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (c0d635ac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (c0d7ca54)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c0d7fca8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (c0daa374)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (c0db7e74)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (c0dfa2cc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/powerpc/kernel/ptrace.c (c0000000000195c8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
  - arch/powerpc/kernel/ptrace.c:ppc_set_hwdebug
  - arch/powerpc/kernel/ptrace.c:ptrace_set_debugreg
  - arch/powerpc/kernel/ptrace.c:task_user_regset_view
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_enter
  - arch/powerpc/kernel/ptrace.c:trace_event_raw_event_sys_enter
```
```
In arch/powerpc/mm/fault.c (c00000000008612c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
```
```
In arch/powerpc/mm/mmap.c (c0000000000888b0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/powerpc/mm/mmap.c:arch_pick_mmap_layout
  - arch/powerpc/mm/mmap.c:arch_pick_mmap_layout
  - arch/powerpc/mm/mmap.c:arch_pick_mmap_layout
  - arch/powerpc/mm/mmap.c:arch_pick_mmap_layout
  - arch/powerpc/mm/mmap.c:radix__arch_get_unmapped_area_topdown
  - arch/powerpc/mm/mmap.c:radix__arch_get_unmapped_area
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008dc70)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache
```
```
In arch/powerpc/mm/book3s64/radix_hugetlbpage.c (c00000000009ee20)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__hugetlb_get_unmapped_area
```
```
In arch/powerpc/mm/slice.c (c0000000000a4ad0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
```
```
In arch/powerpc/perf/callchain.c (c00000000012590c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/powerpc/perf/callchain.c:perf_callchain_user
  - arch/powerpc/perf/callchain.c:read_user_stack_32
  - arch/powerpc/perf/callchain.c:read_user_stack_64
```
```
In arch/powerpc/perf/perf_regs.c (c0000000001260a0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/powerpc/perf/perf_regs.c:perf_get_regs_user
```
```
In kernel/fork.c (c00000000013933c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (c000000000143150)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (c00000000014e0b0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (c000000000155914)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sys.c (c00000000015f2c4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
```
```
In kernel/kthread.c (c000000000171990)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (c000000000ee27e8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (c00000000018eea8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (c000000000196344)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (c0000000001a0cd0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (c0000000001a59d0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (c0000000001ad190)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (c000000000ee3d50)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (c0000000001ad918)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (c000000000ee4144)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (c000000000ee56d0)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/locking/semaphore.c (c000000000ee7264)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (c0000000001c1854)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex.c (c000000000ee7fd8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (c0000000001e2f3c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (c0000000001eaa60)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (c0000000001f31c0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (c0000000001f7e5c)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/time/timer.c (c0000000001ffee0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (c000000000ee8e1c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (c00000000020d534)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (c0000000002125e8)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/futex.c (c00000000021e9b0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (c000000000230e20)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/auditsc.c (c000000000267800)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (c000000000286638)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In kernel/trace/ring_buffer.c (c00000000029b7d4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/trace_syscalls.c (c0000000002cd220)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/bpf/verifier.c (c00000000031a6d4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/core.c (c000000000350930)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (c00000000035b118)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In kernel/rseq.c (c000000000360818)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/filemap.c (c000000000363788)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page-writeback.c (c000000000373f38)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (c000000000384df8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (c000000000395c40)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
```
```
In mm/compaction.c (c0000000003b12ec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (c0000000003b8c54)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (c0000000003bf288)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (c0000000003ca830)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mlock.c:__se_sys_mlockall
```
```
In mm/mmap.c (c0000000003d12dc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:get_unmapped_area
```
```
In mm/mmu_gather.c (c0000000003d1bd4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mremap.c (c0000000003d4ad4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
```
In mm/page_alloc.c (c0000000003eda5c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (c0000000003f3b70)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c0000000003fcc70)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (c00000000040f3ac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (c000000000416c48)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/ksm.c (c00000000041aa2c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (c000000000430898)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (c000000000452910)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (c00000000046bca0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (c000000000475f3c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (c000000000486eac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
```
```
In fs/pipe.c (c000000000487ca0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (c0000000004985ac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (c00000000049a250)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (c00000000049cba8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/namespace.c (c0000000004b69a8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/splice.c (c0000000004cffe0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (c0000000004e20a8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f4560)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f661c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (c0000000004f83c0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (c0000000004fbc54)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (c0000000004fe800)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (c000000000500d3c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (c000000000505988)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/aio.c:__se_compat_sys_io_pgetevents_time64
  - fs/aio.c:__se_compat_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_getevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_getevents
```
```
In fs/io_uring.c (c00000000050ea48)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
```
In fs/dax.c (c000000000512d54)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (c00000000051ecc8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/binfmt_elf.c (c00000000052df5c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (c000000000531bc8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (c0000000005375bc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (c00000000053c6d0)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/ext4/dir.c (c00000000057f618)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (c000000000592068)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (c0000000005bced4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (c0000000005c8310)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (c00000000061f4c8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (c000000000627e18)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (c000000000637554)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (c000000000669efc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (c00000000066ec14)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (c000000000675bc8)
Location: include/linux/sched.h:1737
Inline: True
```
```
In security/selinux/hooks.c (c0000000006a424c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (c00000000073c698)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (c00000000074ec40)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (c0000000007850b0)
Location: include/linux/sched.h:1737
Inline: True
```
```
In block/blk-cgroup.c (c0000000007abf4c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (c0000000007b73cc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In lib/syscall.c (c000000000812140)
Location: include/linux/sched.h:1737
Inline: True
```
```
In drivers/pci/vpd.c (c00000000086e674)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000881ffc)
Location: include/linux/sched.h:1737
Inline: True
```
```
In drivers/tty/tty_io.c (c0000000008f0e58)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (c0000000008f42b4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (c0000000008f99b8)
Location: include/linux/sched.h:1737
Inline: True
```
```
In drivers/tty/tty_port.c (c0000000008fe2c8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (c0000000009085f0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (c000000000929d84)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (c000000000942448)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (c0000000009485a0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (c000000000950f98)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (c0000000009a3ce0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1f0c8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (c000000000a81338)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (c000000000aa3d94)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa72fc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio.c (c000000000ab1670)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/devio.c (c000000000aeeb84)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (c000000000b8d0b4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (c000000000bdee84)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (c000000000bebba4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (c000000000c75528)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (c000000000c81df8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (c000000000c95e20)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c000000000c96738)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (c000000000cbea24)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (c000000000d4dca0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (c000000000d53364)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (c000000000d745bc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c000000000d77cf8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (c000000000dab3e0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (c000000000dbfbec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (c000000000e187dc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b64ba)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_exit
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_enter
```
```
In arch/riscv/mm/fault.c (ffffffe0000b9c54)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In kernel/fork.c (ffffffe0000bfd46)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffe0000c55ea)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffe0000ccc38)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffe0000d1f00)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigsuspend
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffe0000df736)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffe0008c4fa2)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffe0000f1af8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffe0000f6d7e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fa0f0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffe0000fedc8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffe0008c5c92)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffe0000ff422)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffe0008c5f80)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffe0008c6cfe)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffe0008c7a9e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffe00010add4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffe0008c81f6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffe00011e0a6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffe000123d28)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/freezer.c (ffffffe000128db2)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/time/timer.c (ffffffe00012db2e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffe0008c8a24)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffe000135470)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000137d06)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In kernel/futex.c (ffffffe00013d1b6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/seccomp.c (ffffffe00016b610)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffe00017a4fc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffe0001abb0e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/filemap.c (ffffffe0001d4f0c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page-writeback.c (ffffffe0001de91c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffe0001e8196)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffe0001f16ba)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffe000201ba0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffe000204c0e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffe000210ca6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffe00021fecc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffe000220bf4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffe0002267f4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffe000231ab4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/ksm.c (ffffffe0002338e8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memcontrol.c (ffffffe0002442e4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffe00025062e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffe000255832)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffe00025dc4e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
```
```
In fs/pipe.c (ffffffe00025fc06)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffe0002696d8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffe00026a338)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffe00026b282)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffe00028b84c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffe000294da0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0336)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a2338)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffe0002a33b6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/signalfd.c (ffffffe0002a5284)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffe0002a6c90)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffe0002a7dc8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffe0002ac54e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_getevents
```
```
In fs/io_uring.c (ffffffe0002b0fbe)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
```
In fs/dax.c (ffffffe0002b22c2)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffe0002b959a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/coredump.c (ffffffe0002c5d84)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8ef2)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/ext4/dir.c (ffffffe0002f1622)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffe0002fd936)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffe000318a4c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffe00031fec6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffe000355f72)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffe00035aeec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffe0003652dc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffe0003862d4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffe0003893a2)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffe00038cd3e)
Location: include/linux/sched.h:1737
Inline: True
```
```
In security/selinux/hooks.c (ffffffe0003a9762)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffe0003fe09e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffe000409adc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffe00042e16c)
Location: include/linux/sched.h:1737
Inline: True
```
```
In block/blk-cgroup.c (ffffffe000446df0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffe00044e248)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffe0004c48e4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d69be)
Location: include/linux/sched.h:1737
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffe00052f53e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffe00053183e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffe0005345da)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffe000537144)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffe00053d988)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054de66)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffe00055fc52)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffe0005622fe)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffe000567be4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d3c04)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffffffe000612ff2)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffe00062880e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062c480)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffe00064ff64)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/rtc/dev.c (ffffffe0006b5e8e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffe0006e0ff6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffe0006edc3c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffe0007391a0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffe00073ee06)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffe00074b504)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffe00074ba20)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffe000765360)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffe0007bb08a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffe0007be2ca)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d3524)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffe0007d6450)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffe0007f8f40)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffe000804d8e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffe00083f4a4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff810042c1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/kernel/process_64.c (ffffffff81030707)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff8103d8da)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041b37)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81043b65)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff81079110)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810795b5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff8107fc31)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810981e0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff8109f3d7)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810a7c4c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810aca0d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__x64_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810c24e2)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81a6e70b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810da239)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810df34c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810e794c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e9c64)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810eec87)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a6f6a9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ef128)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81a6fc52)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81a70548)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81a7146d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff810fd58f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff81a71fc5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff8111c006)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8112126e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (ffffffff8112669f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff811295a9)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112f3e8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81a728bc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811383e6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c4dd)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/futex.c (ffffffff8114379e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff8115176f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8118a185)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81198670)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff811e7b47)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff81214785)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81219efd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page-writeback.c (ffffffff8122511a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8123050b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff8123c06c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff8124e625)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81253519)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff812659fa)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff8127a63e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff8127d425)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812837ce)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128fb95)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff812978ef)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81a687db)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff812bb788)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812cb7ec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812d2ec5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812dd2f5)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/pipe.c (ffffffff812dfad1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff812eb6be)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812ec3c3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff812ee340)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff8130f853)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff8131bd8b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327e14)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8132a5fd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8132c626)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff8132e802)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffff8133051c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813317c0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81335a06)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff81338afc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
```
```
In fs/dax.c (ffffffff8133f751)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff81347d4b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/coredump.c (ffffffff81359882)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8135c8de)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81388944)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8139677a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813b57e5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813bdb1d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc29b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff814020a3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d59e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff81431d6e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81434e25)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8143a1ed)
Location: include/linux/sched.h:1737
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81457115)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814b704f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff814c2306)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff814e8185)
Location: include/linux/sched.h:1737
Inline: True
```
```
In block/blk-cgroup.c (ffffffff815035de)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff8150bd69)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8157fd6b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81593ebc)
Location: include/linux/sched.h:1737
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8164a765)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff8164cdd6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81650a65)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff816537ab)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff8165a2a8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166d7fd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff81680411)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff816852fa)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff81689584)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff8168a79e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff816d9eec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171b3b0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/nvme/host/core.c (ffffffff81742f81)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_shutdown_ctrl
  - drivers/nvme/host/core.c:nvme_wait_ready
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81772dd3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff817875a0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178c4a0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/usb/core/devio.c (ffffffff817b633f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff8181b985)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff818439c1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff8184d8cc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff818ac059)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff818b3aa0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff818c226c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff818c2871)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff818df12e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff81940bf9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81944580)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195c2ef)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819605e0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819867a6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81993c80)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff819d2281)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff81002791)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/kernel/process_64.c (ffffffff81020197)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff8102cfc8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff810311f7)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81033195)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff810688c0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81068d35)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff8106ec94)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81086c3a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff8108de07)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff81096626)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8109b38d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__x64_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810b0d32)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81a2ab06)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c922b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810ce35c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810d6788)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d9c24)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810ded17)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a2bad9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810df1a8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81a2c06c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81a2c938)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81a2da17)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff810ed78f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff81a2e38f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff8110d076)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81112213)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (ffffffff811190fb)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff8111be39)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/time/timer.c (ffffffff81121e68)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81a2ec8c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8112ae36)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112ef9d)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/futex.c (ffffffff8113765e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff81144a4f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff8117d2b5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8118bb80)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff811da907)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff812074f5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8120d10d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page-writeback.c (ffffffff812182ba)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff812235cb)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff8122f06c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff812415c5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81246232)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff81257e1a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff8126c52e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff8126f290)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8127567f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81281855)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff812894df)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81a2529b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff812ac8f8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812bc660)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812c3b45)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812cdf75)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/pipe.c (ffffffff812d0711)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff812dc2ee)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812dcff3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff812def70)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff81300463)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff8130c92b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813189b4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131b19d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8131bf11)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff8131f456)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffff81321120)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff8132239a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81326246)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff8132982c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
```
```
In fs/dax.c (ffffffff81330411)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff81338a2b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/coredump.c (ffffffff8134a532)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8134d57e)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813793d4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8138720a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813a6275)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813ae5ad)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecd1b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff813f2b23)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff813fe01e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff814227ee)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814258a5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8142ac5d)
Location: include/linux/sched.h:1737
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81447b55)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814a7a6f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff814b2d26)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff814d86f5)
Location: include/linux/sched.h:1737
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f3a9e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff814fc1b3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8156eb4b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8158304c)
Location: include/linux/sched.h:1737
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162abb5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff8162d226)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81630eb5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff81633b9b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff8163a628)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164c9cd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff8165e0e1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81662f9a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff8166700e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff8166819e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff816b456c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f4810)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/nvme/host/core.c (ffffffff81724c11)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_shutdown_ctrl
  - drivers/nvme/host/core.c:nvme_wait_ready
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81752b83)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff81766ef0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81775270)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio.c (ffffffff8177bd46)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/devio.c (ffffffff817a7d5f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff817e306f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff8180b021)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff81814eec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff81865fa9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff8186d9f0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8187c1ac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff8187c7b1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff81898f6e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff818fa6e9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff818fe070)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915ddf)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff8191a0d0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff81940266)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff8194d740)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff8198f041)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff81004281)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/kernel/process_64.c (ffffffff81030567)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff8103d71a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041977)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810439a5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff810790c0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81079565)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff8107fbe1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81098190)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff8109f387)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810a71ac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810abf6d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__x64_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810c1a32)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81adab1b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d6586)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810db6cc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810e39b8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e6d94)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810ebdb7)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81adbab9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ec258)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81adc062)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81adc958)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81add87d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff810fa74f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff81ade3d5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff81119ef6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8111f15e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (ffffffff8112458f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff811272c9)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112d108)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81adeccc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81136106)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a1fd)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/futex.c (ffffffff8114164e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff8114f61f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff81187f55)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81196440)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff811e5917)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff81212525)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81217c9d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page-writeback.c (ffffffff81222eba)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8122e2ab)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff81239e0c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff8124c3c5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812512b9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff8126379a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff812783de)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff8127b1c5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812815de)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d9a5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff812956ff)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81ad4beb)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff812b9598)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812c95fc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812d0cd5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812db105)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/pipe.c (ffffffff812dd8e1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff812e94ce)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812ea1d3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff812ec150)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff8130d643)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff8131985b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813258e4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813280cd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8132a0f6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff8132c2d2)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffff8132dfec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff8132f290)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813334d6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff813365cc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
```
```
In fs/dax.c (ffffffff8133d221)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff8134581b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/coredump.c (ffffffff81357352)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8135a3ae)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813862a4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813940da)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813b3045)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813bb4fd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff813f961b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff813ff423)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8140a91e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff8142df0e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81430fc5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8143638d)
Location: include/linux/sched.h:1737
Inline: True
```
```
In security/selinux/hooks.c (ffffffff814531b5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814b30df)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff814be396)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff814e4215)
Location: include/linux/sched.h:1737
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814ff66e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff81507df9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8157fc3b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815943fc)
Location: include/linux/sched.h:1737
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81678b25)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff8167b196)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff8167ee25)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff81681b6b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff81688668)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169bbdd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff816ae7f1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff816b36ea)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff816b77f4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff816b8a0e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff8170787c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8175a180)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817a3133)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff817b7950)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bc840)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio.c (ffffffff817c6b16)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/devio.c (ffffffff817f2ddf)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff8185ce65)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff81892ff1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff8189cefc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff818fd059)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81904aa0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff8191326c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff81913871)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff8193015e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff81991d89)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff81995710)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nfnetlink.c (ffffffff819989c3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6abf)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819cadb0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819f0f76)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff819fe520)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81a3cd01)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
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
In arch/x86/entry/common.c (ffffffff810043be)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/kernel/process_64.c (ffffffff810313f7)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/process.c (ffffffff8103e836)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042d57)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81044da5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/uprobes.c (ffffffff8107b1c0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_pre_xol
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8107b665)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_reg_abi
```
```
In arch/x86/mm/fault.c (ffffffff81081cde)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff8109fd87)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a72d6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/ptrace.c (ffffffff810af517)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b40dd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__x64_sys_pause
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/kthread.c (ffffffff810c9e60)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/sched/core.c (ffffffff81ae6fcd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e1e86)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
```
In kernel/sched/fair.c (ffffffff810e73bc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
```
In kernel/sched/rt.c (ffffffff810f015c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/rt.c:check_preempt_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f1cf4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/deadline.c:check_preempt_curr_dl
```
```
In kernel/sched/wait.c (ffffffff810f6e17)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81ae8059)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810f7388)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81ae8266)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
```
```
In kernel/locking/mutex.c (ffffffff81ae8d8e)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81ae9f14)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff81105914)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff81aea87d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
```
In kernel/rcu/update.c (ffffffff8112564d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8112a2e2)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/livepatch/transition.c (ffffffff81130bea)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/freezer.c (ffffffff81133929)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/time/timer.c (ffffffff81138e98)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
```
```
In kernel/time/hrtimer.c (ffffffff81aeb15c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81142b86)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146c16)
Location: include/linux/sched.h:1737
Inline: True
```
```
In kernel/futex.c (ffffffff8114e9bc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/kexec_core.c (ffffffff8115c43f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/seccomp.c (ffffffff811958a9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811a4050)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/bpf/verifier.c (ffffffff811f3ce7)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/events/uprobes.c (ffffffff812214a5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81226d59)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page-writeback.c (ffffffff8123209d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8123d6ab)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/shmem.c (ffffffff812494f0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
```
```
In mm/compaction.c (ffffffff8125bd25)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81260c3c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/mmap.c (ffffffff8127315a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/page_alloc.c (ffffffff81287fce)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff8128ad95)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8129131b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129d75e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/ksm.c (ffffffff812a551f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/memory_hotplug.c (ffffffff81ae10cb)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff812c9c18)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff812da24d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812e1b05)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff812ec0ad)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/pipe.c (ffffffff812ee861)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/ioctl.c (ffffffff812fa4bd)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812fb1c3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffff812fd14b)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:do_sys_poll
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
```
```
In fs/splice.c (ffffffff8131ee43)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff8132b4ed)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81337392)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8133950c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8133abce)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
```
In fs/signalfd.c (ffffffff8133e8d1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
```
In fs/eventfd.c (ffffffff813408a7)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813413b0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81346526)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
```
In fs/io_uring.c (ffffffff8134969c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
```
```
In fs/dax.c (ffffffff81350931)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff81358afb)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/coredump.c (ffffffff8136aa32)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8136dafe)
Location: include/linux/sched.h:1737
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81399f94)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813a816a)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff813c7b95)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff813d00b1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f276)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fat/fatent.c (ffffffff81415053)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff814205de)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In ipc/msg.c (ffffffff81444951)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81447683)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8144d1bc)
Location: include/linux/sched.h:1737
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8146acb4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff814cbb5f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algboss.c (ffffffff814d6e66)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/blk-mq.c (ffffffff814fd795)
Location: include/linux/sched.h:1737
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81518819)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff8151f0d5)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8159a0eb)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815ae87c)
Location: include/linux/sched.h:1737
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81692760)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffffffff816957f6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffff81699475)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termiox
```
```
In drivers/tty/tty_port.c (ffffffff8169c1bb)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/vt/selection.c (ffffffff816a2c58)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b671d)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
```
```
In drivers/char/mem.c (ffffffff816c8c3f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff816cdc86)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hpet.c (ffffffff816d1da8)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_read
```
```
In drivers/char/hw_random/core.c (ffffffff816d2fde)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/base/power/wakeup.c (ffffffff817222ac)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81775740)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817bcfb3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/net/tun.c (ffffffff817d20fc)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d6ea0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/vfio/vfio.c (ffffffff817e0db6)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/devio.c (ffffffff8180d05f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
```
```
In drivers/rtc/dev.c (ffffffff818780e0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/md/md.c (ffffffff818aebf1)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
```
In drivers/md/dm.c (ffffffff818b925c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/socket.c (ffffffff8191e0c9)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81925b40)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
```
```
In net/core/datagram.c (ffffffff819343ec)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffffffff819349f4)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/ethtool.c (ffffffff8195182e)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffff819b4879)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/bpf/test_run.c (ffffffff819b829c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819d060f)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff819d4940)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/udp.c (ffffffff819f936c)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffffffff81a088b0)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/unix/af_unix.c (ffffffff81a482c3)
Location: include/linux/sched.h:1737
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
```
</details>
</li>
</ul>

## Differences
