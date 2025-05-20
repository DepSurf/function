# Function: <code>rep_nop</code>

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
In arch/x86/events/intel/rapl.c (ffffffff8101496d)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_event_update
```
```
In arch/x86/kernel/tsc.c (ffffffff81037b20)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/rtc.c (ffffffff81038ada)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810410a3)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104400d)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
```
```
In arch/x86/kernel/reboot.c (ffffffff81050203)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051e44)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052971)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810537bb)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81054bc3)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055a08)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810593d6)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a5a0)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In arch/x86/kernel/apic/probe_64.c (ffffffff8105a8e5)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
```
In arch/x86/kernel/early_printk.c (ffffffff81061d16)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff81f740f3)
Location: arch/x86/include/asm/processor.h:561
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106312f)
Location: arch/x86/include/asm/processor.h:561
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063e46)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff81080d39)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/cpu.c (ffffffff81081696)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
```
```
In kernel/exit.c (ffffffff8108398e)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810982ca)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/task_work.c (ffffffff8109e92a)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/sched/core.c (ffffffff810a9b82)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_move_task
```
```
In kernel/sched/cputime.c (ffffffff810b19c5)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/deadline.c (ffffffff810c290b)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/completion.c (ffffffff810c3be8)
Location: arch/x86/include/asm/processor.h:561
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810c3e97)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/locking/mutex.c (ffffffff810c9aa9)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/osq_lock.c (ffffffff810ca35a)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_unlock
```
```
In kernel/locking/qspinlock.c (ffffffff810ca700)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff810cb02a)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810cbcde)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/locking/qrwlock.c (ffffffff810cbd6d)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff8118bcb1)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/power/hibernate.c:power_down
```
```
In kernel/printk/printk.c (ffffffff810d8533)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff810daaaa)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810dd470)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff810ec45c)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/time/hrtimer.c (ffffffff810eea47)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff810f42ee)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:timekeeping_get_tai_offset
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
```
```
In kernel/time/alarmtimer.c (ffffffff810fb25f)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/tick-common.c (ffffffff810fc76e)
Location: arch/x86/include/asm/processor.h:561
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff810fe984)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/smp.c (ffffffff811039bb)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/acct.c (ffffffff8110c35f)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cpuset.c (ffffffff8111d9e2)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff8111ffca)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
```
```
In kernel/auditsc.c (ffffffff81128ce4)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff8118c30d)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8112fd88)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811345aa)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8113a3b4)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff81170cf6)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/filemap.c (ffffffff8118d619)
Location: arch/x86/include/asm/processor.h:561
Inline: True
```
```
In mm/page_alloc.c (ffffffff81192528)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/page-writeback.c (ffffffff8119a6c9)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8119d40c)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - mm/swap.c:__get_page_tail
```
```
In mm/hugetlb.c (ffffffff811dae42)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff811e0860)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/ksm.c (ffffffff811e4b8c)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff811e9d67)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:___slab_alloc
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
```
In mm/huge_memory.c (ffffffff811f74e5)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/namei.c (ffffffff81216316)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/namei.c:set_root_rcu
  - fs/namei.c:set_root_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:lookup_fast
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff8122281b)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/dcache.c:slow_dentry_cmp
  - fs/dcache.c:d_walk
  - fs/dcache.c:__d_drop
  - fs/dcache.c:dput
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_delete
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_path
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_lookup
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:is_subdir
```
```
In fs/namespace.c (ffffffff8122d5e0)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:lookup_mnt
```
```
In fs/fs-writeback.c (ffffffff81238205)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffffffff81242402)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
```
```
In fs/buffer.c (ffffffff81243faf)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/timerfd.c (ffffffff81258836)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff8125a85f)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff8126cccc)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/page-io.c (ffffffff8129f885)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff812e8174)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
```
```
In fs/jbd2/commit.c (ffffffff812ea34c)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff812f2dfb)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
```
In ipc/msg.c (ffffffff81326a13)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
```
```
In ipc/sem.c (ffffffff81326e14)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:exit_sem
```
```
In block/bio.c (ffffffff813b0fbf)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813bbc8c)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - block/blk-core.c:blk_poll
```
```
In block/blk-ioc.c (ffffffff813bedd4)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff813d8a8a)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-throttle.c (ffffffff813db96c)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In lib/dump_stack.c (ffffffff813e939f)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff813e99ab)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_single
  - lib/flex_proportions.c:fprop_fraction_percpu
```
```
In arch/x86/lib/delay.c (ffffffff813f65b7)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
```
```
In lib/lockref.c (ffffffff813f7b33)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/genalloc.c (ffffffff81406d5c)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:gen_pool_alloc
  - lib/genalloc.c:gen_pool_alloc
```
```
In drivers/pci/pcie/pme.c (ffffffff8144bc17)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff814bd3d0)
Location: arch/x86/include/asm/processor.h:561
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff814c5a16)
Location: arch/x86/include/asm/processor.h:561
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fa75aa)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:wait_for_xmitr
```
```
In drivers/char/virtio_console.c (ffffffff81516c6c)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_control_msg
```
```
In drivers/iommu/dmar.c (ffffffff815334fa)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81535d13)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153c94f)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff815567bb)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a365c)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815a50fb)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
```
In drivers/ata/libata-eh.c (ffffffff815d4bf0)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
```
In drivers/net/virtio_net.c (ffffffff815f1bc1)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_send_command
```
```
In drivers/usb/core/message.c (ffffffff8161209e)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff81673f4e)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff8168dc78)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/md/md.c:md_is_badblock
  - drivers/md/md.c:badblocks_show
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/driver.c (ffffffff816bc097)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/socket.c (ffffffff816fe01e)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8170ccf0)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/core/neighbour.c (ffffffff81725971)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/ipv4/inetpeer.c (ffffffff8175860f)
Location: arch/x86/include/asm/processor.h:561
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175d1fa)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763a2d)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81767696)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781500)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8178c5dd)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff817a18e0)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff817a2914)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a5c15)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b48b1)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff817c539c)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/packet/af_packet.c (ffffffff81802fb1)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In arch/x86/kernel/nmi.c (ffffffff81031a8a)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/tsc.c (ffffffff81036d35)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/rtc.c (ffffffff81037b4a)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040fcc)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044146)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
```
```
In arch/x86/kernel/reboot.c (ffffffff810509af)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051f6f)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052cc9)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f99c42)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81054d24)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055c93)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/early_printk.c (ffffffff81061b46)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff81f9c948)
Location: arch/x86/include/asm/processor.h:572
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81062daf)
Location: arch/x86/include/asm/processor.h:572
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063a6a)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff81082b69)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff8109b882)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810ae69c)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810b4475)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff810c7b8c)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/locking/mutex.c (ffffffff810ce4dc)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/osq_lock.c (ffffffff810cede5)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810cf3fd)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:queued_spin_unlock_wait
  - kernel/locking/qspinlock.c:queued_spin_unlock_wait
```
```
In kernel/locking/rtmutex.c (ffffffff810cfb1e)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8189d9da)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/locking/qrwlock.c (ffffffff810d087d)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff8119e9fe)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/power/hibernate.c:power_down
```
```
In kernel/printk/printk.c (ffffffff810dcff3)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff810e00ba)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810e2c30)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff810f3cce)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
```
```
In kernel/time/hrtimer.c (ffffffff8189e32c)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff810fdc95)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:timekeeping_get_tai_offset
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
```
```
In kernel/time/alarmtimer.c (ffffffff81102721)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/tick-common.c (ffffffff81103ac0)
Location: arch/x86/include/asm/processor.h:572
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81105d34)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/smp.c (ffffffff8110b12b)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff81113bbf)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup.c (ffffffff811217e7)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cpuset.c (ffffffff81125900)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff81128862)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/auditsc.c (ffffffff81130e7b)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff8119f085)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8113808e)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113ca1a)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811428c4)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff8117e3f6)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/filemap.c (ffffffff811a0209)
Location: arch/x86/include/asm/processor.h:572
Inline: True
```
```
In mm/page_alloc.c (ffffffff811ab0d6)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/page-writeback.c (ffffffff811aeff9)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/hugetlb.c (ffffffff811faea9)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff811feb29)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/ksm.c (ffffffff812036be)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8120c709)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff8122bcac)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff8123e11c)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff8124ec44)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_delete
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_walk
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__d_drop
```
```
In fs/namespace.c (ffffffff812561fa)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/libfs.c (ffffffff8125bd42)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/libfs.c:move_cursor
```
```
In fs/fs-writeback.c (ffffffff8126224f)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffffffff8126a762)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
```
```
In fs/buffer.c (ffffffff8126bee9)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff8128115b)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff81283108)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff81298b06)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81299586)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff812ce136)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff81317274)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8131837d)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff81320b4d)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/msg.c (ffffffff8135b665)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
```
```
In ipc/sem.c (ffffffff8135d84c)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
```
```
In block/bio.c (ffffffff813f49af)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813ffaa0)
Location: arch/x86/include/asm/processor.h:572
Inline: True
```
```
In block/blk-ioc.c (ffffffff81402da9)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/badblocks.c (ffffffff81413076)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff8141e7e1)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-throttle.c (ffffffff81421458)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In lib/dump_stack.c (ffffffff8142f5ae)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff8142fe9b)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff8143d187)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
```
```
In lib/lockref.c (ffffffff8143e9c3)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/genalloc.c (ffffffff8144ee26)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff81497eb7)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff8150d2f5)
Location: arch/x86/include/asm/processor.h:572
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81515f76)
Location: arch/x86/include/asm/processor.h:572
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fd3a8f)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff8156990c)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff81587aac)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158a4b3)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815915f6)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff815a87f8)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815fa741)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815fc1ae)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8164c56f)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/net/virtio_net.c (ffffffff816514d1)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_send_command
```
```
In drivers/usb/core/message.c (ffffffff81671fdc)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff816d472e)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff816f2ac5)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/driver.c (ffffffff8171d9a7)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff8177675a)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/dev.c (ffffffff8178343a)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
```
```
In net/core/neighbour.c (ffffffff81790891)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff817c48ef)
Location: arch/x86/include/asm/processor.h:572
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817c9fc7)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0553)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee9cb)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff817f9be1)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f5ab)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff81810192)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818138b4)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8182058f)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81831f91)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/packet/af_packet.c (ffffffff81874341)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In arch/x86/kernel/nmi.c (ffffffff810316da)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/tsc.c (ffffffff81036a65)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/rtc.c (ffffffff81037923)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040a0f)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045bd9)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
```
```
In arch/x86/kernel/reboot.c (ffffffff8105321f)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff810548be)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105592e)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81fd511e)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057ae4)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058a2e)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/early_printk.c (ffffffff81064bf6)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff81065863)
Location: arch/x86/include/asm/processor.h:614
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81066245)
Location: arch/x86/include/asm/processor.h:614
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81066f1a)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff810875c9)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810a07b2)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810b47d9)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810baaa5)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff818d3db9)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/mutex.c (ffffffff810d517b)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810d5a25)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810d5ded)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:queued_spin_unlock_wait
  - kernel/locking/qspinlock.c:queued_spin_unlock_wait
```
```
In kernel/locking/rtmutex.c (ffffffff810d6500)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/rwsem-xadd.c (ffffffff818d287f)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/locking/qrwlock.c (ffffffff810d72ed)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff811ae449)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/power/hibernate.c:power_down
```
```
In kernel/printk/printk.c (ffffffff810e3693)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff810e6a0a)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810e9530)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff810fad2e)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff818d31cd)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81100a85)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:timekeeping_get_tai_offset
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
```
```
In kernel/time/alarmtimer.c (ffffffff81105042)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/tick-common.c (ffffffff8110b1ad)
Location: arch/x86/include/asm/processor.h:614
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110d480)
Location: arch/x86/include/asm/processor.h:614
Inline: True
```
```
In kernel/smp.c (ffffffff81112b04)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff8111b2cf)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup.c (ffffffff81129d75)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cpuset.c (ffffffff8112f2fa)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff81132513)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/auditsc.c (ffffffff8113abeb)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff811aeb2b)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff81141e22)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8114401d)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811467ca)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8114c6a4)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff8118a006)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/filemap.c (ffffffff811af649)
Location: arch/x86/include/asm/processor.h:614
Inline: True
```
```
In mm/page_alloc.c (ffffffff811bade7)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff811bf66b)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/hugetlb.c (ffffffff8120b9a9)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff81210369)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/ksm.c (ffffffff812156db)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8121e769)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff8123e208)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff81250efc)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81261c54)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_delete
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_walk
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__d_drop
```
```
In fs/namespace.c (ffffffff812695ea)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/libfs.c (ffffffff8126f2f2)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/libfs.c:move_cursor
```
```
In fs/fs-writeback.c (ffffffff8127574f)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffffffff8127d665)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/buffer.c (ffffffff8127f259)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff81294c8b)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff81296c28)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff812ad584)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff812ae0a6)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff812e3f26)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff8132d264)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132e36e)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813369fd)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In block/bio.c (ffffffff8140e39f)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-ioc.c (ffffffff8141cad9)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff814220e3)
Location: arch/x86/include/asm/processor.h:614
Inline: True
```
```
In block/badblocks.c (ffffffff8142e5a6)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff81439da1)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-throttle.c (ffffffff8143c836)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In lib/dump_stack.c (ffffffff8144b7de)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff8144c0cb)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff8145a107)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
```
```
In lib/lockref.c (ffffffff8145ba13)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/genalloc.c (ffffffff8146d7e6)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff814b9767)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff81539425)
Location: arch/x86/include/asm/processor.h:614
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815423f6)
Location: arch/x86/include/asm/processor.h:614
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8201144f)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff8159604c)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff815b516c)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b7b23)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815beeb6)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff815d72e6)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81628a11)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ae72)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8167e27f)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff8169fc8c)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff8170440e)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff817241e6)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/driver.c (ffffffff818d405c)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff817a39dc)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff817a404c)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff817b0d67)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
```
```
In net/core/neighbour.c (ffffffff817be141)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff817f440f)
Location: arch/x86/include/asm/processor.h:614
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817f9280)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818003a5)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f3db)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8182aab1)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81840afb)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff81841690)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81844db5)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81851dcf)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff818596f7)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81863f35)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/packet/af_packet.c (ffffffff818a8931)
Location: arch/x86/include/asm/processor.h:614
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In arch/x86/kernel/nmi.c (ffffffff8102f8e8)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/rtc.c (ffffffff810359d3)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e992)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104c2f6)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_read
```
```
In arch/x86/kernel/reboot.c (ffffffff81052d0f)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff810541fb)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105523d)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff820b5e27)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057264)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8190ebfd)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/early_printk.c (ffffffff81063b76)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff81064c53)
Location: arch/x86/include/asm/processor.h:625
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106557f)
Location: arch/x86/include/asm/processor.h:625
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810661ea)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff81084459)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff8109d994)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810b082c)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810b538b)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff8190af19)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/mutex.c (ffffffff810d41cd)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810d49a5)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810d4d6f)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:queued_spin_unlock_wait
  - kernel/locking/qspinlock.c:queued_spin_unlock_wait
```
```
In kernel/locking/rtmutex.c (ffffffff810d5487)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8190974d)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/locking/qrwlock.c (ffffffff810d632d)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810da8c7)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff810e374d)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff810e605a)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810e89fc)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff810fd05f)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff8190a350)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81102bc4)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
```
```
In kernel/time/alarmtimer.c (ffffffff81106f52)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/tick-common.c (ffffffff8110d09d)
Location: arch/x86/include/asm/processor.h:625
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110f39c)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/smp.c (ffffffff81114000)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff8111ceff)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81128b1c)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rdma.c (ffffffff8112bf67)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81130954)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff81133af3)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/auditsc.c (ffffffff8113c1dc)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff81142035)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8114365e)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81145d3d)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8114852a)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8114e614)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff8118cb92)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/filemap.c (ffffffff811b654c)
Location: arch/x86/include/asm/processor.h:625
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c304b)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff811c7494)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/hugetlb.c (ffffffff81214607)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff81220ce8)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8122a3af)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff81249ba9)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff8125c5e4)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff8126f51b)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_delete
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__d_drop
```
```
In fs/namespace.c (ffffffff81276d8d)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/libfs.c (ffffffff8127cadf)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/libfs.c:move_cursor
```
```
In fs/fs-writeback.c (ffffffff81282af6)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffffffff8128b227)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/buffer.c (ffffffff8128cbf3)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff812a1f14)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff812a44bc)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff812baa1f)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff812bb5e9)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff8131db77)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff81342434)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81343a49)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8134b6a9)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In block/bio.c (ffffffff8141bfa7)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-ioc.c (ffffffff8142aa49)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff814308b7)
Location: arch/x86/include/asm/processor.h:625
Inline: True
```
```
In block/badblocks.c (ffffffff8143b8af)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff81447622)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-throttle.c (ffffffff8144b783)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In lib/lockref.c (ffffffff81460f03)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/genalloc.c (ffffffff81472ead)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff814c3f3a)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff8154cc95)
Location: arch/x86/include/asm/processor.h:625
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81555fc6)
Location: arch/x86/include/asm/processor.h:625
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff820f2fae)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff815a9dfa)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff815cb004)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff815cdbe3)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d4a80)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff815eba1f)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163e64b)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816404c3)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff816412e9)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816933c1)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff816b4e5c)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff81719fe9)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff8173c5f9)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/driver.c (ffffffff8190b1e7)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff817c1b3b)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff817c219e)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff817d10e1)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff817dcbae)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff8181482c)
Location: arch/x86/include/asm/processor.h:625
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff818197ce)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81821455)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183ff90)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8184bce1)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff818623ef)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff81862ebc)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81866915)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81874f35)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff8187d62a)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81889725)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/packet/af_packet.c (ffffffff818cf176)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In lib/dump_stack.c (ffffffff818ebf84)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff818ec873)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff818fbe46)
Location: arch/x86/include/asm/processor.h:625
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff810318e8)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/rtc.c (ffffffff81037cf3)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104165f)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff81056a0f)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057fdf)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105900d)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826bc62d)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8105aef4)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826bdc12)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff81067ce6)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff81068de3)
Location: arch/x86/include/asm/processor.h:647
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106974f)
Location: arch/x86/include/asm/processor.h:647
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a03a)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff8108ae39)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810a40c7)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810b7c6c)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810bc53b)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81995289)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/mutex.c (ffffffff810dc11d)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810dc925)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810dcac5)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff810dd367)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819938e7)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/locking/qrwlock.c (ffffffff810de2f0)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810e2a45)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff810eb40d)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff810ee2da)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810f0dd0)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff8110783f)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff8199469c)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8110db67)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
```
```
In kernel/time/alarmtimer.c (ffffffff81112065)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/tick-common.c (ffffffff8111831d)
Location: arch/x86/include/asm/processor.h:647
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8111a3d3)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/futex.c (ffffffff8111e055)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/smp.c (ffffffff8111f57e)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff81128606)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81135186)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rdma.c (ffffffff81138d77)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d894)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff811408a3)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/auditsc.c (ffffffff81148f5c)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff8114edf5)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff81150314)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8115267d)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81154dda)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8115aea4)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff8119a649)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/filemap.c (ffffffff811ca579)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page_alloc.c (ffffffff811d868d)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff811dc2aa)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/hugetlb.c (ffffffff8122f1b9)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8123bf62)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8124555f)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff81269e09)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff81283ae6)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81291e3a)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_delete
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff812997cd)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/libfs.c (ffffffff8129f57f)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/libfs.c:move_cursor
```
```
In fs/fs-writeback.c (ffffffff812a5636)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffffffff812add73)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/buffer.c (ffffffff812af693)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff812c5234)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff812c7945)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff812de2ff)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff812deede)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff81342187)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff81366a64)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8136809c)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8136fcd9)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In block/blk-ioc.c (ffffffff81455c39)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff8145bda3)
Location: arch/x86/include/asm/processor.h:647
Inline: True
```
```
In block/badblocks.c (ffffffff814678bf)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff81474212)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-throttle.c (ffffffff81477cf7)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In lib/lockref.c (ffffffff8148cdc3)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/genalloc.c (ffffffff814a0230)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff81504183)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff815b020b)
Location: arch/x86/include/asm/processor.h:647
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815b9c26)
Location: arch/x86/include/asm/processor.h:647
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81604bc8)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff8161075a)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff81631dd4)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff81634a23)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b816)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff81652e07)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a7485)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816a9542)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff816aa100)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816fd2d4)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff817206ec)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff8178b259)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff817ae1be)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/poll_state.c (ffffffff81995578)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff8183b54f)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff8183bb8f)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff8184b1d1)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff8185777e)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81893892)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81897df9)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a021e)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf337)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff818cb981)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff818e24e5)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818e2fec)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e6ab5)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f58a1)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff818fe2cb)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81909b77)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/packet/af_packet.c (ffffffff81954110)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In lib/dump_stack.c (ffffffff81971f74)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff81972843)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff81982ca6)
Location: arch/x86/include/asm/processor.h:647
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff81032a5b)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/rtc.c (ffffffff81038df3)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042f2f)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff8105981f)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105aca4)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105be7e)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826e63db)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8105def4)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826e79c6)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff8106a926)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff826e92f6)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8106c354)
Location: arch/x86/include/asm/processor.h:663
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106ce4a)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff8108e619)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810ac083)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810bf7c9)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810c3c02)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff819f17e9)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/locking/mutex.c (ffffffff810e478e)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810e4f65)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810e529a)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff810e5a27)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819efea0)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/locking/qrwlock.c (ffffffff810e69d0)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810eb015)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff810f4798)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff810f66ca)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff810f9150)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff811132ef)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff819f0e9f)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8111954d)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff8111d8f4)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/tick-common.c (ffffffff81124e5b)
Location: arch/x86/include/asm/processor.h:663
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81126b3a)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff8112aa62)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/smp.c (ffffffff8112c8aa)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff811364f6)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811438ad)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff81143e39)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff811479c8)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c12c)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff8114f1e3)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/auditsc.c (ffffffff8115793c)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff8115d865)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8115eeb1)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81161277)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8116365a)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81169ae4)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811b0089)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/filemap.c (ffffffff811eb629)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page_alloc.c (ffffffff811f97d3)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff811fdb6b)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/hugetlb.c (ffffffff8125198e)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8125f4cd)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812695b5)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff8128e79a)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff812aacbe)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812b59f2)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff812bf671)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/libfs.c (ffffffff812c6f9f)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/libfs.c:move_cursor
```
```
In fs/fs-writeback.c (ffffffff812cbd1d)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff812d3d3e)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/nsfs.c (ffffffff812d5b7f)
Location: arch/x86/include/asm/processor.h:663
Inline: True
```
```
In fs/buffer.c (ffffffff812d6de5)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff812ee5a8)
Location: arch/x86/include/asm/processor.h:663
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812f0cac)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff8130a541)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff8130aebb)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff81370008)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff81395155)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81396425)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8139e1f0)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In block/blk-ioc.c (ffffffff81489179)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff8148f521)
Location: arch/x86/include/asm/processor.h:663
Inline: True
```
```
In block/badblocks.c (ffffffff8149b734)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff814a8a8e)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-throttle.c (ffffffff814ac368)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In lib/lockref.c (ffffffff814c1ab3)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/genalloc.c (ffffffff814d53ed)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff815350e3)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff815e85eb)
Location: arch/x86/include/asm/processor.h:663
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815f1ab6)
Location: arch/x86/include/asm/processor.h:663
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8163de58)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff8164a23c)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff8166d188)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff8166ffa7)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81676e22)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff8168ef33)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e3463)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816e5615)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff816e65fe)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8173b3c8)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff8175efac)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff817cca7d)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff817f4084)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/poll_state.c (ffffffff819f1af8)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff81885beb)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818862d7)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff818955c4)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff818a2906)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff818e7b84)
Location: arch/x86/include/asm/processor.h:663
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff818ebfd6)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f45d5)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914dce)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81921e1a)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819398e7)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d4ef)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194bbbd)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81954d94)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81960bea)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/packet/af_packet.c (ffffffff819aeb1a)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In lib/dump_stack.c (ffffffff819ce37c)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff819cec3e)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff819df0b6)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff81033e0b)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/rtc.c (ffffffff8103a003)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104450f)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f49f)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81060924)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061b5e)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289cf1e)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81063b84)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289e50f)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff810706b6)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff8289feb2)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810720e4)
Location: arch/x86/include/asm/processor.h:658
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107301a)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff810968a9)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810b4f63)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810c8ac9)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810ccec2)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81a2cc8b)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/psi.c (ffffffff810ef072)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_stats
```
```
In kernel/locking/mutex.c (ffffffff810efd7e)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810f0545)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810f0881)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff810f0faa)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b8d2)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/locking/qrwlock.c (ffffffff810f1fce)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810f6648)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff810fff28)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff81101e3a)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff811048f0)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff8111d60f)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81a2c21f)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81124a3d)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff811291f4)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/tick-common.c (ffffffff8113055b)
Location: arch/x86/include/asm/processor.h:658
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113221a)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff81136ba2)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/smp.c (ffffffff8113817a)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff81141c86)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f3c6)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff8114f949)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff81153281)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81158d72)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff8115bec3)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/auditsc.c (ffffffff8116493c)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff8116a485)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8116bbde)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8116e0a7)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811705ba)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81176924)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811be699)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In mm/filemap.c (ffffffff811fc169)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page_alloc.c (ffffffff8120bea1)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff8121068a)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/hugetlb.c (ffffffff81265d8e)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff81273c0d)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8127c68d)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff812a330a)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff812bc977)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812cad10)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff812d487f)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/libfs.c (ffffffff812dc27f)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/libfs.c:move_cursor
```
```
In fs/fs-writeback.c (ffffffff812e142f)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff812e8f8e)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/nsfs.c (ffffffff812eaf4f)
Location: arch/x86/include/asm/processor.h:658
Inline: True
```
```
In fs/buffer.c (ffffffff812ec566)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff81302f38)
Location: arch/x86/include/asm/processor.h:658
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81305bb3)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff8131fd21)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff813206fb)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff81388499)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813adec5)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813af17b)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813b6f60)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In block/blk-ioc.c (ffffffff814a2f38)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff814a8faf)
Location: arch/x86/include/asm/processor.h:658
Inline: True
```
```
In block/badblocks.c (ffffffff814b5a44)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff814c3068)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-throttle.c (ffffffff814c672a)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In lib/lockref.c (ffffffff814d61a3)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/genalloc.c (ffffffff814e9e3e)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c693)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff8160262b)
Location: arch/x86/include/asm/processor.h:658
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8160c856)
Location: arch/x86/include/asm/processor.h:658
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8165c098)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff8166862c)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff8168b599)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168e4c7)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695ed2)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff816af263)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817067e3)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff81708603)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff8170998e)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8175eb8c)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff8178372c)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff817f5742)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff8181ffb4)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2d02e)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff818a631b)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818a6a57)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff818b723e)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff818c5af4)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81914a34)
Location: arch/x86/include/asm/processor.h:658
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81919d8c)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8192236a)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194357e)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81950c43)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81969577)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196d2bf)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980fda)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff819897e1)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81996f04)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/packet/af_packet.c (ffffffff819e54ba)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In lib/dump_stack.c (ffffffff81a07835)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff81a080fe)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff81a19fe6)
Location: arch/x86/include/asm/processor.h:658
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff81035b82)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/rtc.c (ffffffff8103c5e1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046adf)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff8106290f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff810643c0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810651c2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b4bf1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067247)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b6389)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff810746f6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff81075490)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075c1b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81076c0c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff8109ae39)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810bad8b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810d0496)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810d5292)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81a9cdf9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/psi.c (ffffffff810f63d7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/locking/mutex.c (ffffffff810f77dc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810f8170)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810f8bc5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810f90a7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff810f9740)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff810fa42e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810febf3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff8110870c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff8110a6c3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff8110db0c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff81129297)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81a9c3c7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8112f387)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff81133c51)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/time/tick-common.c (ffffffff8113b0f1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113cc95)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff81141e85)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/smp.c (ffffffff81143332)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff8114d0b5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b243)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff8115b863)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff8115fbe4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811654ec)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff81168575)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff8117160f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff811771c8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff811789fc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8117aecb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117e974)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_go
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81183714)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811ce242)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/offload.c (ffffffff811f5052)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/filemap.c (ffffffff81213895)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page-writeback.c (ffffffff8121fd4c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff81272029)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff812811f4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8128fcb3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff81298260)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff812be675)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff812d94f7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812e8461)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff812f1d89)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/libfs.c (ffffffff812fa932)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/libfs.c:move_cursor
```
```
In fs/fs-writeback.c (ffffffff812ffb84)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff8130794a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/nsfs.c (ffffffff813099c2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/buffer.c (ffffffff8130dcde)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff8132413b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8132718e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/io_uring.c (ffffffff81330c70)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
```
```
In fs/mbcache.c (ffffffff8134759d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81347fd8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff813b255a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813d823c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d9684)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813e1676)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8141d0ee)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488efc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/blk-ioc.c (ffffffff814d0fe5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff814d693b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/badblocks.c (ffffffff814e3f8d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff814f16b6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-throttle.c (ffffffff814f4f7d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In lib/lockref.c (ffffffff8150202d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/rhashtable.c (ffffffff8150d8bd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff81516a74)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c2df)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff81634ee6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816403f5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81691788)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff8169e0ac)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff816c2fa9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c5b17)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816ce7f2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff816e8de7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81741b66)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff817440c9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff81745176)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8179c20f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff817c1a45)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff81836402)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff818624a1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a9d1bf)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff818f1857)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818f1efe)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81903066)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81911b7d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/xdp.c (ffffffff8193084d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81962baf)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969db4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inetpeer.c (ffffffff81976f0e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff8197be93)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8198505b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7d3b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819b555f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfcfd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (ffffffff819d0231)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6cdf)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff819dbb6e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e61c2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff819f359c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81a00f41)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6mr.c (ffffffff81a44389)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f6af)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff81a53238)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In lib/dump_stack.c (ffffffff81a771c5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff81a77a83)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff81a89da2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff81036382)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/rtc.c (ffffffff8103cda1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104725f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff8106317f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064a40)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065832)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b804a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067d50)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b984c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff810756c6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff81076460)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81076beb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81077c5c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810968c4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv4_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099957)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff810a1359)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810c0fbf)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810da446)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810df852)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81ad4649)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/psi.c (ffffffff81102177)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/locking/mutex.c (ffffffff8110359c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff81103fa0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff811049d5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff81104e89)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff81105530)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff8110620e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff8110b03f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff81114aec)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff81116a93)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81119dcc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff81135240)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81ad3cbb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:lock_hrtimer_base
```
```
In kernel/time/timekeeping.c (ffffffff8113b347)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff8113fc21)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff81140195)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8114553b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff81146d01)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81148a35)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff8114c1d1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
```
In kernel/smp.c (ffffffff8114ee72)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff81158d8a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81166f01)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff81167483)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff8116b844)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811713dc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff81174425)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff8117d48f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff811830f8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff81184849)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81186d5b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118a7f4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_go
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8118f584)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811da862)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/offload.c (ffffffff81202056)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/filemap.c (ffffffff81221065)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page-writeback.c (ffffffff8122d7fc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff81280e8a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81290e84)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8129fa43)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812a80c0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff812d0565)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff812eb007)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812f9ff1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff81303949)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff81312194)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff8131a9c0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/nsfs.c (ffffffff8131ca32)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/buffer.c (ffffffff81320cd0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff81336e9b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81339f70)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff8135f70d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81360278)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff813cb5b1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813f231c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f3672)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813fb6c6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff81436f3e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2dac)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/blk-ioc.c (ffffffff814ea3a2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff814efc94)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/badblocks.c (ffffffff814fd34d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff8150aca3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-throttle.c (ffffffff8150e5fa)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff8150ff4c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/lockref.c (ffffffff8151ff3d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/rhashtable.c (ffffffff8152b70d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff815374b4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff8159dd3f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff81656c06)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81662b05)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816b4278)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff816c0e1c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff816e5e99)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e8b47)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f2632)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff8170ce47)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81765cf8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81768234)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff8176931d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817bfcbf)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff817f23c5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff81867d72)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff818940cd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/poll_state.c (ffffffff81ad49c7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff819237a7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff81923e4e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81935e06)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff819441eb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/xdp.c (ffffffff81962dd6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff819640c4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819a0824)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inetpeer.c (ffffffff819ad8a0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff819b2839)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbad8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819dedc7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819ec27f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0688d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (ffffffff81a06d81)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d7cf)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff81a12a9e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1d1b2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2a46c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81a37b14)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6mr.c (ffffffff81a7af79)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8633f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff81a89e28)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In lib/dump_stack.c (ffffffff81aae5a5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff81aaee73)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff81ac1062)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff81bbdd0f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d140)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/rtc.c (ffffffff8103fc21)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a082)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:wait_for_master_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810691cf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b3ca)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106c182)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82cdd256)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106eaa0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdea30)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff8107c8f6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d47e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107de34)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f0b8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109befd)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv1_throttle
  - arch/x86/platform/uv/tlb_uv.c:uv4_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109f0dc)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/panic.c (ffffffff810a8199)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810c919d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/core.c (ffffffff810e3492)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810e7ba8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81bcc6b9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/sched/psi.c (ffffffff8110cdea)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/locking/mutex.c (ffffffff8110e0b4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110eb08)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8110f785)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8110fcfa)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:pv_wait_head_or_lock
  - kernel/locking/qspinlock.c:pv_wait_node
