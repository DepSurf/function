# Function: <code>tif_need_resched</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81042bd0)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_reschedule_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff82142fc2)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095dad)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff821430f0)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smp.c (ffffffff82140537)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/softirq.c (ffffffff810ff8f0)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff811495cb)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/sched/core.c:klp_cond_resched
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8116695a)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8116e399)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/locking/mutex.c (ffffffff8118d855)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff82155420)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8118ece2)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff82156481)
Location: include/linux/thread_info.h:182
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811c5808)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff811d8d93)
Location: include/linux/thread_info.h:182
Inline: True
```
```
In kernel/entry/kvm.c (ffffffff811d9b2a)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/time/tick-sched.c (ffffffff81205846)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (ffffffff8122700c)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/trace/trace.c (ffffffff81282938)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
```
```
In kernel/bpf/verifier.c (ffffffff8131a0c7)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/filemap.c (ffffffff8138cb09)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/vmscan.c (ffffffff813b133a)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/shmem.c (ffffffff813bf027)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff813dd533)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff813ed6e6)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/khugepaged.c (ffffffff81480bf6)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/select.c (ffffffff814ce6ee)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff814d2c7f)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff814d9d10)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/libfs.c (ffffffff814ecb56)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff814f7398)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/drop_caches.c (ffffffff8155145e)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff815c785d)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/jbd2/checkpoint.c (ffffffff8161ab6b)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_shrink_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff816376a7)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff816861cb)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e776)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - crypto/jitterentropy-testing.c:jent_raw_hires_read
```
```
In block/blk-mq.c (ffffffff8177d2ad)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/blk-mq-sched.c (ffffffff8178a7ba)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In block/blk-cgroup.c (ffffffff817a2524)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff817d084b)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:tctx_task_work
```
```
In io_uring/sqpoll.c (ffffffff817db78b)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In drivers/idle/intel_idle.c (ffffffff82143625)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff82143910)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_safe_halt
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f26f)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/char/mem.c (ffffffff81addb67)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7695)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff82144040)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81e3dcec)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/bpf/test_run.c (ffffffff81ece47a)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
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
In arch/x86/xen/smp.c (ffffffff810490a0)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_reschedule_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff822256b2)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109d2ed)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff822257d5)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smp.c (ffffffff82222546)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/softirq.c (ffffffff81108fa9)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff81154fcb)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/sched/core.c:klp_cond_resched
  - kernel/sched/core.c:rt_mutex_schedule
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8117369a)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8117b959)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/locking/mutex.c (ffffffff8119c205)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff82238260)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/osq_lock.c (ffffffff8119d690)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex_api.c (ffffffff822392c1)
Location: include/linux/thread_info.h:182
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811ddf52)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff811ee8a3)
Location: include/linux/thread_info.h:182
Inline: True
```
```
In kernel/entry/kvm.c (ffffffff811ef7da)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
```
```
In kernel/time/tick-sched.c (ffffffff8121be80)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/cgroup/rstat.c (ffffffff8123ed8a)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/trace/trace.c (ffffffff8129da28)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_gen_ctx_irq_test
```
```
In kernel/bpf/verifier.c (ffffffff8133ba55)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
```
In mm/filemap.c (ffffffff813b6678)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/vmscan.c (ffffffff813da8ba)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/shmem.c (ffffffff813ea077)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff81407493)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/memory.c (ffffffff81418cbc)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/madvise.c (ffffffff814617ea)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff814aebd0)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In fs/select.c (ffffffff8150102e)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff81503f69)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/dcache.c:select_collect2
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff8150c4b5)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/file.c (ffffffff8150f94c)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/file.c:__close_range
```
```
In fs/libfs.c (ffffffff81520a9f)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8152bad8)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/drop_caches.c (ffffffff8158735e)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/ext4/mballoc.c (ffffffff815ff475)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/jbd2/checkpoint.c (ffffffff81653a8e)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_shrink_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/fat/fatent.c (ffffffff81670b97)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In security/keys/gc.c (ffffffff816c25f8)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-mq.c (ffffffff817bf63d)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/blk-mq-sched.c (ffffffff817ccf1a)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In block/blk-cgroup.c (ffffffff817e6064)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff81814140)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:tctx_task_work
```
```
In io_uring/sqpoll.c (ffffffff8181fae2)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In drivers/idle/intel_idle.c (ffffffff82225d35)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff82226030)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_safe_halt
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1dd1)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/char/mem.c (ffffffff81b30f57)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/hw_random/core.c (ffffffff81b3aa97)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/cpuidle/poll_state.c (ffffffff82226760)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
  - drivers/cpuidle/poll_state.c:poll_idle
```
```
In net/core/dev.c (ffffffff81efc58c)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
```
In net/bpf/test_run.c (ffffffff81f91caa)
Location: include/linux/thread_info.h:182
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
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