```
```
In kernel/locking/rtmutex.c (ffffffff811102e4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff8111123e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81115b49)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/power/hibernate.c:power_down
```
```
In kernel/printk/printk.c (ffffffff8111ea3c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:boot_delay_msec
```
```
In kernel/irq/manage.c (ffffffff81125464)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81125d9c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff8114444a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81bcbca4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff8114a399)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff8114eb0f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff8114f585)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff81154b9e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff81156bc3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81158677)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff8115c448)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/smp.c (ffffffff8115f80d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff81169189)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/acct.c:acct_get
```
```
In kernel/cgroup/cgroup.c (ffffffff81178574)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff81178c7f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff8117d474)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811830ec)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff811862f5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff8118f0db)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In kernel/kprobes.c (ffffffff81196f58)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8119888f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8119b5c4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119d6ea)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811a4044)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811f7342)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
```
```
In kernel/bpf/offload.c (ffffffff812292f9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/filemap.c (ffffffff8124ec83)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page-writeback.c (ffffffff8125b2f1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff812b2f89)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c372e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff812d4098)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812dd3d0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff81306cbd)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff81322db6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:__follow_mount_rcu
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff8133225f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff8133d721)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff8134c2b4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff813548ea)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/nsfs.c (ffffffff813566f9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/timerfd.c (ffffffff81370d5d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff81372f59)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
```
```
In fs/mbcache.c (ffffffff813a52e5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff813a5db3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/jbd2/journal.c (ffffffff81448e37)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff81486972)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff814fd0a5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/blk-ioc.c (ffffffff81549342)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff8154eff4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/badblocks.c (ffffffff8155c7b2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff8156bcf3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-throttle.c (ffffffff8156f0e3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff81570ffe)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/lockref.c (ffffffff8158329e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_put_return
  - lib/lockref.c:lockref_get_or_lock
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
  - lib/lockref.c:lockref_get
```
```
In lib/rhashtable.c (ffffffff8158ec3c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/genalloc.c (ffffffff8159be25)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In lib/dump_stack.c (ffffffff815e8300)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff815e8be6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff815fd4f5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
```
```
In drivers/pci/pcie/pme.c (ffffffff8163dd1a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff81706556)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_sync_wait
```
```
In drivers/xen/grant-table.c (ffffffff81711d55)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v2
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v2
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v1
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v1
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81767a88)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff817756d1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179c779)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179fade)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a7761)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aab7b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff817c8387)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81826040)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818297ab)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182aa59)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
```
```
In drivers/usb/core/message.c (ffffffff818c1dc7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff8193b8c6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff81966764)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/poll_state.c (ffffffff81bcc9b9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff819f7329)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819f7a00)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81a0aac6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81a14248)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/xdp.c (ffffffff81a36042)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a7928d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inetpeer.c (ffffffff81a977c1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81a9b706)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa606c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbde9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad9fe7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5f32)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ping.c (ffffffff81af6807)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe711)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff81b01d5c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0e8a5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1cd0c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c436)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ip6mr.c (ffffffff81b752ec)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b814a2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/packet/af_packet.c (ffffffff81b85237)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In arch/x86/kernel/nmi.c (ffffffff81c365ef)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d5ea)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/rtc.c (ffffffff8103faa1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81049522)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:wait_for_master_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106ae4f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d036)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106da62)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82fc95ea)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106ff20)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcae9e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff8107c746)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d3ee)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107daf4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ece8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109abbe)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/panic.c (ffffffff810a3ee9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810c42fe)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/core.c (ffffffff810e0e93)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810e57c1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81c45264)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/sched/psi.c (ffffffff81109f98)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/locking/mutex.c (ffffffff8110b383)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110bc00)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8110c945)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8110ceba)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:pv_wait_head_or_lock
  - kernel/locking/qspinlock.c:pv_wait_node
```
```
In kernel/locking/rtmutex.c (ffffffff8110d494)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff8110e3be)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81bdf3cd)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/power/hibernate.c:power_down
```
```
In kernel/printk/printk.c (ffffffff8111948c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:boot_delay_msec
```
```
In kernel/irq/manage.c (ffffffff811212c4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81121aac)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff811409da)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81c44ac4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff811468e9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff8114ad7f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff8114b805)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff81150e1e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff81152cc8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8115455b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff81158748)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/smp.c (ffffffff8115b7ad)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff81165828)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/acct.c:acct_get
```
```
In kernel/cgroup/cgroup.c (ffffffff811752e7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff811758cf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff8117a2e0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180080)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff81183485)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff8118c288)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In kernel/kprobes.c (ffffffff811940d8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff811959ef)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81198744)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119a72a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811a11a4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811f5eb2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
```
```
In kernel/bpf/offload.c (ffffffff81230e89)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/filemap.c (ffffffff81259043)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page-writeback.c (ffffffff8126545a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff812bec46)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cf704)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff812dfa88)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812e61d5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff8131284d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff8132dfb3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:__follow_mount_rcu
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff8133dc82)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff81349643)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff81359293)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff81361096)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/nsfs.c (ffffffff813630a4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/timerfd.c (ffffffff8137eadb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff81380da8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
```
```
In fs/mbcache.c (ffffffff813b6045)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff813b6afd)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/jbd2/journal.c (ffffffff814659d7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff814a4022)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a2c4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/blk-mq.c (ffffffff8156cddb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/badblocks.c (ffffffff81578834)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-throttle.c (ffffffff81589ead)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff8158c35f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/lockref.c (ffffffff815a011e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_put_return
  - lib/lockref.c:lockref_get_or_lock
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
  - lib/lockref.c:lockref_get
```
```
In lib/rhashtable.c (ffffffff815ab79c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/genalloc.c (ffffffff815b784c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In lib/dump_stack.c (ffffffff81bf4a00)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff8160dc3b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff81622225)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
```
```
In drivers/pci/pcie/pme.c (ffffffff816643aa)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff817238c6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_sync_wait
```
```
In drivers/xen/grant-table.c (ffffffff8172eb05)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v2
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v2
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v1
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v1
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff817827e8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff81790411)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aa449)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff817ad67e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b3601)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b70db)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff817dd197)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818368b9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8183927f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183b653)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
```
```
In drivers/usb/core/urb.c (ffffffff818cbf41)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff818cdfd7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff81941c06)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff8196ce4f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/opp/core.c (ffffffff819940c4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c45519)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff819f6d99)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819f75e3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81a0bcd1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81a144cb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a29fe1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/xdp.c (ffffffff81a38412)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a8209d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inetpeer.c (ffffffff81aa158e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81aa54e1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab04b1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7b79)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ae693a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02da2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ping.c (ffffffff81b035f7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c676)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff81b0fe3c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1c326)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2acd0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ae51)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ip6mr.c (ffffffff81b8405c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90ce2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In arch/x86/kernel/nmi.c (ffffffff81c28a7f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ee23)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/rtc.c (ffffffff81041441)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104bff7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b8bf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dac5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106e4d2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff831d3e45)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81070a70)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d5735)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff8107d8f6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff8107e78e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8107ec4b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f978)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b313)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/panic.c (ffffffff810a4b39)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/softirq.c (ffffffff810ab261)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_unlock_spin_wait
```
```
In kernel/workqueue.c (ffffffff810c5ad6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/core.c (ffffffff810e2cae)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810e7791)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81c384e4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/sched/psi.c (ffffffff8110bd27)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/locking/mutex.c (ffffffff8110d213)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110dae0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8110e778)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8110ec27)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff81c3627f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff8110eedb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81bd166b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff8111b805)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff811215a4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81121cec)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff81141c2a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81c37d31)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff81147a59)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff8114c23c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff8114ccb5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8115224e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff81153fb8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811559db)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff811599c0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/smp.c (ffffffff8115c88d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff81166e78)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81175e4d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff81176438)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff8117ae60)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b50)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff811845b5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff8118e76b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff811950d8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8119698f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81199594)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119b56a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811a1e04)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811f6da2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
```
```
In kernel/bpf/offload.c (ffffffff8123502c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/filemap.c (ffffffff8125d463)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page-writeback.c (ffffffff81269669)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff812c3ccb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d694f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff812e6ca8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812ed965)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff81318db3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff813345ff)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81343f80)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff81350023)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff8135fde3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff81367b76)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/nsfs.c (ffffffff81369b44)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/timerfd.c (ffffffff8138575b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff8138864e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In fs/mbcache.c (ffffffff813bd195)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff813bdb59)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/jbd2/journal.c (ffffffff8146b187)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff814a9f56)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff81520bc7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/blk-mq.c (ffffffff81574c7b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/badblocks.c (ffffffff81580584)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-throttle.c (ffffffff815909af)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff8159321f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/lockref.c (ffffffff815a6f0b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_put_return
  - lib/lockref.c:lockref_get_or_lock
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
  - lib/lockref.c:lockref_get
```
```
In lib/rhashtable.c (ffffffff815b6601)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff815c26c1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In lib/dump_stack.c (ffffffff81be6903)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff815f138b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff81605b05)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
```
```
In drivers/pci/pcie/pme.c (ffffffff8164674a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff81704b16)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_sync_wait
```
```
In drivers/xen/grant-table.c (ffffffff817127c5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v2
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v2
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v1
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v1
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff817660e8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff81772d21)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d1ec)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81790011)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff81796731)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179a3cb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff817c1547)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81819a81)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c53f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181e867)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
```
```
In drivers/usb/core/urb.c (ffffffff818af561)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff818b19d7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff81925396)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff8194f931)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/opp/core.c (ffffffff8197833f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c38799)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff819dcf19)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819dd763)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff819f30c7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff819fae5a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a11231)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/xdp.c (ffffffff81a1f256)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6b18c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c4de)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81a905a1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b68f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2d19)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad1c0b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee6a6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ping.c (ffffffff81aeee37)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afa2e6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff81afda2e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0a016)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b188f1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81b28a81)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ip6mr.c (ffffffff81b72cde)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fef6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In arch/x86/kernel/nmi.c (ffffffff81d46c1f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff81044b93)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/rtc.c (ffffffff810476d0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810533f8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff810763af)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff810792d2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079e02)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff832b69d1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c6f0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b836a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff8108c326)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff8108d40e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8108d8db)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e758)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab516)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff810b6359)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/softirq.c (ffffffff810bcd81)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_unlock_spin_wait
```
```
In kernel/workqueue.c (ffffffff810d873e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/core.c (ffffffff810f96ec)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810fee31)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81d56d91)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/sched/psi.c (ffffffff8112a81d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/locking/mutex.c (ffffffff8112ca53)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8112d390)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8112df08)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8112e46a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d54b62)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff8112e77b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81caa1f4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff811383f9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_wait_on_cpu_lock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff81141b35)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff8114228c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff8116509a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81d565f1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff8116b582)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff81170003)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff81170b45)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8117681e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff811786d8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8117a64b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff8117e8e0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/smp.c (ffffffff811819f0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff8118c638)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d436)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff8119da76)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff811a2945)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8940)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff811ac8e5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff811b757b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff811bdf98)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff811bfd33)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811c3374)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c54ca)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811cb5c4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff81228372)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
```
```
In kernel/bpf/offload.c (ffffffff8126f15c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/filemap.c (ffffffff812993b3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page-writeback.c (ffffffff812a60f1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff81307b64)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/hugetlb.c (ffffffff8131c70f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8132ebd8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff81335cfe)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff813653a3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff81381f47)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff813918b0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff8139e3e3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff813aea13)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff813b6726)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/nsfs.c (ffffffff813b8834)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/timerfd.c (ffffffff813d28d5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff813d598f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In fs/mbcache.c (ffffffff8140cf44)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff8140d949)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/jbd2/journal.c (ffffffff814c189c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff81502406)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ed67)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/blk-mq.c (ffffffff815d91ca)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/badblocks.c (ffffffff815e58a4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-throttle.c (ffffffff815f79af)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff815fa4cf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/lockref.c (ffffffff8160ff8b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_put_return
  - lib/lockref.c:lockref_get_or_lock
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
  - lib/lockref.c:lockref_get
```
```
In lib/rhashtable.c (ffffffff8161cb49)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff8162a60d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In lib/flex_proportions.c (ffffffff8165e4fb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff816743f5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7ff3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff81780156)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_sync_wait
```
```
In drivers/xen/grant-table.c (ffffffff8178f265)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v2
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v2
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v1
  - drivers/xen/grant-table.c:gnttab_end_foreign_transfer_ref_v1
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff817eaab8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff817f8ac1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/intel/dmar.c (ffffffff8181454c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81817881)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e6c1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81822a0b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff8184b0c7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a699f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a8ef7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
```
```
In drivers/usb/core/urb.c (ffffffff819446b1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81946c27)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff819c8323)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff819f4db1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/opp/core.c (ffffffff81a212be)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpuidle/poll_state.c (ffffffff81d57079)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff81a8d18d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff81a8da43)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81aa3f25)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81aaca9a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81ac7780)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/xdp.c (ffffffff81ad34e6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b247ac)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inetpeer.c (ffffffff81b4761e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81b4c16b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b56cbf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b808ca)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81b9085b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81baea56)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ping.c (ffffffff81baf207)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbafe6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff81bbfb2e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcce36)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdcce1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81bef15c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ioam6.c (ffffffff81c3a2fb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d21e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b796)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In arch/x86/kernel/nmi.c (ffffffff81f1514f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8104d222)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/rtc.c (ffffffff810505b4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105ee98)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810611aa)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8108397d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8108511f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81088118)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81088c50)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff834684bf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8108bab0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a074)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff8109cc86)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff8109d715)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8109e3e3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f31a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c10b0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/panic.c (ffffffff810cc8a9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/softirq.c (ffffffff810d3c21)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_unlock_spin_wait
```
```
In kernel/workqueue.c (ffffffff810f125c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/core.c (ffffffff81115bf2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/build_policy.c (ffffffff81139714)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/sched/build_utility.c (ffffffff811437a5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:collect_percpu_times
```
```
In kernel/locking/mutex.c (ffffffff8114da0e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8114e74f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8114ef4a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8114f67a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f26734)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff8114faa2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81e5a4c4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff8115ac39)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_wait
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:console_trylock_spinning
```
```
In kernel/irq/manage.c (ffffffff8116558c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81165dca)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff81198cdf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81f28473)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff8119f3c9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff811a4543)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff811a5155)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff811abc9b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff811ad8b8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811afb78)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex/core.c (ffffffff811b24e3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/requeue.c (ffffffff811b647e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/smp.c (ffffffff811b8049)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff811bbac2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd7c0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff811cdd05)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff811d33a6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9ad3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff811de41c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff811ea2dc)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff811f1338)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff811f322f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811f6bd7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811f8f0a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811ff29c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff8126935d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff812be1b9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/filemap.c (ffffffff812ef2c4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/filemap.c:folio_wake_bit
```
```
In mm/page-writeback.c (ffffffff812fed6d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff8136fcd2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/hugetlb.c (ffffffff813878f1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8139ec7b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff813a74e9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:get_any_partial
  - mm/slub.c:free_debug_processing
```
```
In fs/namei.c (ffffffff81403c4a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81413815)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff81421588)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff81432caf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff8143bd1c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/nsfs.c (ffffffff8143e10b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/timerfd.c (ffffffff8145b13d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff8145fb3a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In fs/mbcache.c (ffffffff81481e35)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81482c3e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/jbd2/journal.c (ffffffff8154c260)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff81593b49)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d8a1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/blk-mq.c (ffffffff8168bd93)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll
```
```
In block/badblocks.c (ffffffff81694974)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-throttle.c (ffffffff816aa66e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff816ac829)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/lockref.c (ffffffff816dc32c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_put_return
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
  - lib/lockref.c:lockref_get
```
```
In lib/rhashtable.c (ffffffff816ea476)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff816fba25)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In lib/flex_proportions.c (ffffffff81777c6b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff8178eaf5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc4e1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff818b6976)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_sync_wait
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8192a8ba)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff819382e7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/intel/dmar.c (ffffffff8195539c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81958805)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195ea91)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff819626bb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff81990a79)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f2e37)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
```
```
In drivers/usb/core/urb.c (ffffffff81a9d25d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81a9f08f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff81b2913f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff81b5e9c0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/opp/core.c (ffffffff81b8a231)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpuidle/poll_state.c (ffffffff81f29a52)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_estimator.c (ffffffff81c03322)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81c1c984)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81c25a04)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81c3d2d5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/xdp.c (ffffffff81c50dc0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cac186)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff81cd4825)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81cd8d65)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3d4b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10ccd)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81d21d3b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41b92)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81d42546)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4f10c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff81d56010)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62c16)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81d73aab)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81d87015)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ioam6.c (ffffffff81dd8088)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb74f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deaf9c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
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
In arch/x86/kernel/nmi.c (ffffffff820bc60f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff810596ae)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d608)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106fb1a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8109670d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810984ef)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109baa7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c86c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8c947)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8109ff30)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8ece7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff810b3b16)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff810b4830)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b56f3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6858)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ddb45)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/panic.c (ffffffff810ea279)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/softirq.c (ffffffff810f29f1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_unlock_spin_wait
```
```
In kernel/workqueue.c (ffffffff8111385c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/core.c (ffffffff8113e069)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/build_policy.c (ffffffff81163ed4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/sched/build_utility.c (ffffffff8116eeb7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_recent_times
```
```
In kernel/locking/mutex.c (ffffffff8117ccdd)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8117d7af)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8117e19a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff820d694a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff8117e3a4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rtmutex_spin_on_owner
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff820d6e02)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81184747)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff8118d159)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_wait
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:console_trylock_spinning
```
```
In kernel/irq/manage.c (ffffffff8119949c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff81199eaa)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff811d7072)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timer.c:__timer_delete_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff820d40c3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff811de0b9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff811e3e63)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff811e4a95)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff811ebf3b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff811edea8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811f0598)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex/core.c (ffffffff811f3363)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/requeue.c (ffffffff811f75be)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/smp.c (ffffffff811f92e6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff811fd952)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81210e50)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff81211655)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff81217326)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8121efa3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff81223f6c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff812304bc)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff81237e98)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff81239fc1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8123de48)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff812403da)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81246b9c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff812be19d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff8132177a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d7c7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/filemap.c (ffffffff81359de4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/filemap.c:folio_wake_bit
```
```
In mm/page-writeback.c (ffffffff813694ec)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/page_alloc.c (ffffffff813ec346)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/hugetlb.c (ffffffff81405d3a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8141e2bb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff81429f79)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff8148e0ae)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff8149ec10)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu_op_compare
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff814adab8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff814c0c6f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff814ca34c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/nsfs.c (ffffffff814ccb1b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/timerfd.c (ffffffff814ea74d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff814efc04)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In fs/mbcache.c (ffffffff81514fd8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff815159ee)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/jbd2/journal.c (ffffffff815ec078)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff8163c61f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d135d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/blk-mq.c (ffffffff81741c6d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_classic
```
```
In block/badblocks.c (ffffffff817534d4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-throttle.c (ffffffff817680f3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff8176b0c4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/rhashtable.c (ffffffff817da68f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff817ee6b5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff818fe5c1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff81a03b5b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_sync_wait
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81a87d1a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff81a98137)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abb998)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf991)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac64ef)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb42f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff81b00dc9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/sync_file.c (ffffffff81b70c16)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
```
```
In drivers/usb/core/urb.c (ffffffff81c222fd)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81c244ff)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff81cbccbf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff81cf88ae)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/opp/core.c (ffffffff81d29972)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpuidle/poll_state.c (ffffffff820d58b4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_estimator.c (ffffffff81db28e2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81dcda14)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81dd7c44)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81df5105)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/xdp.c (ffffffff81e0646f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69d59)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff81e94b05)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81e996a5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea679b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6a4d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ee918b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a9a1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81f0b3d6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18d0c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff81f2072e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d7b6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3faeb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81f54fb5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ioam6.c (ffffffff81fa9a74)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae33f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbeb8a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In lib/flex_proportions.c (ffffffff8202094b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff8204c4a5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff8213dd4f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8105ac55)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8107171a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8109982d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8109b5af)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f7b9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b01d7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2eb0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b2587)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff810b6c16)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff810b78f2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810b87d1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b996d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8fca)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/panic.c (ffffffff810f5e99)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/cpu.c (ffffffff810f9806)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_ap_sync_alive
  - kernel/cpu.c:arch_cpuhp_sync_state_poll
```
```
In kernel/softirq.c (ffffffff810feab1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_unlock_spin_wait
```
```
In kernel/workqueue.c (ffffffff8111ff3f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/core.c (ffffffff8114ab89)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/build_policy.c (ffffffff811746b4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/sched/build_utility.c (ffffffff81180624)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_recent_times
```
```
In kernel/locking/mutex.c (ffffffff8118d87d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8118e449)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8118ee3a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff82159d4c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff821565a4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff8215a192)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff811954b8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff8119e919)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_wait
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:console_trylock_spinning
```
```
In kernel/irq/manage.c (ffffffff811ab17c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff811abada)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff811eb4f2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timer.c:__timer_delete_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff82158304)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff811f2589)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff811f84d3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff811f90f5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8120066b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff812025d8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81204d28)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex/core.c (ffffffff81207adb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/requeue.c (ffffffff8120be3b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/smp.c (ffffffff8120df9f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff81212ad0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81226840)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff81227039)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff8122cc46)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff812350d3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff8123a58c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff81246fdf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff8124ef78)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff81250fd1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81254ea8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8125746a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8125dc0c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff812e4d5d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff813513fc)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e5ce)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/filemap.c (ffffffff8138b724)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/filemap.c:folio_wake_bit
```
```
In mm/page-writeback.c (ffffffff8139b68c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/page_alloc.c (ffffffff8142135d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/hugetlb.c (ffffffff814392bf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/ksm.c (ffffffff81452f4b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8145f429)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff814c37f1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff814d3f30)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu_op_compare
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff814e2898)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff814f565f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff8150058c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/nsfs.c (ffffffff81502d5b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/timerfd.c (ffffffff815214f0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff8152692b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In fs/mbcache.c (ffffffff8154c9d8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff8154d4c6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/jbd2/journal.c (ffffffff81623b58)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff81674baa)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a26d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/blk-mq.c (ffffffff8177d2ab)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/badblocks.c (ffffffff8178f694)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-throttle.c (ffffffff817a7264)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff817aa1a4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/rhashtable.c (ffffffff818198d9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff8182ea90)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81914bdf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff81941a71)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a26d60)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/dma/dmaengine.c (ffffffff81a4c9bb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_sync_wait
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a51664)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81ad30aa)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/tty/serial/8250/8250_rt288x.c (ffffffff81ad33ed)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_rt288x.c:au_putc
```
```
In drivers/char/virtio_console.c (ffffffff81ae3947)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b08278)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b12bc3)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b130dd)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b17e4b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff81b4ef79)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/misc/sram.c (ffffffff81b881d0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/dma-buf/sync_file.c (ffffffff81bc4446)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
```
```
In drivers/spi/spi-mem.c (ffffffff81c30c44)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3970f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c415da)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c4d179)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_send_command
```
```
In drivers/usb/core/urb.c (ffffffff81c8926a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81c8b54f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbbe8c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci.c (ffffffff81ce300a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81d038ec)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/rtc/interface.c (ffffffff81d245cf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d3524e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36c65)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81d3d10b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/md/md.c (ffffffff81d607dd)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/opp/core.c (ffffffff81d92b8e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpuidle/poll_state.c (ffffffff82144048)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_estimator.c (ffffffff81e22eb2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81e3e615)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81e46f73)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_ha_snapshot
```
```
In net/core/filter.c (ffffffff81e66af5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/xdp.c (ffffffff81e78cf2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec5d04)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff81ef32d5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81ef7fa5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f061cf)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_sk_get_local_port_range
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35a83)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81f48282)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/arp.c:neigh_ha_snapshot
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a4d1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81f6afb6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f78977)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff81f80108)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8d486)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9f40b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81fb49c5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ioam6.c (ffffffff8200a3fb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e99c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f9aa)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/handshake/request.c (ffffffff82092cde)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In lib/flex_proportions.c (ffffffff820a098b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff820cadb5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff8221fd4f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff81061f15)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078eda)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810a105d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810a2b7f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6c49)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e07f2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a9dd1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e2e67)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff810be056)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff810bed32)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/kernel/amd_nb.c (ffffffff810bfc11)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0dd0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f121d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/panic.c (ffffffff810ff229)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/cpu.c (ffffffff81102c16)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_ap_sync_alive
  - kernel/cpu.c:arch_cpuhp_sync_state_poll
```
```
In kernel/softirq.c (ffffffff81108161)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_unlock_spin_wait
```
```
In kernel/sys.c (ffffffff81123ae1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/workqueue.c (ffffffff811286fc)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/sched/core.c (ffffffff81156789)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/build_policy.c (ffffffff811753fe)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:kcpustat_cpu_fetch
  - kernel/sched/build_policy.c:kcpustat_cpu_fetch
  - kernel/sched/build_policy.c:kcpustat_field
  - kernel/sched/build_policy.c:kcpustat_field_vtime
  - kernel/sched/build_policy.c:task_gtime
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/sched/build_utility.c (ffffffff8118e374)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_recent_times
```
```
In kernel/locking/mutex.c (ffffffff8119c22d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8119cdf9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8119d7ea)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8223d5cc)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff822393e4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff8223da12)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff811a3e98)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff811adad9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_wait
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:console_trylock_spinning
```
```
In kernel/irq/manage.c (ffffffff811badbc)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff811bb6da)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/rcu/tree.c (ffffffff811e081e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
```
```
In kernel/time/timer.c (ffffffff81201522)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timer.c:__timer_delete_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff8223b174)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff812086c9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff8120e673)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff8120f2e5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff81216b0b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff81218ac8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8121b3f8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex/core.c (ffffffff8121eceb)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/requeue.c (ffffffff812233d0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/smp.c (ffffffff8122572f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff8122a170)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e4d0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff8123edb7)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff81244d06)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ed1e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff8125425c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff81260e59)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff81268ea8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8126ae21)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8126ed28)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8127132a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81277b4c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff81302e0d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff8137885c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a782e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/filemap.c (ffffffff813b56e4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/page-writeback.c (ffffffff813c55fc)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/page_alloc.c (ffffffff8144e0c4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In mm/slub.c (ffffffff8145a671)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472def)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/ksm.c (ffffffff8148d7ab)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In fs/namei.c (ffffffff814f5cc1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:choose_mountpoint_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81506608)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu_op_compare
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff81516688)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:mnt_get_write_access
```
```
In fs/fs-writeback.c (ffffffff81529d6f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff815351ac)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/nsfs.c (ffffffff81537983)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/timerfd.c (ffffffff81555b30)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/userfaultfd.c (ffffffff8155aef0)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In fs/mbcache.c (ffffffff81582808)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff815832f6)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/base.c (ffffffff815a30d1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff815ac3e5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/jbd2/journal.c (ffffffff8165cbf8)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In ipc/util.c (ffffffff816b0f6a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747d6d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In block/blk-mq.c (ffffffff817bf63b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/badblocks.c (ffffffff817d1df4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:_badblocks_check
```
```
In block/blk-throttle.c (ffffffff817eafe1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff817edf64)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/rhashtable.c (ffffffff8185ec29)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff81880650)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8195cb4f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8198ad01)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4b59)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a71d70)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/dma/dmaengine.c (ffffffff81a9860b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_sync_wait
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9d3b4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81aae15b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81b22aea)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/tty/serial/8250/8250_rt288x.c (ffffffff81b26fcd)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_rt288x.c:au_putc
```
```
In drivers/char/virtio_console.c (ffffffff81b36d37)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5c298)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b67a03)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d78b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff81ba74f9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/misc/sram.c (ffffffff81bdc080)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81c15cd9)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c18cc1)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb3e6e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_count_and_time
```
```
In drivers/spi/spi-mem.c (ffffffff81ce3ad4)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81ceea9f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6c6a)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d02a29)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_send_command
```
```
In drivers/usb/core/urb.c (ffffffff81d3dcba)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81d3ffff)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d70bfc)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci.c (ffffffff81d9815c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake_check_state
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81db94ac)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/rtc/interface.c (ffffffff81dda32f)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb3de)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81deca25)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81df3a5b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a337)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_disable
```
```
In drivers/md/md.c (ffffffff81e1853d)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/opp/core.c (ffffffff81e4a483)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpuidle/poll_state.c (ffffffff82226768)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e93843)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
```
```
In net/core/gen_estimator.c (ffffffff81ee0df2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81efcec5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81f05c33)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_ha_snapshot
```
```
In net/core/filter.c (ffffffff81f25ca5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/xdp.c (ffffffff81f38bc2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f88f64)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff81fb7265)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81fbbff5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbb33)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8200e3e2)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/arp.c:neigh_ha_snapshot
```
```
In net/ipv4/inet_fragment.c (ffffffff82030b81)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv4/ping.c (ffffffff820329fc)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203f037)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff82046788)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205ae16)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c76b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff82082065)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ioam6.c (ffffffff820d939c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd92c)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eeada)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In net/handshake/request.c (ffffffff8216958e)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
```
```
In lib/flex_proportions.c (ffffffff8217896b)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff821a55e5)
Location: arch/x86/include/asm/vdso/processor.h:11
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810364e2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/rtc.c (ffffffff8103cf21)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810473df)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff81062c6f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064530)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065322)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828a6051)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067840)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7864)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff810746c6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff81075460)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075beb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81076c5c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff8109ac79)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810bb32f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810d48f6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810d9a42)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81a734b9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/psi.c (ffffffff810fb487)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/locking/mutex.c (ffffffff810fc8ac)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810fd2b0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810fdce5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810fe199)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff810fe840)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff810ff51e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff8110325c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff8110d0cc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff8110f073)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff811123ac)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff8112d9f0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81a72b2b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:lock_hrtimer_base
```
```
In kernel/time/timekeeping.c (ffffffff81133af7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff811383d1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff81138945)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8113dceb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff8113f4b1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81141055)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff811447f1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
```
In kernel/smp.c (ffffffff81147492)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff811513aa)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f521)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff8115faa3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff81163e64)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811699fc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff8116ca45)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff81175aaf)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff8117b718)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8117ce69)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8117f37b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81182e14)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_go
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81187ba4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811d2e82)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/offload.c (ffffffff811fa676)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/filemap.c (ffffffff812196b5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page-writeback.c (ffffffff81225e4c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff812794da)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81289464)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff81298023)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812a06a0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff812c8b45)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff812e35e7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812f25d1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff812fbf29)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff8130a774)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff81312fa0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/nsfs.c (ffffffff81315012)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/buffer.c (ffffffff813192b0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff8132f47b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81332550)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff81357ced)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81358858)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff813c3b91)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813ea8fc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813ebc52)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813f3ca6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8142f51e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b38c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/blk-ioc.c (ffffffff814e2982)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff814e8274)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/badblocks.c (ffffffff814f592d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff81503283)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-throttle.c (ffffffff81506bda)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff8150852c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/lockref.c (ffffffff8151851d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/rhashtable.c (ffffffff81523ced)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff8152fa94)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff8159153f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff8161caa6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81628975)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81679cd8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff8168686c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff816ab979)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ae627)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b7e22)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff816d2597)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171a3e8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171c924)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff8171da0d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8178478f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff817aa7a5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff8181aa22)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff81839f4d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a73837)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff818c37a7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818c3e4e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff818d5dd6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff818e41bb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/xdp.c (ffffffff81902da6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81904094)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81940694)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inetpeer.c (ffffffff8194d710)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff819526a9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b948)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197ec37)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8198c0af)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff819a662d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (ffffffff819a6b21)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad56f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff819b235e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bc842)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff819c9afc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff819d71a4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a609)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a259cf)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff81a294b8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In lib/dump_stack.c (ffffffff81a4d3f5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff81a4dcc3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff81a5feb2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff81025e32)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/rtc.c (ffffffff8102c5b1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036563)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff81052fff)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105481c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055672)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289e18e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057bb0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289f943)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff810646f6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff810652e1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81065bdb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81066bdc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff810896b9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810a9e1f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810c2f46)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810c8a78)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_gtime
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81a2f843)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/psi.c (ffffffff810eb6a7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/locking/mutex.c (ffffffff810ecabc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810ed4c0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810edee5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810ee399)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff810eea3a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff810ef70e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810f44ff)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff810fde8c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff810ffdb3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff811030cc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/rcu/tree.c (ffffffff81113e29)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
```
```
In kernel/time/timer.c (ffffffff81120260)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81a2eefb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:lock_hrtimer_base
```
```
In kernel/time/timekeeping.c (ffffffff81126557)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff8112ae21)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff8112b395)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff81130815)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff81131fe1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81133df5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff81137009)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
```
In kernel/smp.c (ffffffff8113a76d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff8114468a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811527b1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff81152d2d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff811570b4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cbfc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff8115fbe5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff81168c4f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff8116e8b8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8116ffdc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811724be)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81175f54)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_go
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff8117ace4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811c5c52)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/offload.c (ffffffff811ed3c6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/filemap.c (ffffffff8120c8c5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page-writeback.c (ffffffff81218fec)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff8126b3ca)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8127b304)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff81289be3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812921b0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff812b9b85)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff812d4227)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812e3201)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff812ecb49)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff812fb394)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff81303bb0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/nsfs.c (ffffffff81305c02)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/buffer.c (ffffffff81309e01)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff813200a5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81323110)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff8134899d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81349508)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff813b4610)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813db37c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dc6d2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813e4726)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8141ff9e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bdac)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/blk-ioc.c (ffffffff814d3312)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff814d87e4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/badblocks.c (ffffffff814e5e3d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff814f3757)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-throttle.c (ffffffff814f7094)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff814f89dc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/lockref.c (ffffffff8150881d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/rhashtable.c (ffffffff81513fcd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff8151fd74)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff81580839)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff81611196)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81658dc8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff8166473c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff816892d9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168bf87)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695a62)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff816ad897)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/nvdimm/btt.c (ffffffff816ed0b0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:btt_write_pg
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f3848)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f5d84)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff816f6e6d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817640df)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff8179c1a2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff817e2112)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff818015bd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2fbb1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff8187d6e7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff8187dd8e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff8188fc1a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff8189dffb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/xdp.c (ffffffff818bcbd6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdec4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818fa184)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inetpeer.c (ffffffff81907200)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff8190c199)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915438)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819386f7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81945b6f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff819600ed)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (ffffffff819605e1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81969b9f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff8196e98e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81979632)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff819868ec)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81993f64)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6mr.c (ffffffff819d73c9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e278f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff819e66a8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In lib/dump_stack.c (ffffffff81a0a50f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff81a0adb3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff81a1cf82)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff81036342)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/rtc.c (ffffffff8103cd61)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104721f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff8106311f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff810649e0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810657d2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b8f61)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067cf0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba763)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff81074676)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff81075410)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81075b9b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81076c0c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In kernel/panic.c (ffffffff8109ac29)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810ba88f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810d1736)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810d5d82)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81adf8c9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/psi.c (ffffffff810f8647)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/locking/mutex.c (ffffffff810f9a6c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810fa470)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff810faea5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810fb359)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff810fba00)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff810fc6de)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff8110150f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff8110afbc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff8110cf63)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff8111029c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff8112b710)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81adef3b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:lock_hrtimer_base
```
```
In kernel/time/timekeeping.c (ffffffff81131817)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff811360f1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff81136665)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8113ba0b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff8113d1d1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113ef05)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff811426a1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
```
In kernel/smp.c (ffffffff81145342)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff8114f25a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d2f1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff8115d873)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff81161c34)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811677cc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff8116a815)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff8117387f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff811794e8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff8117ac39)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8117d14b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81180be4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_go
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff81185974)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811d0c52)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/offload.c (ffffffff811f8446)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/filemap.c (ffffffff81217455)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page-writeback.c (ffffffff81223bec)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff8127727a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81287274)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff81295e33)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8129e4b0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff812c6955)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff812e13f7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812f03e1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff812f9d19)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff81308564)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff81310d90)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/nsfs.c (ffffffff81312e02)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/buffer.c (ffffffff81316d80)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff8132cf4b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81330020)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff813557bd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81356328)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff813c1021)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813e7c7c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e8fd2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813f1026)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8142b6be)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149742c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/blk-ioc.c (ffffffff814dea12)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff814e4304)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/badblocks.c (ffffffff814f19bd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff814ff313)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-throttle.c (ffffffff81502c6a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff815045bc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/lockref.c (ffffffff815145ad)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/rhashtable.c (ffffffff8151fd7d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff8152b7d4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff81591a8f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff8164aa46)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81656945)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816a80b8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff816b4e8c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff816d9b59)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dc807)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e62f2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff81700b07)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817591b8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175b6f4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff8175c7dd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817b4b3f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff817e7245)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff8185bf02)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff8188957d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/poll_state.c (ffffffff81adfc47)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff819147a7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff81914e4e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81926e06)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff819351eb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/xdp.c (ffffffff81953dd6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff819550c4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81991824)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199eb2a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
  - net/netfilter/nf_conntrack_core.c:nf_ct_delete_from_lists
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a11fe)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_start
```
```
In net/ipv4/inetpeer.c (ffffffff819b7ee0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff819bce79)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6118)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9407)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819f68bf)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10ecd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (ffffffff81a113c1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17e0f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff81a1cbfe)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a272c2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3457c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81a41c24)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6mr.c (ffffffff81a85089)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9044f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff81a95068)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In lib/dump_stack.c (ffffffff81ab97e5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff81aba0b3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff81acc2a2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/x86/kernel/nmi.c (ffffffff81037342)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
```
In arch/x86/kernel/rtc.c (ffffffff8103ddf1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104861f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff810646df)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_panic_self_stop
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81065fc0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81066db2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b9062)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:native_apic_wait_icr_idle
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810692d0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba879)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/early_printk.c (ffffffff810766d6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_serial_putc
```
```
In arch/x86/kernel/hpet.c (ffffffff81077470)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/amd_nb.c (ffffffff81077bfb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107867a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098514)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv4_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ae27)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/panic.c (ffffffff810a2899)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/panic.c:panic_smp_self_stop
```
```
In kernel/workqueue.c (ffffffff810c22fd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff810da953)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/core.c:__cond_resched_lock
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (ffffffff810e169c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffffffff81aec099)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/psi.c (ffffffff81103787)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/locking/mutex.c (ffffffff81104bf2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff81105604)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff81106075)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff81106529)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff81106bb7)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/qrwlock.c (ffffffff8110790e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff8110c8df)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/printk/printk.c (ffffffff8111645c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/manage.c (ffffffff811184c3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffffffff8111b81a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/time/timer.c (ffffffff81137d90)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffffffff81aeb3cb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_active
  - kernel/time/hrtimer.c:lock_hrtimer_base
```
```
In kernel/time/timekeeping.c (ffffffff8113e237)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/alarmtimer.c (ffffffff81142b71)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff81142fa5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff811484d2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-common.c (ffffffff81149cc1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8114ba75)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/futex.c (ffffffff8114e6f9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
```
In kernel/smp.c (ffffffff81151f22)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff8115c077)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a49e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/cgroup/rstat.c (ffffffff8116aaa3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/rdma.c (ffffffff8116f096)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81174e44)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/stop_machine.c (ffffffff81177f85)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_machine_yield
```
```
In kernel/auditsc.c (ffffffff8118113f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/kprobes.c (ffffffff81186df8)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/kprobes.c:wait_for_kprobe_optimizer
```
```
In kernel/debug/debug_core.c (ffffffff81188569)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8118aa6b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118e504)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_go
```
```
In kernel/debug/kdb/kdb_keyboard.c (ffffffff811932c4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
```
```
In kernel/irq_work.c (ffffffff811def12)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_sync
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/offload.c (ffffffff812067dd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/filemap.c (ffffffff81226505)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/page-writeback.c (ffffffff81232e1b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/page_alloc.c (ffffffff81286e67)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff812979f4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff812a5c43)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812ae414)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/zsmalloc.c (ffffffff812d80ed)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In fs/namei.c (ffffffff812f0439)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff813014f3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_walk
  - fs/dcache.c:___d_drop
```
```
In fs/namespace.c (ffffffff8130b05e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff81319bd1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/d_path.c (ffffffff813225d9)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/nsfs.c (ffffffff8132463e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/buffer.c (ffffffff81328dd4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/timerfd.c (ffffffff8133fa50)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81342981)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In fs/mbcache.c (ffffffff81368dd4)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81369a43)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/ext4/page-io.c (ffffffff813d616e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/transaction.c (ffffffff813fd493)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fe8bd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff81406c0c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In ipc/util.c (ffffffff8144269e)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af551)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/blk-ioc.c (ffffffff814f7820)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffff814fd884)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In block/badblocks.c (ffffffff8150aa1d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-cgroup.c (ffffffff8151846f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-throttle.c (ffffffff8151c0e1)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffff8151db6c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/lockref.c (ffffffff8152dd2d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/rhashtable.c (ffffffff8153968c)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/genalloc.c (ffffffff8154556b)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/pci/pcie/pme.c (ffffffff815ac0d6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/dma/dmaengine.c (ffffffff81664fe6)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81670f25)
Location: arch/x86/include/asm/processor.h:648
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816c2518)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
```
In drivers/char/virtio_console.c (ffffffff816cf1bc)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:__send_to_port
```
```
In drivers/iommu/dmar.c (ffffffff816f4109)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f6e47)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff817009f2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/power/runtime.c (ffffffff8171a9aa)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817746a0)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff817769af)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff81777e7d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817ceb0f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/usb/core/message.c (ffffffff81800bc2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/rtc/interface.c (ffffffff818770f2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/md/md.c (ffffffff818a6cad)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In drivers/cpuidle/poll_state.c (ffffffff81aec447)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/gen_stats.c (ffffffff81935977)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819363a3)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81948456)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff819568fb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/xdp.c (ffffffff81975528)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff8197712a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b42dd)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inetpeer.c (ffffffff819c1750)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff819c6789)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfc2a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3167)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81a00aeb)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b80a)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (ffffffff81a1bd31)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a228ad)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffff81a27b43)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a328f2)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3fea5)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d889)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6mr.c (ffffffff81a9198d)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d07f)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff81aa1338)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In lib/dump_stack.c (ffffffff81ac5c35)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/flex_proportions.c (ffffffff81ac6503)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In arch/x86/lib/delay.c (ffffffff81ad8792)
Location: arch/x86/include/asm/processor.h:648
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
```
</details>
</li>
</ul>

## Differences
