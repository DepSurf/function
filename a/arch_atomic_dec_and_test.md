# Function: <code>arch_atomic_dec_and_test</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff826cd78a)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/core.c (ffffffff810061fe)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048af3)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:move_myself
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105bdaa)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff8108e0ce)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mmput_async
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
```
```
In kernel/exit.c (ffffffff81092390)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff8109ad3a)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/sys.c (ffffffff810a79e2)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/umh.c (ffffffff810a9329)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810ab323)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/pid.c (ffffffff810b0956)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/pid.c:put_pid
```
```
In kernel/kthread.c (ffffffff810b3800)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810b4688)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810b5afb)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (ffffffff810b6fa5)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In kernel/groups.c (ffffffff810b8603)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810c20e7)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
```
```
In kernel/sched/fair.c (ffffffff810cd79d)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810d4257)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810d8016)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/topology.c (ffffffff810daa6c)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff810e4801)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In kernel/locking/rtmutex.c (ffffffff810e5c4e)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/power/swap.c (ffffffff810ed9a9)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff810f7339)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8110277a)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8110393f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff811053d0)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_callback
```
```
In kernel/kcmp.c (ffffffff8110ebe8)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81120efb)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/futex.c (ffffffff81128e1f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff8112d707)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff8113d451)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/namespace.c (ffffffff81144230)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8114555d)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff8114c3da)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8114ce9e)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffffffff8114dd4a)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffffffff8114e9a7)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/hung_task.c (ffffffff81169cac)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff8116ed9d)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bb6a)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b38b3)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffffffff811ca8d5)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In kernel/bpf/sockmap.c (ffffffff811ceac2)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:free_sg
  - kernel/bpf/sockmap.c:free_bytes_sg
  - kernel/bpf/sockmap.c:bpf_tcp_push
```
```
In kernel/bpf/stackmap.c (ffffffff811d0d84)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811e1a5f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/ring_buffer.c (ffffffff811e2e05)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff811e6ba3)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:put_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811e9375)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - kernel/memremap.c:dev_pagemap_put_ops
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ede35)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/oom_kill.c (ffffffff811f2cb4)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page_alloc.c (ffffffff811f5fc1)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/page-writeback.c (ffffffff811fe579)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811ffe98)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8120212d)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81203a91)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8120a9bb)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81211dc3)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffffffff812191da)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffffffff81226c09)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812311c2)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff81231d5f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81233016)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8123f797)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffffffff812440e3)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In mm/madvise.c (ffffffff81244ebb)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff81246af6)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/swap_state.c (ffffffff812486bf)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8124d615)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff812503fc)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812586cb)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff8125b35b)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/mmu_notifier.c (ffffffff8125e0a5)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff8125fd47)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff819e63d5)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8126fef7)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8127993a)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127db79)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8128318f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8128a503)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:kill_procs
```
```
In mm/zsmalloc.c (ffffffff8128dcf6)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8129022e)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812912ca)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812917c5)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/open.c (ffffffff812960fd)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffffffff81297ef3)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In fs/file_table.c (ffffffff8129b9d4)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff8129c433)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff812a0e78)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff812a3a8f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812a659c)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff812b574d)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff812bc505)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In fs/namespace.c (ffffffff812bda2c)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffffffff812c6c96)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff812c9cae)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In fs/splice.c (ffffffff812d032c)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812d9f58)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812dc9f7)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812e0dc4)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_complete
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff812e37c1)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/proc_namespace.c (ffffffff812e4211)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/mark.c (ffffffff812e5713)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812ef912)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/aio.c (ffffffff812f20b9)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff813064b1)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81309e56)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffffffff8130a26d)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffffffff8130c444)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff8130fa6b)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dio_complete
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/proc/task_mmu.c (ffffffff813183f1)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8131d0e6)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:mem_release
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813225f1)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/fd.c (ffffffff81323557)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff81324eed)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/kernfs/dir.c (ffffffff8132c447)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In fs/kernfs/file.c (ffffffff8132e233)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81330c3b)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8133391f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813340ac)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/inline.c (ffffffff8134dab6)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8135a687)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81363ea2)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813687f7)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81370505)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff81370fa1)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8138be3b)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff8138f778)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff81393a07)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffffffff81396b13)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff8139ff70)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813a2a2f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6563)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6aad)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813b7086)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813c39de)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff813cbf19)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/inode.c (ffffffff813ce1dc)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In ipc/mqueue.c (ffffffff813e0b93)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
```
```
In ipc/namespace.c (ffffffff813e364a)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffffffff813e8c66)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff813e9fd1)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813ea18b)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813ead8a)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_revoke
```
```
In security/tomoyo/common.c (ffffffff81426413)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff81428b16)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff8143aa65)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81443e74)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In security/yama/yama_lsm.c (ffffffff8144eddb)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/yama/yama_lsm.c:__report_access
```
```
In block/bio.c (ffffffff8147ba44)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-core.c (ffffffff81481ada)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-tag.c (ffffffff814859e5)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In block/blk-ioc.c (ffffffff81489195)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In block/blk-mq.c (ffffffff8148dd5d)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/partition-generic.c (ffffffff81499556)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8149bd6c)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8149c83b)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8149ccca)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8149d836)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8149eb3b)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff814a0d9b)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814a1518)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814a16f9)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814a19f9)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814a1c84)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814a1f3b)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814a3099)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814a3311)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/bsg.c (ffffffff814a5ba6)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff814a7e39)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814abbb9)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/cfq-iosched.c (ffffffff814b42a1)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81553a25)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff815e82c7)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f01de)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff815f25b4)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/tty_ldsem.c (ffffffff819f1279)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/serial/serial_core.c (ffffffff81631398)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff81649fdc)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8165196f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8168fc32)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffffffff81695d73)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffffffff816ab5c5)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816e4a80)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/scsi/scsicam.c (ffffffff816ea955)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8173d718)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/core/devio.c (ffffffff81769fef)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff817f5d2c)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff81803837)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff81807586)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81811d99)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff81812a57)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In net/core/sock.c (ffffffff81875e30)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81881cc9)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffffffff81887d7f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff8188dacb)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff8189fa66)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff818b3ade)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818baa82)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818bda3f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/netlink/af_netlink.c (ffffffff818da7e1)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff818e8268)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff818ebcc2)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff818fbab8)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8190669c)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81912413)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8191a279)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191f9bf)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff81932ebf)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/ping.c (ffffffff81939948)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81943b3f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f79d)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff81956121)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819566fe)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff8195d18f)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/anycast.c (ffffffff8195f472)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81960fe3)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff8196425b)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/addrconf.c (ffffffff8196d40a)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81978dad)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff8197c2ec)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81981e67)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81988f10)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819999c6)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff819b2196)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff819c447c)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/xdp/xdp_umem.c (ffffffff819ccc44)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
```
In lib/dec_and_lock.c (ffffffff819ce1dc)
Location: arch/x86/include/asm/atomic.h:120
Inline: True
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
In init/do_mounts.c (ffffffff82883768)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/core.c (ffffffff8100615e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810584d3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061a3a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff8109635e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
```
```
In kernel/exit.c (ffffffff8109a697)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810a306a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/sys.c (ffffffff810b06f2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/umh.c (ffffffff810b2219)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810b43a3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/pid.c (ffffffff810b9a36)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/pid.c:put_pid
```
```
In kernel/kthread.c (ffffffff810bcb00)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810bd7d8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810bed06)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (ffffffff810c0335)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/groups.c (ffffffff810c1680)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810cb407)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
```
```
In kernel/sched/fair.c (ffffffff810d6046)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810dd767)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810df7b6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/topology.c (ffffffff810e45bc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff810efdf1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/locking/rtmutex.c (ffffffff810f11e8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810f1c0d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/power/swap.c (ffffffff810f9019)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff81102d00)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8110e182)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8110f25a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff811103e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_barrier_callback
```
```
In kernel/kcmp.c (ffffffff8111a1b3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112c61b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/futex.c (ffffffff81133a0b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff81138ff7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff81148a21)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/namespace.c (ffffffff8114fd40)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811510d4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff81158ffa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81159abe)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffffffff8115aa1a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffffffff8115b787)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/hung_task.c (ffffffff81176b75)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff8117c89d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119958a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811c453e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffffffff811de1d5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811e08c2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811f1ecf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/ring_buffer.c (ffffffff811f3275)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff811f76ff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/memremap.c (ffffffff811f9f55)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/memremap.c:dev_pagemap_put_ops
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ff434)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff81204cc9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page_alloc.c (ffffffff812094a1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/page-writeback.c (ffffffff81211209)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81212768)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81214aad)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81216384)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8121d6be)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81223c60)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffffffff8122c13a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffffffff81239d08)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81244992)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff8124552f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812467eb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff81253e97)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffffffff812587e3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/madvise.c (ffffffff8125950e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff8125af24)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/swap_state.c (ffffffff8125cc95)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81261a2c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_vma
```
```
In mm/zswap.c (ffffffff812648ec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8126cd9d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff8126fe0c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/mmu_notifier.c (ffffffff81272924)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81274487)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81a21be6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff812845aa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8128df57)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8129165c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812991e1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8129f46c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:kill_procs
```
```
In mm/zsmalloc.c (ffffffff812a3636)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812a4c33)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812a62ea)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812a67e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/open.c (ffffffff812aaeed)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffffffff812ad20d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/file_table.c (ffffffff812b075c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff812b1573)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff812b5e78)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff812b8bdf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812bb66c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff812caa70)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff812d17c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/namespace.c (ffffffff812d2ecc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffffffff812dbe66)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff812deede)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/splice.c (ffffffff812e667c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812ef446)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812f0c47)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812f5b6d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_complete
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff812f8468)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/proc_namespace.c (ffffffff812f8e91)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/mark.c (ffffffff812fa303)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81304292)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/aio.c (ffffffff81306a89)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff8131bc41)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131f656)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffffffff8131fb9d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffffffff81321ca4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff813269f3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dio_complete
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_readpages
  - fs/iomap.c:iomap_readpages_actor
  - fs/iomap.c:iomap_readpages_actor
  - fs/iomap.c:iomap_read_end_io
  - fs/iomap.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff8132f271)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff813343c6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:mem_release
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81339706)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/fd.c (ffffffff8133a477)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff8133c08d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/kernfs/dir.c (ffffffff813435b7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/kernfs/file.c (ffffffff81345623)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/configfs/inode.c (ffffffff8134802b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8134acaf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8134b426)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/inline.c (ffffffff81365c56)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813729d3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8137c144)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff81380c7d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81388995)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff81389443)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813a49cb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813a80fe)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff813ac727)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffffffff813af88e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813b8d00)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813bb817)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf343)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813cfffd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813d05d6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813dd18d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff813e4fd9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/inode.c (ffffffff813e7b2c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff813ea41a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (ffffffff813fb383)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
```
```
In ipc/namespace.c (ffffffff813fe001)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffffffff81403469)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81404a1c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81404bc5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814057aa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_revoke
```
```
In security/tomoyo/common.c (ffffffff81442b13)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff814453e6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff814578a1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8145f5b3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In security/yama/yama_lsm.c (ffffffff8146bdab)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/yama/yama_lsm.c:__report_access
```
```
In block/bio.c (ffffffff81498560)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-ioc.c (ffffffff814a3005)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In block/partition-generic.c (ffffffff814b37b6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814b607c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814b6b5b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814b6fea)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814b7b56)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814b8edb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff814bb15b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814bb8d8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814bbab9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814bbdbd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814bc047)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814bc2fb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814bd279)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814bd4f1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156b255)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff816022f7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a7c4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8160dba4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a2c601)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164f458)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff8166821c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8166fcbf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816affc2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffffffff816b63c3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffffffff816cbd35)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81707fe0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170b1b5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8170e405)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff81763ae3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/core/devio.c (ffffffff8178d704)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81821cac)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff81830027)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff81833586)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff8183dd29)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183e9d7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In net/core/sock.c (ffffffff81897c10)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8189d40e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffffffff818a888f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff818ae968)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff818c21f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff818d9692)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818e19de)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818e4e1f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff818e6b1f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff819061fe)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff8191578b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81918f92)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff81929a41)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81934896)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940bef)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81948ac6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194e641)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff8196274f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/ping.c (ffffffff819695d8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81973cab)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffffffff81976a33)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982dd4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff8198ad39)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b1f4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff8199156a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/anycast.c (ffffffff819940c6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/ip6_output.c (ffffffff81995893)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81999b2b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff819a2f62)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819aea29)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1fd1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819b8510)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff819bf870)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d0316)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff819e90bd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff819fb92a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/xdp/xdp_umem.c (ffffffff81a05cf2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
```
In lib/dec_and_lock.c (ffffffff81a0769c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
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
In init/do_mounts.c (ffffffff8289a78a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/core.c (ffffffff8100631e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a45e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065109)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff8109a8a0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff8109fda9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a7f4f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/umh.c (ffffffff810b7da6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810b9f76)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/nsproxy.c (ffffffff810c3825)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810c4d7f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffffffff810c7772)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810d3475)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (ffffffff810eb1ee)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff810f784c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/power/swap.c (ffffffff8110171e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff8110b2d5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/rcu/srcutree.c (ffffffff81118fc5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff8111a3b5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/futex.c (ffffffff8113ed2a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff811441ed)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff81154071)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115bc42)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c35c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/utsname.c (ffffffff8116572c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8116620e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffffffff811670ca)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffffffff81167f93)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/bpf/syscall.c (ffffffff811d2075)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffffffff811f3905)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811f64c2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811fdde7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff8120f40c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/jump_label.c (ffffffff812113df)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/filemap.c (ffffffff812164c6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff8121c261)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8122088d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81222149)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81223d56)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81225f05)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8122d132)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8123548f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffffffff8123be4a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffffffff8124afa1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
  - mm/gup.c:put_user_pages
  - mm/gup.c:__put_user_pages_dirty
```
```
In mm/memory.c (ffffffff81256965)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff812575b4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812589f2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff81266147)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffffffff8126c051)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/page_alloc.c (ffffffff812707ad)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (ffffffff8127544f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277e65)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8127c8a5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff8127fe61)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812881c4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff8128b425)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffffffff8128dee5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812905f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff8129c5cf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a13cb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a88d8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ac2ea)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812b459e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812ba74f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812be9a4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812c0576)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812c19f6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812c1ec5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812c259c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages_release
  - mm/memremap.c:devmap_managed_enable_put
```
```
In mm/hmm.c (ffffffff812c2f29)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/hmm.c:hmm_free_rcu
```
```
In fs/open.c (ffffffff812c76e6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffffffff812c9d0e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/file_table.c (ffffffff812cd09c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff812ce2c4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff812d2c0f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff812d57df)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812d826c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff812e748d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff812ee7c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/namespace.c (ffffffff812eff9e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffffffff812fa507)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff812fd59e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/splice.c (ffffffff813052ec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff8130a532)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffffffff81310c96)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81312b48)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffffffff81316d30)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff81318a99)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/mark.c (ffffffff8131ad03)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8132558b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/aio.c (ffffffff81328079)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8133148b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_mem_free
```
```
In fs/binfmt_elf.c (ffffffff81343534)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81346e8b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffffffff8134740d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffffffff81349aea)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8134cd7c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff8134d3f8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff81356da1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/root.c (ffffffff8135a30f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8135b224)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff813606ef)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff8136b847)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/kernfs/file.c (ffffffff8136d63c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/sysfs/mount.c (ffffffff8136f5dc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffffffff813704c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813735a8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81373de0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/inline.c (ffffffff8138ef75)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8139bde7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813a2b72)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813a9fb1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff813b2a75)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff813b3612)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813cebaa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813d25ed)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffffffff813d6993)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffffffff813d9dde)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813e3b29)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813e60b2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9c9b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813fabec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb0a4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81408cc8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81410a4c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/inode.c (ffffffff81413af0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81416af9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (ffffffff814279e3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8142a636)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffffffff81430078)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff814318ce)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81431c45)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8143286b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In security/tomoyo/common.c (ffffffff814706d5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff81473062)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff81485130)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8148c9c6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffffffff814c63e8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_pc_page
```
```
In block/blk-ioc.c (ffffffff814d10c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In block/partition-generic.c (ffffffff814e1d40)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814e45dc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e4fbf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e559d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814e612a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e7bb2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814e97ee)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814e9ef5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ea118)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ea42a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ea6b7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ea999)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814eb92d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814ebba1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159b7e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81634bd7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e513)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81641d4f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff8168413e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff8169dc90)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816a573d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816e9e57)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffffffff816f02b7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffffffff81707335)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/nvdimm/bus.c (ffffffff8172e5e4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81743280)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff817467e7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81749bce)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817a187a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/core/devio.c (ffffffff817cafc4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8186481f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff81872762)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff818754b6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff818809e9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff81881695)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In net/core/sock.c (ffffffff818e214a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818e7c8e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffffffff818f3ec7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff818fa256)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff8190e955)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff8192b858)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff819301d1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81934746)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff819364e3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff819674e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff81977cd4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff8197b0be)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff8198cc3c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81998563)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a51c1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ad17f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b2dd1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff819c7824)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff819d0214)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff819dd7ca)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e05bd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecadd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_input.c (ffffffff819f57db)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6721)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff819fd43f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff81a0114f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81a05a67)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a1ab3d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffffffff81a2e511)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3f016)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff81a57538)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff81a6affd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/xdp/xdp_umem.c (ffffffff81a754ae)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In lib/dec_and_lock.c (ffffffff81a77017)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
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
In init/do_mounts.c (ffffffff8289d76f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/core.c (ffffffff810063ce)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b32e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065779)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810a0e60)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810a6390)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810ae56f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810afb33)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffffffff810be2a6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810c03f6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/nsproxy.c (ffffffff810cc935)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810cde8f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffffffff810d0842)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810dd9e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (ffffffff810f6b8e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8110367c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/power/swap.c (ffffffff8110db4e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff81117405)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/rcu/srcutree.c (ffffffff81125395)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff811267c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/futex.c (ffffffff8114a754)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff8114fccd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff8115fcc1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81167862)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811682fc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/utsname.c (ffffffff811715ec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811720ce)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffffffff81172f8a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffffffff81173e44)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/bpf/syscall.c (ffffffff811de615)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffffffff812006a5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81203480)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8120b097)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff8121ca4f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffffffff8121db90)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (ffffffff8121f01f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/filemap.c (ffffffff81223dd6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff81229c2d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8122e33d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8122fbf9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81231ae6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81233bb7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123a5c3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812436cf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffffffff8124a29a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffffffff81259491)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81264ef5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff81265b04)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81266ec2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff81274a67)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffffffff8127ae61)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127f5ed)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (ffffffff812842bd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81287955)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128c380)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff8128f2ea)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81297dc4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff8129af95)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffffffff8129db03)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812a0375)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff812ac02e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b05a3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b9e58)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812be840)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812c5ebe)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812cc62f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812d0905)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812d24c7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812d3926)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812d3df5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812d44d5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:devmap_managed_enable_put
```
```
In fs/open.c (ffffffff812d90f6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffffffff812db7ec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/file_table.c (ffffffff812deabc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff812dfd74)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff812e471f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff812e734f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e9ddc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff812f8fff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff81300285)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/namespace.c (ffffffff81301a6e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffffffff8130c287)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff8130fa8d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/splice.c (ffffffff8131837c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff8131d502)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffffffff813213ad)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81325a88)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffffffff81329bae)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff8132b8d9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/mark.c (ffffffff8132d873)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8133831b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/aio.c (ffffffff8133ae19)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff81345032)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
```
```
In fs/verity/enable.c (ffffffff8134f72a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff81351333)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff8135b972)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135f199)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffffffff8135f56f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffffffff81361d8a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8136504c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff813656a4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff8136f371)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/root.c (ffffffff8137253f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff81373674)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff8137894f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff81383a17)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/kernfs/file.c (ffffffff813857cc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/sysfs/mount.c (ffffffff8138793c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffffffff813889b1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81389f6a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8138c022)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff813a79d5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813b48ef)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813bb9d2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813c2ee1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff813cbad5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff813cc861)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813e827a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813ebccd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (ffffffff813eef59)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813f09d3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffffffff813f3e0d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813fdb59)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81400115)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81403d3b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81414abc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81414f74)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814205d4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8142a65c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/inode.c (ffffffff8142db18)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81430a35)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (ffffffff81441713)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81444366)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffffffff81449dd8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8144b62e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8144b9a5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8144c5db)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8148a495)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff8148ce02)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff8149f050)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff814a6886)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffffffff814df218)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-ioc.c (ffffffff814ea485)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In block/partition-generic.c (ffffffff814fb0ff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814fd99c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814fe536)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814fe96d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814ff4fa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81500f82)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff81502bb2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff815032b5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff815034d8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff815037ea)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81503a77)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81503d55)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81504ced)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81504f61)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bcde5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff816568f7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660a7d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8166430f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a67ee)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff816c0a00)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816c846d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8170deb7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffffffff81714753)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffffffff8172b585)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/nvdimm/bus.c (ffffffff81752884)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8176722f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176a937)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8176dd1e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817c683a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d381c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/usb/core/devio.c (ffffffff817fbbb2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8189655f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff818a4562)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff818a7266)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff818b28a9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b3535)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4f58)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff8191430d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81919eaa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffffffff81925e82)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff8192c396)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff81940fb5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff8195db94)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff8196242e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819674f2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff819694b3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff8199df75)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff819ae664)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff819b1a2e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff819c35dc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819cf167)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbec1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819e3e4f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e9b74)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff819fe3d4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81a06d64)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81a148ec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a175ed)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23af9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25220)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c48b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d3a4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff81a340cf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff81a37d2b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c5e6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a517b8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffffffff81a65084)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a75c86)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff81a8e580)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff81aa19ed)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In lib/dec_and_lock.c (ffffffff81aae3f7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
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
In init/do_mounts.c (ffffffff8100426c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/events/core.c (ffffffff810072fe)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d11c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fcce)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106c0c9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810a7cc1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/cpu.c (ffffffff810a8f89)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/exit.c (ffffffff810ae157)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:exit_mm
```
```
In kernel/ptrace.c (ffffffff810b610f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b7991)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffffffff810c55a6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810c7b86)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/kthread.c (ffffffff810d13ae)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/nsproxy.c (ffffffff810d611b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810d7c26)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffffffff810da73c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810df044)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (ffffffff81100baa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8110e1b3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/swap.c (ffffffff81118b6e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff811235da)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/rcu/update.c (ffffffff8112ff94)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:trc_read_check_handler
```
```
In kernel/rcu/srcutree.c (ffffffff81132538)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff81133f15)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/time/namespace.c (ffffffff8115a026)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/futex.c (ffffffff8115b2a9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff811604ad)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff8116f73d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff811790f2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811798a1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/utsname.c (ffffffff8118348c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81184651)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffffffff81184d8a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffffffff81185b09)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/bpf/cpumap.c (ffffffff81228245)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff8122b202)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/events/core.c (ffffffff81236f97)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff81246f6d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:copy_insn
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffffffff81249b74)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (ffffffff8124ae5a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/watch_queue.c (ffffffff8124c950)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/filemap.c (ffffffff81252c7d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff81256a95)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8125a189)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8125cfa9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_readahead_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8125e6a6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81261391)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8126a24d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8126f88f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81287be1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:put_compound_head
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812952c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:wp_page_shared
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff81295e3c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81297138)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812a5e77)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff812b171b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (ffffffff812b5d48)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b98ec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812bf36d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff812c1f9a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812cb485)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff812d070d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:lookup_node
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
```
```
In mm/mmu_notifier.c (ffffffff812d1bc4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812d6e84)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff812e1493)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/migrate.c (ffffffff812e346f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812eea25)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f3d9f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812fbba6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81301e71)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff8130734b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff813085e4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff81309696)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff8130a232)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In fs/open.c (ffffffff8130d75c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/open.c:access_override_creds
```
```
In fs/read_write.c (ffffffff81311529)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/file_table.c (ffffffff8131590c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff81317684)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff8131b90f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/exec.c:would_dump
  - fs/exec.c:exec_mmap
  - fs/exec.c:copy_string_kernel
  - fs/exec.c:bprm_mm_init
```
```
In fs/pipe.c (ffffffff8131ef0f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff81321fcc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff81331fb4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff813393f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/namespace.c (ffffffff8133a92e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffffffff81345769)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff81348e2d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/splice.c (ffffffff813508dd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff81357580)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffffffff8135bae4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/block_dev.c (ffffffff8135ee38)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffffffff8136396e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff813655b3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/notify/mark.c (ffffffff81367933)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81372114)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
```
```
In fs/aio.c (ffffffff813772af)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8138138b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_remove_personalities
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_offload_start
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:__io_req_aux_free
  - fs/io_uring.c:__io_req_aux_free
```
```
In fs/io-wq.c (ffffffff8138a625)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/verity/enable.c (ffffffff81395eb6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff81397d8a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff813a04b0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813a3766)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffffffff813a514f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff813a81cd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff813ab23f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff813ad72e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff813b6a41)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/root.c (ffffffff813ba85e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff813bb7e4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff813c1a30)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff813cea37)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
```
```
In fs/kernfs/file.c (ffffffff813cfd1d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_put_open_node
```
```
In fs/sysfs/mount.c (ffffffff813d25fc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffffffff813d36f1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813d6a78)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813d7362)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff813f39f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813ffd9c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8140c87d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_free
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8140f493)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81417c45)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
```
```
In fs/ext4/readpage.c (ffffffff814186e7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff81434dd7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81438eb1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (ffffffff8143bcc8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8143ca72)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
```
```
In fs/jbd2/commit.c (ffffffff8143fa0b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff8144b5b6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8144da88)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_read_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81451b8f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81462d7b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81463234)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8146f339)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8147a754)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/inode.c (ffffffff8147cd64)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81480625)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In ipc/mqueue.c (ffffffff81494d15)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8149510a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In security/keys/keyctl.c (ffffffff8149b7d8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8149d3b7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8149da20)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8149e63b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In security/tomoyo/common.c (ffffffff814e1627)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff814e4079)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff814f85df)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81503fd0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffffffff8153ee46)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-ioc.c (ffffffff81549425)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In block/blk-map.c (ffffffff8154a9b5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff8155de11)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff8155e10f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8155eb22)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8155f088)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8155fbc2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81561b3b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff815634cb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff81563b7f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81563e05)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff815640c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81564332)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff815646e0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81565616)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8156585a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/dec_and_lock.c (ffffffff815e8188)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81666bb5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710766)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81712a29)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175873e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff81774483)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff8177c8dd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff817c90da)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
```
```
In drivers/base/power/domain.c (ffffffff817d15a3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/block/loop.c (ffffffff817e7545)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/nvdimm/bus.c (ffffffff818112c9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81827701)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182cac9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff818302f3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8188cffa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/core/devio.c (ffffffff818cd7fc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81963ed3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff819738ee)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_sb_page
```
```
In drivers/md/dm.c (ffffffff81977d42)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81982f39)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff819848df)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9efe)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff819e631a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819ec06c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffffffff819f86be)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff819ff8a6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff81a10b75)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81a2ccb3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81a35dde)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a3ab07)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81a3ceec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff81a772c3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff81a98504)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81a9c272)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff81aaecef)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81abc04e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac9019)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ad1523)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad78e1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff81aed1a4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81af67e6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81b0586c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b085c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15940)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16e50)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e8ff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b20033)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/espintcp.c (ffffffff81b22537)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/unix/af_unix.c (ffffffff81b2441c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff81b2dcff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b31c86)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b490c9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffffffff81b5d9a3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6fe86)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff81b8b0e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff81b9d36e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/mptcp/protocol.c (ffffffff81baae5f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
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
In init/do_mounts.c (ffffffff81bd189f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/events/core.c (ffffffff810061fe)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d5dd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060994)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8106609c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81066e61)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106d9a9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810a3a39)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
```
```
In kernel/cpu.c (ffffffff810a49d9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/exit.c (ffffffff810a9811)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:exit_mm
```
```
In kernel/ptrace.c (ffffffff810b1301)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b2c24)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffffffff810c08d6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810c2ca6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/kthread.c (ffffffff810cbb8b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/nsproxy.c (ffffffff810d0c86)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810d2a7a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffffffff810d5e9c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810dbd1b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/sched/topology.c (ffffffff810ff6fa)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8110b473)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/swap.c (ffffffff8111463e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff8111f42a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/rcu/update.c (ffffffff8112bde6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:trc_read_check_handler
```
```
In kernel/rcu/srcutree.c (ffffffff8112dd28)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff8112f6b5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/futex.c (ffffffff811573e5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff8115c43d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff8116c25e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81176611)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81181a43)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/stop_machine.c (ffffffff81182c3a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/bpf/cpumap.c (ffffffff8122f005)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81233138)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/events/core.c (ffffffff81240b97)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff812515bd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:copy_insn
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffffffff81253dd0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (ffffffff8125524a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/watch_queue.c (ffffffff81256d90)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/filemap.c (ffffffff8125d84d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff81261630)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812642f5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81267305)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8126872f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8126b791)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81274cef)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8127abff)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff8128cafe)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81291b9b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:follow_page_pte
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812a013e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:wp_page_shared
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a11ac)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff812a20e8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812b12f7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff812bd61d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (ffffffff812c2c85)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c5355)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff812caf67)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff812cdb7a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812d70a5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff812dc22d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:lookup_node
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
```
```
In mm/mmu_notifier.c (ffffffff812dd5c4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812e2a11)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff812ec34c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In mm/migrate.c (ffffffff812ee8ea)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812fa095)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ff68f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff813077f6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8130ebec)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:isolate_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff8131308b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff813143a9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff813154a6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff813163de)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/open.c (ffffffff813196bc)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/open.c:access_override_creds
```
```
In fs/file_table.c (ffffffff81320e6c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff813228e4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff81328b78)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8132a43f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8132d58c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff8133d9d4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff81345055)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/libfs.c (ffffffff81351ea7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff81355d8d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/splice.c (ffffffff8135d8ad)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff81363f65)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/remap_range.c (ffffffff813668a9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/buffer.c (ffffffff8136a094)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/block_dev.c (ffffffff8136c618)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffffffff81370ccb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff81372483)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/notify/mark.c (ffffffff81374c93)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8137ff3c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
```
```
In fs/aio.c (ffffffff8138559f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8138f5f0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_personality
  - fs/io_uring.c:io_remove_personalities
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_req_clean_work
  - fs/io_uring.c:io_req_clean_work
  - fs/io_uring.c:io_req_clean_work
  - fs/io_uring.c:io_sq_thread_drop_mm_files
```
```
In fs/io-wq.c (ffffffff8139bdcc)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/io-wq.c:io_impersonate_work
```
```
In fs/verity/enable.c (ffffffff813a7bd6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff813a960a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/mbcache.c (ffffffff813b5eaf)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff813b9609)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff813bd860)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff813bec1a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff813c80e1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff813cd221)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff813d392b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff813e0667)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
```
```
In fs/kernfs/file.c (ffffffff813e18ed)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_put_open_node
```
```
In fs/configfs/inode.c (ffffffff813e5431)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813e8748)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813e9002)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff81406185)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814125b5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8141fced)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_free
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8142294f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8142b745)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
```
```
In fs/ext4/readpage.c (ffffffff8142c242)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8144d8b7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff814519da)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/fast_commit.c (ffffffff814567ff)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_update
```
```
In fs/ext4/verity.c (ffffffff8145803a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff81458df2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
```
```
In fs/jbd2/commit.c (ffffffff8145badb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff81467c96)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8146a048)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_read_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e04a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e81b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8147ea84)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81489a96)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81495458)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff8149bd08)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/keys/keyctl.c (ffffffff814b926d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff814bae9b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814bb500)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814bc12b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In security/tomoyo/common.c (ffffffff814fea57)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff815014a2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff81515722)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff815213d5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffffffff8155b654)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-ioc.c (ffffffff81565245)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In block/blk-map.c (ffffffff815667ce)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff81579c20)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff81579d6f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8157a759)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8157ac48)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8157b6e2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8157d60b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff8157e608)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff8157ecaf)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8157ef35)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8157f1e6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8157f472)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8157f7fd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff815805b6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff815807ea)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/dec_and_lock.c (ffffffff8160d348)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81687795)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d343)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8172f7b9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff817737fe)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff8178f1e3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81795a2d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff817dcd99)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
```
```
In drivers/base/power/domain.c (ffffffff817e5d53)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/block/loop.c (ffffffff817fc175)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/nvdimm/bus.c (ffffffff81820209)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81838191)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8183dbfa)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81840f6a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8189b233)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/core/devio.c (ffffffff818d88bc)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8196a7c3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff819787ee)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_sb_page
```
```
In drivers/md/dm.c (ffffffff8197c9d2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81987059)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff8198897f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca648)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff819e5b2a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819eb87c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819ff606)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff81a10f25)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81a2e26c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81a37cb0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a3cde5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81a3e3a5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff81a80036)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff81aa2454)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81aa60d2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff81ab8f50)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ac778e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4fb9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81add5a3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae3f31)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff81afa0f4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81b0366d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81b13a8c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b16b25)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23da5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffffffff81b250c0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d302)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e948)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/espintcp.c (ffffffff81b30f37)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/unix/af_unix.c (ffffffff81b32c3c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c74f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b40886)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b57cee)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffffffff81b6c186)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7e996)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff81b9a0fc)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff81c336e9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/mptcp/protocol.c (ffffffff81bbb19f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
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
In init/do_mounts.c (ffffffff81bc38af)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/events/core.c (ffffffff81005f6e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ee16)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060aa4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066506)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8106740d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106e419)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810a467f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
```
```
In kernel/cpu.c (ffffffff810a56a9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/exit.c (ffffffff810aa843)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:exit_mm
```
```
In kernel/ptrace.c (ffffffff810b28c1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b4264)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffffffff810c22d6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810c4ab6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/kthread.c (ffffffff810cd4bb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/nsproxy.c (ffffffff810d2862)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810d46ac)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffffffff810d7b89)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810ddd3b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/sched/topology.c (ffffffff8110179a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8110d293)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/swap.c (ffffffff81114dfe)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff8111f583)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/rcu/update.c (ffffffff8112c276)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:trc_read_check_handler
```
```
In kernel/rcu/srcutree.c (ffffffff8112e278)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff8112fa45)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/futex.c (ffffffff811587f9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff8115d65d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff8116cb2e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177171)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81182b93)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/stop_machine.c (ffffffff81183d8a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/bpf/cpumap.c (ffffffff81233e55)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/events/core.c (ffffffff81244937)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff81257ba4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffffffff81258460)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (ffffffff8125974a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/watch_queue.c (ffffffff8125b22c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/filemap.c (ffffffff81260614)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_private_2
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff81265e70)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81269ed5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8126ba7c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8126e4c9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81270321)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81279fef)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8127fd78)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81291d76)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8129748b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812a5a7b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/mincore.c (ffffffff812a6dc6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff812a7978)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812b69c7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff812c25ad)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/memory_hotplug.c (ffffffff812c6a6b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In mm/madvise.c (ffffffff812c9b01)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cc005)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812d1a45)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff812d4ea1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812de69c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff812e3aca)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In mm/mmu_notifier.c (ffffffff812e4d44)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812ea1a1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812f4a7b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81300e41)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81306331)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8130df77)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81315143)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff813192bd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8131b1d0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff8131bb76)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff8131c4b4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/open.c (ffffffff8131f957)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff81326f6c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff813289a4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff8132e9d8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813303df)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff81332f2c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff81343cd3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff8134b3d5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/libfs.c (ffffffff81358bcb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff8135c96d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/splice.c (ffffffff81364341)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff8136a9e5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/remap_range.c (ffffffff8136d159)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/buffer.c (ffffffff81371349)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/block_dev.c (ffffffff81372f48)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffffffff813775b1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff81378563)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/notify/mark.c (ffffffff8137b653)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81386bef)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
```
```
In fs/aio.c (ffffffff8138c80f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8139eb26)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_free_work
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_remove_waitqs
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_poll_remove_double
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_dismantle_req
  - fs/io_uring.c:io_req_complete_failed
  - fs/io_uring.c:io_req_complete_post
```
```
In fs/io-wq.c (ffffffff813a24c0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cb
```
```
In fs/verity/enable.c (ffffffff813aec38)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/read_metadata.c (ffffffff813b06ef)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/verity/verify.c (ffffffff813b0b4a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/mbcache.c (ffffffff813bce8f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff813c0774)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff813c49a8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff813c588b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff813cf121)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff813d40f1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff813da75b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff813e7197)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
```
```
In fs/kernfs/file.c (ffffffff813e851d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_put_open_node
```
```
In fs/configfs/inode.c (ffffffff813ec041)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813ef058)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813efb72)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff8140c664)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81418a20)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8142087a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_free
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8142915d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81432365)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff81432f22)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff814533b9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff8145710a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/fast_commit.c (ffffffff8145c1af)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_update
```
```
In fs/ext4/verity.c (ffffffff8145d9f2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8145e7ee)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
```
```
In fs/jbd2/commit.c (ffffffff8146141b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff8146d29e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8146f7cd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8147348b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff814843ad)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81484609)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8148f306)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8149a4b8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff814a0e22)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/keys/keyctl.c (ffffffff814bf0bd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff814c0d69)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814c13c0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814c1ffb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In security/tomoyo/common.c (ffffffff815056f7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff81507f82)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff8151c0a5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff815277db)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffffffff81563ce4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/blk-ioc.c (ffffffff8156d8b5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In block/blk-map.c (ffffffff8156ed0c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff81581953)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff81581a9f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81582489)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81582978)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff815833e9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8158519b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff8158618f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff8158680f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81586a91)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81586d4c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81586fb2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8158733d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81588126)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8158835a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/buildid.c (ffffffff815eff3d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/dec_and_lock.c (ffffffff815f0aa8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166a405)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff817110b0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8171381c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff817571be)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff81771fd0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff817786ed)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff817c1155)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
```
```
In drivers/base/power/domain.c (ffffffff817ca163)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/block/loop.c (ffffffff817e1225)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/nvdimm/bus.c (ffffffff818034e9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8181b46e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81820d8a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8182415a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8187da90)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/core/devio.c (ffffffff818bb96c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8194e5d3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff8195d5ce)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_sb_page
```
```
In drivers/md/dm.c (ffffffff81960866)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff8196b739)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196d05f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af841)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff819cbc3a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819d1e6c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819e8ac3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff819f7d95)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81a14f23)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81a1ee41)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a23ba5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81a4dacc)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
```
```
In net/netlink/af_netlink.c (ffffffff81a6a590)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff81a8d17a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81a91292)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff81aa4203)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ab279e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac003f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81ac8672)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81acf113)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae5834)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81aeeead)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81b018c9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b04843)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11a80)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffffffff81b12ce0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1af45)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c6ca)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/espintcp.c (ffffffff81b1ec65)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/unix/af_unix.c (ffffffff81b2535e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff81b29baf)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e116)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81b45888)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffffffff81b5a4b9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d596)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff81b8906e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff81c25a0c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/mptcp/protocol.c (ffffffff81baa7df)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In init/do_mounts.c (ffffffff81c94912)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/events/core.c (ffffffff8100661e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81044b86)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106a764)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070625)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071798)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079d36)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810b5e9f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
```
```
In kernel/cpu.c (ffffffff810b6ee9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/exit.c (ffffffff810bc36a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:exit_mm
```
```
In kernel/ptrace.c (ffffffff810c4a61)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/umh.c (ffffffff810d4e16)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810d76de)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/kthread.c (ffffffff810e06ab)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/nsproxy.c (ffffffff810e59a2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810e788c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/reboot.c (ffffffff81ca574a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/reboot.c:hw_protection_shutdown
```
```
In kernel/groups.c (ffffffff810eb439)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810f29b6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/sched/topology.c (ffffffff8111d857)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8112cad3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/swap.c (ffffffff8113548a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff8113f9ef)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/rcu/update.c (ffffffff8114ce1a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:trc_read_check_handler
```
```
In kernel/rcu/srcutree.c (ffffffff8114f735)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff81151285)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/futex.c (ffffffff8117d703)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff8118295d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff81192730)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119e8a0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/user_namespace.c (ffffffff811aac23)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/stop_machine.c (ffffffff811abf17)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/bpf/cpumap.c (ffffffff8126db95)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/events/core.c (ffffffff8127f8d7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff81291259)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/jump_label.c (ffffffff8129547a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/watch_queue.c (ffffffff8129702c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/filemap.c (ffffffff8129d005)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_private_2
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff812a269a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812a6b65)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff812a8749)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - mm/readahead.c:read_cache_pages_invalidate_page
```
```
In mm/swap.c (ffffffff812ab4d1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff812ad5c3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812b8010)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812be085)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff812d142e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812d7e38)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812dd0e4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memory.c:put_page
```
```
In mm/mincore.c (ffffffff812e829f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff812e8f98)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812f8de7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff81305f7d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/memory_hotplug.c (ffffffff8130b517)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In mm/madvise.c (ffffffff8130eb21)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813111df)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff813171ac)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff8131a4ab)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff813259c6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:add_hugetlb_page
```
```
In mm/mempolicy.c (ffffffff8132adaa)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:lookup_node
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In mm/mmu_notifier.c (ffffffff8132cb54)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff813320c0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff8133f21b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8134aab8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_put_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff81350181)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff81358dd6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813611d9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff813659a9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff813667b9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813683d2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff81368e33)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff813697b1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/open.c (ffffffff8136cef7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff8137452c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff81375f74)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff8137c1e8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8137db9c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff813806b9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff81391603)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff81399235)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/libfs.c (ffffffff813a72b8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff813aadbd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/splice.c (ffffffff813b2b55)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff813b96a5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/remap_range.c (ffffffff813bbe36)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/buffer.c (ffffffff813bfc57)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff813c3bb6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff813c4e43)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/notify/mark.c (ffffffff813c83f5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/userfaultfd.c (ffffffff813d3ef1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
```
```
In fs/aio.c (ffffffff813d9e52)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff813ef002)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_req_task_link_timeout
  - fs/io_uring.c:io_wq_free_work
  - fs/io_uring.c:io_clean_op
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_poll_remove_double
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:__io_commit_cqring_flush
```
```
In fs/io-wq.c (ffffffff813f301c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_wqe_dec_running
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:create_worker_cb
  - fs/io-wq.c:io_worker_cancel_cb
```
```
In fs/verity/enable.c (ffffffff813fe7d8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/read_metadata.c (ffffffff814002d9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/verity/verify.c (ffffffff8140074a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/mbcache.c (ffffffff8140ca4f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff814105dd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8141415c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff81415e6d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff814203b1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff81425801)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff8142be95)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff81438d47)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
```
```
In fs/kernfs/file.c (ffffffff8143a24d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_put_open_node
```
```
In fs/configfs/inode.c (ffffffff8143ddfc)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81440f48)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81441a62)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff8145f0df)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8146bc25)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81473c3d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_free
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8147cf56)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81485bf5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff81486877)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff814a7396)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff814ab19e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/fast_commit.c (ffffffff814afa1f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_update
```
```
In fs/ext4/verity.c (ffffffff814b2eaf)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff814b3b5e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
```
```
In fs/jbd2/commit.c (ffffffff814b6908)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff814c3b29)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff814c6237)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca080)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff814dba2a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbc89)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814e6d76)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff814f1f25)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/inode.c (ffffffff814f5de7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/readdir.c (ffffffff814f8e0d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/keys/keyctl.c (ffffffff81517add)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff815197b1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81519e30)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8151a9eb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81562517)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff815651bd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff8157a165)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81585a6b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/fops.c (ffffffff815c5375)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
  - block/fops.c:blkdev_bio_end_io
```
```
In block/bio.c (ffffffff815c79b4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_put
```
```
In block/blk-ioc.c (ffffffff815d1ea5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In block/blk-map.c (ffffffff815d3346)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff815e6d51)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff815e6e96)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff815e77e3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff815e7cb1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff815e8cd9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff815eaaf8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff815ebbb8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff815ec35c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff815ec5cd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff815ec884)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff815ecb2f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff815eceac)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff815eddc3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff815edffa)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/buildid.c (ffffffff8165d1d9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/dec_and_lock.c (ffffffff8165dbe8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178dbc7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff817910d2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff817da9fe)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff817f7d6d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff817fe59a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8184bc55)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
```
```
In drivers/base/power/domain.c (ffffffff81855902)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
```
In drivers/block/loop.c (ffffffff8186dbc9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/nvdimm/bus.c (ffffffff8188da69)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818a58de)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab6df)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff818af997)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8190f18c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/core/devio.c (ffffffff81951f78)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff819f39d6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff81a02e3b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_sb_page
```
```
In drivers/md/dm.c (ffffffff81a0a257)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81a13bf9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff81a1508f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5dcc1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff81a7b29a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/skbuff.c (ffffffff81a81aec)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81a962ab)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff81aa99c5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81ac8833)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81ad2ee1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81ad822e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81b06361)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
```
```
In net/netlink/af_netlink.c (ffffffff81b23b90)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff81b48319)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81b4c626)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff81b6040e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f687)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7dcaf)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81b86edb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8dab7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba5244)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81baf27d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81bc3649)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6ba1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5574)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd6bdb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf4bb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be103a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/espintcp.c (ffffffff81be38d3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/unix/af_unix.c (ffffffff81bea444)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff81bef765)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4403)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81c0c9e5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffffffff81c21b39)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c353f6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47582)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81c48fac)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff81c5517e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff81d421db)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/mptcp/protocol.c (ffffffff81c7e660)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In init/do_mounts.c (ffffffff81e43ac2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/events/core.c (ffffffff810059ff)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8104d215)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810779f3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107db7a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f809)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81088b76)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810cc3a6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
```
```
In kernel/cpu.c (ffffffff810cd639)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/exit.c (ffffffff810d2db2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810dbd71)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/umh.c (ffffffff810eddcc)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810eef81)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
```
In kernel/kthread.c (ffffffff810f9967)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/nsproxy.c (ffffffff810ff77f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff81101b0b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/reboot.c (ffffffff81e54feb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/reboot.c:hw_protection_shutdown
```
```
In kernel/groups.c (ffffffff81106360)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff8110eff1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81141229)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:destroy_sched_domain
  - kernel/sched/build_utility.c:sched_put_rd
  - kernel/sched/build_utility.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8114dd16)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/swap.c (ffffffff81157975)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff81163390)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/rcu/update.c (ffffffff81172969)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic_cb
```
```
In kernel/rcu/srcutree.c (ffffffff81177232)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff811794c5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/futex/core.c (ffffffff811b278c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff811b9235)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff811c3170)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf019)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/user_namespace.c (ffffffff811dc2b5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/stop_machine.c (ffffffff811dd929)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/bpf/cpumap.c (ffffffff812bc9b5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/events/core.c (ffffffff812d48f8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff812e67f9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/jump_label.c (ffffffff812eb259)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/watch_queue.c (ffffffff812ed430)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In mm/filemap.c (ffffffff812f4082)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff812fb1ba)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812fdbd1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_write_one
```
```
In mm/readahead.c (ffffffff813019a6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813052bd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8130805f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8130ed35)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_page_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8131993b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81330ec8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8133796f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/memory.c (ffffffff81348102)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/mincore.c (ffffffff81349614)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff8135f647)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff81372dfe)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:page_frag_free
```
```
In mm/memory_hotplug.c (ffffffff81374268)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In mm/madvise.c (ffffffff81376b14)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c13e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff813828e9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff81385978)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81394623)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:add_hugetlb_page
```
```
In mm/mempolicy.c (ffffffff8139a789)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In mm/mmu_notifier.c (ffffffff8139cedf)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff813a31a1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff813b6020)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff813b6460)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1a6d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_put_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff813c8340)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff813d3006)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813dd414)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff813e1e67)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff813e3ae2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e5a53)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff813e67a6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/open.c (ffffffff813eb1ba)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff813f350c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff813f4f23)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff813fb272)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813fe3f0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814006ad)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff814135af)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff8141bb75)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/libfs.c (ffffffff8142c7d1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff81431c6d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/splice.c (ffffffff81437bc6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff8143f0fd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/remap_range.c (ffffffff81441dd8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/buffer.c (ffffffff814468f0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff8144a787)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff8144bc96)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/notify/mark.c (ffffffff8144f535)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8145d900)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
```
```
In fs/aio.c (ffffffff81464322)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff814722f5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/read_metadata.c (ffffffff81474073)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/verity/verify.c (ffffffff8147476d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff814860cf)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8148a271)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff8148d644)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff81498331)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8149ebc1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff814a5ad3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff814b3e27)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
```
```
In fs/configfs/inode.c (ffffffff814b96fe)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff814bcab9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff814bd649)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff814ddb2f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814e0d0b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff814f5426)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_free
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff814ff7a8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815091a6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff8150a17d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/fast_commit.c (ffffffff81537e8f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_update
```
```
In fs/ext4/verity.c (ffffffff8153c64a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8153d38e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
```
```
In fs/jbd2/commit.c (ffffffff8154038b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff8154e76e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815511f8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81555d96)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff815695fe)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81569902)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81574b23)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8157f847)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/inode.c (ffffffff81584bbc)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/readdir.c (ffffffff8158946b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/keys/keyctl.c (ffffffff815aa503)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff815ac38d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff815acb9b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff815ad868)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In security/tomoyo/common.c (ffffffff815fd5f2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff816009d4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff81618249)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81626574)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bdev.c (ffffffff8166ed77)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put_whole
```
```
In block/fops.c (ffffffff81670473)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
  - block/fops.c:blkdev_bio_end_io
```
```
In block/bio.c (ffffffff816726b0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
  - block/bio.c:bio_put
```
```
In block/blk-flush.c (ffffffff8167c119)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff8167df9a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-map.c (ffffffff8167f0a4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/blk-mq.c (ffffffff816879e5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/partitions/core.c (ffffffff81695f2e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff816960e4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81696c17)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81697262)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff81698470)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8169a642)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff8169bba9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff8169c58d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8169c912)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8169cc0a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8169cfcb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8169d3d9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8169e3b8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8169e707)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In io_uring/io_uring.c (ffffffff816d88bf)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_wait_rsrc_data
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_queue_linked_timeout
  - io_uring/io_uring.c:io_req_task_link_timeout
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_put
```
```
In io_uring/io-wq.c (ffffffff816dbb91)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wqe_dec_running
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/buildid.c (ffffffff81776640)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/dec_and_lock.c (ffffffff8177720f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c637c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff818c8d7a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff81919969)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff81936ae8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff8193db53)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff8199c9ca)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
```
In drivers/base/firmware_loader/main.c (ffffffff819a03df)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff819b5645)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff819d6f89)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff819ef803)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5e6c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff819fa906)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff81a63e24)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/usb/core/devio.c (ffffffff81aaaf52)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81b5d671)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff81b693de)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_sb_page
```
```
In drivers/md/dm.c (ffffffff81b72281)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81b7c4e0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7deaf)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcde4c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff81bed246)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/skbuff.c (ffffffff81bfddd1)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81c1fabe)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/core/dst.c (ffffffff81c21e05)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81c44d99)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81c51818)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81c53953)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81c5900a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81c8c112)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff81cacbcb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/tcp.c (ffffffff81ceed1b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81cfed4d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/fib_semantics.c (ffffffff81d37c24)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81d425b7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c36c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d7b5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81d7b32a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/unix/af_unix.c (ffffffff81d81df3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/route.c (ffffffff81da7956)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd2dd6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/dns_resolver/dns_key.c (ffffffff81f0eb38)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/mptcp/protocol.c (ffffffff81e1d74b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
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
In init/do_mounts.c (ffffffff83e6232e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/events/core.c (ffffffff81006f6f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8105969b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088593)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f108)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810918f5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c726)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810e9a56)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:mm_access
  - kernel/fork.c:__mmput
  - kernel/fork.c:__put_task_struct
```
```
In kernel/cpu.c (ffffffff810eb6f9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/exit.c (ffffffff810f190f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810fbe81)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/umh.c (ffffffff8110f25e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff81110631)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
```
In kernel/kthread.c (ffffffff8111c6b7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/nsproxy.c (ffffffff811244af)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff81126cdb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/reboot.c (ffffffff81127a5b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/groups.c (ffffffff8112bfad)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff81135e04)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8116c50c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:destroy_sched_domain
  - kernel/sched/build_utility.c:sched_put_rd
  - kernel/sched/build_utility.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8117ced6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/swap.c (ffffffff81188861)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff81196fd0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/rcu/update.c (ffffffff811a9319)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic_cb
```
```
In kernel/rcu/srcutree.c (ffffffff811ae936)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff811b0c25)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/futex/core.c (ffffffff811f362c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff811fa775)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff81205350)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81212959)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81221b45)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/stop_machine.c (ffffffff81223399)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/bpf/cpumap.c (ffffffff8131fdf5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/events/core.c (ffffffff8133cce7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff813502dd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/jump_label.c (ffffffff813552e9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In kernel/watch_queue.c (ffffffff813577f0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In mm/filemap.c (ffffffff8135e382)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/oom_kill.c (ffffffff81364467)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff813683a8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_write_one
```
```
In mm/readahead.c (ffffffff8136c192)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff8136f4c3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8137200f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813810db)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff8138d927)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff813a76f9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813af00f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff813c05a3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff813c10c7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/rmap.c (ffffffff813da4a7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff813f057e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:__free_pages
```
```
In mm/memory_hotplug.c (ffffffff813f1d3b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In mm/madvise.c (ffffffff813f44e6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f98de)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff813fc895)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff814036b5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8141309d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:add_hugetlb_folio
```
```
In mm/mempolicy.c (ffffffff8141a77f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In mm/mmu_notifier.c (ffffffff8141c30f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81422e1a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81436174)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8143889d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443b5b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_put_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8144cbe5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff81458820)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8146412a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff8146944a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff8146b4bf)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146d557)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8146e2a6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/open.c (ffffffff8147340c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff8147c2ac)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff8147e0b3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff81485333)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff81488070)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8148a87d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff8149c8ac)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/dcache.c:copy_name
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff814a7cc5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/libfs.c (ffffffff814ba041)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff814bfd0d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/splice.c (ffffffff814c5ec7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff814cdd7d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/remap_range.c (ffffffff814d09f7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/buffer.c (ffffffff814d59fb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff814d8e89)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff814da26f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/notify/mark.c (ffffffff814dddb5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ecdf5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
```
```
In fs/aio.c (ffffffff814f4652)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff81503de3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815062c7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/verity/verify.c (ffffffff81506d69)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff81519921)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8151c061)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff81520c16)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff8152c521)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff81533911)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff8153b0e3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff8154ac07)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
```
```
In fs/configfs/inode.c (ffffffff81550e8e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81554619)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff815552c9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff81576b74)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8157a2f6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81590e46)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_free
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff81599f54)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815a3d46)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff815a4ca2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/fast_commit.c (ffffffff815d609e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_update
```
```
In fs/ext4/verity.c (ffffffff815dad3a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff815dbbae)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
```
```
In fs/jbd2/commit.c (ffffffff815def0b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff815eede4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815f2364)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff815f748e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d1de)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d533)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8161a933)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81625527)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/inode.c (ffffffff8162ad2c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/readdir.c (ffffffff8162f70f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/keys/keyctl.c (ffffffff81654803)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8165681d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816570bb)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81657ea8)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In security/tomoyo/common.c (ffffffff816ae3d4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff816b193b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/audit.c (ffffffff816c148a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In security/apparmor/domain.c (ffffffff816cbae2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/lsm.c (ffffffff816da8e2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/safesetid/lsm.c (ffffffff816ecbca)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
```
```
In block/bdev.c (ffffffff8172a04a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put_whole
```
```
In block/fops.c (ffffffff8172b813)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
  - block/fops.c:blkdev_bio_end_io
```
```
In block/bio.c (ffffffff8172e030)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_dirty_fn
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-flush.c (ffffffff81738999)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff8173ac0a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-map.c (ffffffff8173c1a4)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/blk-mq.c (ffffffff81745d7a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/partitions/amiga.c (ffffffff81755419)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81755c65)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8175614a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff817573e0)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81759ae2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff8175ac6d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff8175b38a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8175b579)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8175b78b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8175b9c7)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8175bea3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8175cdee)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8175d061)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In io_uring/io_uring.c (ffffffff8178c552)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In io_uring/timeout.c (ffffffff81799e59)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
```
In io_uring/rsrc.c (ffffffff817a0dea)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_wait_rsrc_data
  - io_uring/rsrc.c:io_rsrc_put_work
```
```
In io_uring/io-wq.c (ffffffff817a7c9d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wqe_dec_running
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In drivers/pci/p2pdma.c (ffffffff8191bee3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16cab)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a1a0fd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a755f9)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff81a96988)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81a9ea83)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81acea2c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_domain_free
```
```
In drivers/base/power/domain.c (ffffffff81b0dc1a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11f6a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff81b29fc5)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81b51c69)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81b6cdf3)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b73439)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81b78906)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff81bf3007)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/usb/core/devio.c (ffffffff81c323b2)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81cf75bd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff81d04d65)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_sb_page
```
```
In drivers/md/dm.c (ffffffff81d0ebbe)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81d1a310)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1be8f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d77c52)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff81d99506)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/skbuff.c (ffffffff81da5006)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81dd0863)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/core/dst.c (ffffffff81dd4359)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81dff35c)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e06cd6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e09107)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81e0ef6a)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81e47364)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff81e6963b)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/tcp.c (ffffffff81eb1f97)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3b92)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f00074)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81f0b447)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f26501)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38d85)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81f48399)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/unix/af_unix.c (ffffffff81f4f333)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/route.c (ffffffff81f76f8e)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa42c6)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/dns_resolver/dns_key.c (ffffffff842b36ec)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
```
In net/mptcp/protocol.c (ffffffff81ff4ecd)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8201f08d)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/dec_and_lock.c (ffffffff8201fc9f)
Location: arch/x86/include/asm/atomic.h:121
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
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
In init/do_mounts.c (ffffffff83682838)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/events/core.c (ffffffff8100670f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8105ac42)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108bc19)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092008)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094832)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f1f3)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810f5667)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:mm_access
  - kernel/fork.c:__mmput
  - kernel/fork.c:__put_task_struct
```
```
In kernel/cpu.c (ffffffff810f7339)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/exit.c (ffffffff810fd87d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff81107f21)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/umh.c (ffffffff8111b6fe)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff8111c831)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
```
In kernel/kthread.c (ffffffff8112a8f2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/nsproxy.c (ffffffff811317af)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff8113417b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/reboot.c (ffffffff81134efb)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In kernel/groups.c (ffffffff81138e0d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff81143575)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8117c95c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:destroy_sched_domain
  - kernel/sched/build_utility.c:sched_put_rd
  - kernel/sched/build_utility.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8118db86)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/swap.c (ffffffff81199a21)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff811a8ae0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/rcu/update.c (ffffffff811bb069)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic_cb
```
```
In kernel/rcu/srcutree.c (ffffffff811c0923)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff811c2bf5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In kernel/futex/core.c (ffffffff81207dde)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff8120fb15)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff8121ac20)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228301)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81237ff5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/stop_machine.c (ffffffff81239bc9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/trace/trace_events_user.c (ffffffff812c337a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
  - kernel/trace/trace_events_user.c:user_event_mm_destroy
```
```
In kernel/bpf/cpumap.c (ffffffff8134f613)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In kernel/events/core.c (ffffffff8136de57)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff813814c3)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/jump_label.c (ffffffff813867d9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In kernel/watch_queue.c (ffffffff81389060)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In mm/filemap.c (ffffffff813910f4)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/oom_kill.c (ffffffff81396939)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/readahead.c (ffffffff8139e2f7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813a15e3)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff813a41b1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813b2494)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813c0324)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff813db19c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e35ee)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff813f52f9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813f5de5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/rmap.c (ffffffff8140ebe7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff8142410e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:__free_pages
```
```
In mm/memory_hotplug.c (ffffffff814258e8)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff81427b73)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c858)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8142fc9b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff814375cf)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81446691)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:add_hugetlb_folio
```
```
In mm/mempolicy.c (ffffffff8144dcf5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
```
```
In mm/mmu_notifier.c (ffffffff8144f8bf)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81457f8f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8146bd4a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:migrate_folio_undo_src
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8146e59d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814790a9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_put_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff81482510)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8148e3ed)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81499bdd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff8149e3d9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff814a02a2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814a1f9c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/page_idle.c (ffffffff814a2c43)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_folio
```
```
In fs/open.c (ffffffff814a7a81)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff814b0f5d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/file_table.c:init_file
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff814b3063)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff814ba3a1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814bcf5d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814c0a4d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff814d1c3e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/dcache.c:copy_name
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff814dcca5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/libfs.c (ffffffff814eefbe)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff814f4f8d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/splice.c (ffffffff814fb3a8)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff81503f6d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/remap_range.c (ffffffff815070f7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/buffer.c (ffffffff8150c25d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/mpage.c (ffffffff8150e1af)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/direct-io.c (ffffffff81510496)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/notify/mark.c (ffffffff815145e5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81523b24)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
```
```
In fs/aio.c (ffffffff8152b422)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/read_metadata.c (ffffffff8153d5fd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/verity/verify.c (ffffffff8153df03)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff81551215)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff815542a0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff81558bcf)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff815648e1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8156bb01)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff815733f0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff81582857)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
```
```
In fs/configfs/inode.c (ffffffff81588b6e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8158c399)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8158d069)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff815ae0dc)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815b1e89)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff815c6383)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_put_free
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff815d0735)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815da7c6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff815db6a9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/fast_commit.c (ffffffff8160dc4e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_update
```
```
In fs/ext4/verity.c (ffffffff81611da4)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8161366e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
```
```
In fs/jbd2/commit.c (ffffffff8161813b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/block.c (ffffffff816241b6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff81626dd4)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8162a454)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f5b6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8164509e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff816453f2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81652c33)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8165d897)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/inode.c (ffffffff81662f4c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/readdir.c (ffffffff81667982)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/keys/keyctl.c (ffffffff8168d043)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8168f05d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8168f955)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81690728)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In security/tomoyo/common.c (ffffffff816e6e04)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff816ea338)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/audit.c (ffffffff816fa0aa)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In security/apparmor/domain.c (ffffffff8170477d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/lsm.c (ffffffff81714075)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/safesetid/lsm.c (ffffffff81726ff7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
```
```
In block/bdev.c (ffffffff81766405)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put_whole
```
```
In block/fops.c (ffffffff81767693)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
  - block/fops.c:blkdev_bio_end_io
```
```
In block/bio.c (ffffffff8176a300)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put
```
```
In block/blk-flush.c (ffffffff81774fd9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff817772aa)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff8178258a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/partitions/amiga.c (ffffffff817917d6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8179256d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81792edf)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff81794761)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81796fd2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff81798b1c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff81799498)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8179982c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81799c7f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8179a074)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8179a713)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8179b862)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8179bb53)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In io_uring/io_uring.c (ffffffff817cd716)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_eventfd_ops
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/timeout.c (ffffffff817daf29)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
```
In io_uring/kbuf.c (ffffffff817e010e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817e8b5d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_dec_running
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In drivers/pci/p2pdma.c (ffffffff8195f4f6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fd3b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a62c9a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abfde9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff81ae2199)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81aea3fb)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b1d43c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_domain_free
```
```
In drivers/base/power/domain.c (ffffffff81b5bcca)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b6025d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff81b7a1f5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81ba51c0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc0536)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6d6c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81bcc593)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff81c4a25e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81c541d1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_rq_free_unused_buf
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/usb/core/devio.c (ffffffff81c99696)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81d5eeb9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81d6de4d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff81d77f8e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81d83470)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d84fff)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de5ba2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff81e07826)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/skbuff.c (ffffffff81e1eac2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81e41463)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/core/dst.c (ffffffff81e450fc)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81e70e2c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e79616)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e7b776)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81e8272a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81ea2dcc)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff81ec551b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/tcp.c (ffffffff81f10646)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81f22d55)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5faf4)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81f6b027)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8618d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98a72)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81fa7f4d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/unix/af_unix.c (ffffffff81faebff)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/route.c (ffffffff81fd6f85)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82004b76)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/dns_resolver/dns_key.c (ffffffff83af63ec)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
```
In net/mptcp/protocol.c (ffffffff820716e9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8209f0a0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/dec_and_lock.c (ffffffff8209fbae)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
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
In init/do_mounts.c (ffffffff838b18d8)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/events/core.c (ffffffff8100be0f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81061f02)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108f2a5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099378)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bd12)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6673)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810fc2d9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
  - kernel/fork.c:__mmput
  - kernel/fork.c:__put_task_struct
```
```
In kernel/cpu.c (ffffffff811006e9)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/exit.c (ffffffff811066ed)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff811251ee)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff811261c1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
```
In kernel/kthread.c (ffffffff81134f82)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/reboot.c (ffffffff811403f0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114ea4f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8118a68c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:destroy_sched_domain
  - kernel/sched/build_utility.c:sched_put_rd
  - kernel/sched/build_utility.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8119c536)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/swap.c (ffffffff811a8a81)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff811b8640)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/rcu/update.c (ffffffff811cb029)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic_cb
```
```
In kernel/rcu/srcutree.c (ffffffff811d0e03)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff811d2df5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In kernel/futex/core.c (ffffffff8121ef39)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/cgroup.c (ffffffff81232990)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/stop_machine.c (ffffffff81253899)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/trace/trace_events.c (ffffffff812c311b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_file_put
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1a5d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_destroy
```
```
In kernel/events/core.c (ffffffff81396f87)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_sched_delayed
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/uprobes.c (ffffffff813aa872)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/jump_label.c (ffffffff813afc99)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In mm/filemap.c (ffffffff813bae94)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/oom_kill.c (ffffffff813c0249)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/readahead.c (ffffffff813c7f98)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813cb266)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff813cdd01)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813dba45)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813eb392)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81404e88)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140de0b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff81415906)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81421ab5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/rmap.c (ffffffff8143b5a7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff81450f56)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:__free_pages
```
```
In mm/memory_hotplug.c (ffffffff81452b3a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/slub.c (ffffffff81454cc8)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/slub.c:free_large_kmalloc
```
```
In mm/madvise.c (ffffffff81461388)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465f9b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81469784)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff814700ab)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8148012f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:add_hugetlb_folio
```
```
In mm/mempolicy.c (ffffffff81487bbb)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In mm/mmu_notifier.c (ffffffff8148959f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff814928ee)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8149adc2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:migrate_folio_undo_src
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8149ef2a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a86a7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_put_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff814b1899)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff814bdc5a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c93cc)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff814cd50a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff814cf914)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814d2ca7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/page_idle.c (ffffffff814d3ad3)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_folio
```
```
In fs/super.c (ffffffff814e4ac3)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff814ec921)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814ef3fd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814f3099)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff8150460e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/dcache.c:copy_name
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff8150f465)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/libfs.c (ffffffff81522c29)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff8152969d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/splice.c (ffffffff8153009a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/remap_range.c (ffffffff8153c415)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/buffer.c (ffffffff81540e4f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/mpage.c (ffffffff81542c8c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/direct-io.c (ffffffff81544936)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/notify/mark.c (ffffffff81548ab5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/userfaultfd.c (ffffffff815580a4)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
```
```
In fs/aio.c (ffffffff8155c639)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/read_metadata.c (ffffffff81572a5d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/verity/verify.c (ffffffff815734a0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff815870f2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8158a4bb)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:ifs_free
```
```
In fs/iomap/direct-io.c (ffffffff8158f30a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff8159b2c1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff815a4271)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In fs/kernfs/dir.c (ffffffff815bb487)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
```
```
In fs/configfs/inode.c (ffffffff815c1741)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff815c507a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff815c5daf)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff815e6e9c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815eacb7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81601cd1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_put_free
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff81608f66)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81612f86)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff81613f76)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/fast_commit.c (ffffffff81646a0e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_update
```
```
In fs/ext4/verity.c (ffffffff8164ab52)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8164c46e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81651072)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/block.c (ffffffff8165d256)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff8165ff35)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8166377e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81668ad4)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e5ce)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8167e913)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8168c243)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff816975d7)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/inode.c (ffffffff8169cabb)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/readdir.c (ffffffff816a1cc6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/common.c (ffffffff81723b14)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff81727048)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bdev.c (ffffffff817a7f02)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/bdev.c:bdev_release
  - block/bdev.c:blkdev_put_whole
```
```
In block/fops.c (ffffffff817a9483)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
  - block/fops.c:blkdev_bio_end_io
```
```
In block/bio.c (ffffffff817ac760)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put
```
```
In block/blk-flush.c (ffffffff817b72ff)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff817b94ca)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff817c492a)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/partitions/amiga.c (ffffffff817d50e6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff817d5e7d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff817d67ef)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff817d80c1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff817da9d2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff817dc54c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff817dcec8)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff817dd25c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff817dd6af)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff817ddaa4)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff817de143)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff817df2c2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff817df5b3)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In io_uring/io_uring.c (ffffffff81811370)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In io_uring/timeout.c (ffffffff8181f219)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
```
In io_uring/io-wq.c (ffffffff8182e90d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_dec_running
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In drivers/pci/p2pdma.c (ffffffff819a8b56)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/pmdomain/core.c (ffffffff81aa37ca)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_power_on
  - drivers/pmdomain/core.c:genpd_power_on
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab254b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81ab52ca)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b12c69)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff81b35589)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81b3d88b)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b739c1)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_domain_free
```
```
In drivers/block/loop.c (ffffffff81bce155)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81bf9440)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14cb6)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b8db)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81c211c3)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97e37)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_release
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb5f28)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_put
```
```
In drivers/net/tun.c (ffffffff81cffbea)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81d078ce)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:free_receive_page_frags
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:virtnet_rq_unmap
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/md/md.c (ffffffff81e16129)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81e2544d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_sb_page
```
```
In drivers/md/dm.c (ffffffff81e2f1be)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81e3ab30)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3c77f)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9bd82)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff81ec4266)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81edc122)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81effdcd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/core/dst.c (ffffffff81f03d7c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81f30503)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81f396b0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81f3ba06)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81f436bd)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/skmsg.c (ffffffff81f650fc)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff81f8890c)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/tcp.c (ffffffff81fd4835)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81fe7be5)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/fib_semantics.c (ffffffff820260c4)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d76d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff82065de2)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff8207520d)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/route.c (ffffffff820a4905)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d3946)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/mptcp/protocol.c (ffffffff82145869)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff821770a0)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/dec_and_lock.c (ffffffff82177b7e)
Location: arch/x86/include/asm/atomic.h:65
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
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
In init/do_mounts.c (ffffffff8288b76f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/core.c (ffffffff810063ce)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105aeae)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065269)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff8109a780)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff8109fcb0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a88df)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810a9ea3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffffffff810b8616)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810ba766)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/nsproxy.c (ffffffff810c6cb5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810c820f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffffffff810cabc2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810d7bd5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (ffffffff810eff8e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff810fc98c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/power/swap.c (ffffffff81105d79)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff8110f9e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/rcu/srcutree.c (ffffffff8111d975)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff8111eda5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/futex.c (ffffffff81142d74)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff811482ed)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff811582e1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115fe82)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116091c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/utsname.c (ffffffff81169c0c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8116a6ee)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffffffff8116b5aa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffffffff8116c464)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/bpf/syscall.c (ffffffff811d6c35)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffffffff811f8cc5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811fbaa0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff812036b7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff8121509f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffffffff812161e0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (ffffffff8121766f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/filemap.c (ffffffff8121c426)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff8122227d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8122698d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81228249)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8122a136)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8122c207)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81232c13)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8123bd1f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffffffff812428ea)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffffffff81251ae1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d545)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff8125e154)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8125f512)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126d0b7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffffffff812734b1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/page_alloc.c (ffffffff81277c3d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (ffffffff8127c90d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127feec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81284960)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff812878ca)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812903a4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff81293575)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffffffff812960e3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81298955)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff812a460e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a8b83)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b2438)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b6e20)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812be49e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c4c0f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812c8ee5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812caaa7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812cbf06)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812cc3d5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812ccab5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:devmap_managed_enable_put
```
```
In fs/open.c (ffffffff812d16d6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffffffff812d3dcc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/file_table.c (ffffffff812d709c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff812d8354)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff812dccff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff812df92f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e23bc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff812f15df)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff812f8865)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/namespace.c (ffffffff812fa04e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffffffff81304867)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff8130806d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/splice.c (ffffffff8131095c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff81315ae2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffffffff8131998d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8131e068)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffffffff8132218e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff81323eb9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/mark.c (ffffffff81325e53)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/userfaultfd.c (ffffffff813308fb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/aio.c (ffffffff813333f9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8133d612)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
```
```
In fs/verity/enable.c (ffffffff81347d0a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff81349913)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81353f52)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81357779)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffffffff81357b4f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffffffff8135a36a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8135d62c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff8135dc84)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff81367951)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/root.c (ffffffff8136ab1f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8136bc54)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff81370f2f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff8137bff7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/kernfs/file.c (ffffffff8137ddac)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/sysfs/mount.c (ffffffff8137ff1c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffffffff81380f91)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8138254a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81384602)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff8139ffb5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813acecf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813b3fb2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813bb4c1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff813c40b5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff813c4e41)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813e085a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813e42ad)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (ffffffff813e7539)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813e8fb3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffffffff813ec3ed)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813f6139)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813f86f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc31b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d09c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d554)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81418bb4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81422c3c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/inode.c (ffffffff814260f8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81429015)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (ffffffff81439cf3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8143c946)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffffffff814423b8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81443c0e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81443f85)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81444bbb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81482a75)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff814853e2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff81497630)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8149ee66)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffffffff814d77f8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-ioc.c (ffffffff814e2a65)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In block/partition-generic.c (ffffffff814f36df)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814f5f7c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f6b16)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f6f4d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814f7ada)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f9562)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814fb192)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814fb895)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814fbab8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814fbdca)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814fc057)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814fc335)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814fd2cd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814fd541)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b0f35)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff8161c797)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816268ed)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8162a17f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166c24e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff81686450)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8168debd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816d3607)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffffffff816daa83)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffffffff816f1365)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/nvdimm/bus.c (ffffffff81706f74)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8171b91f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171f027)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8172240e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8178b31a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/core/devio.c (ffffffff817b3f92)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8183c3df)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff8184a3e2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff8184d0e6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81858729)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff818593b5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81896288)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff818b430d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818b9eaa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffffffff818c5e82)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff818cc396)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff818e0f85)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff818fdb64)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff819023fe)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819074c2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff81909483)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff8193dde5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff8194e4d4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff8195189e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff8196344c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8196efd7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197bd31)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81983cbf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819899e4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff8199e174)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff819a6b04)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff819b3fba)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b6c7d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c3189)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffffffff819c48b0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff819cbb1b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cca34)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff819d375f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff819d73bb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff819dbc76)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819f0e48)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffffffff81a04714)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a15316)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff81a2dc10)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff81a40d7d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In lib/dec_and_lock.c (ffffffff81a4d247)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
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
In init/do_mounts.c (ffffffff828896ec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/core.c (ffffffff81004b4e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104af2e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810555b9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810891c0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff8108e6e0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810972af)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81098853)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffffffff810a6f56)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810a90a0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/nsproxy.c (ffffffff810b54d5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810b6a2f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffffffff810b93d2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810c64f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (ffffffff810dfffe)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff810ecb9c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/power/swap.c (ffffffff810f700e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff81100725)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/rcu/srcutree.c (ffffffff8110ea0f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff811106c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/futex.c (ffffffff811360d4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff8113b59d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff8114b601)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff811530f2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81153b8c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/utsname.c (ffffffff8115ce0c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff8115d8ee)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffffffff8115e7aa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffffffff8115f64d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/bpf/syscall.c (ffffffff811c99f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffffffff811eba15)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811ee7eb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811f67b7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff81207e0f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffffffff81208f40)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (ffffffff8120a3cf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/filemap.c (ffffffff8120f610)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff8121542d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81219afd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8121b389)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8121d256)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8121f2e1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81225cb3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8122ed1f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffffffff812358ba)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffffffff81244b0c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124f995)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812505e4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81251932)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8125f0e7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffffffff81265421)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/page_alloc.c (ffffffff81269b4d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (ffffffff8126e7bd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271c76)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812767d0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff8127972a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81282034)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff81285185)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffffffff81287cf3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff8128a515)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff812960de)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129a543)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a37c4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a7ff0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812af562)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b5c4f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812b9f25)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812bb9ed)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812bcd76)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812bd245)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812bd925)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:devmap_managed_enable_put
```
```
In fs/open.c (ffffffff812c2356)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffffffff812c4a4c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/file_table.c (ffffffff812c7d1c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff812c8fd4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff812cd97f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff812d056f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812d2ffc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff812e220f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff812e9485)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/namespace.c (ffffffff812eac6e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffffffff812f5487)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff812f8c8d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/splice.c (ffffffff8130156c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff813066d2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffffffff8130a54d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8130ec08)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffffffff81312d2e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff81314a59)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/mark.c (ffffffff813169f3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/userfaultfd.c (ffffffff813214eb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/aio.c (ffffffff81324069)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8132e2d2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
```
```
In fs/verity/enable.c (ffffffff813389ea)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff8133a5f3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81344c12)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81348429)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffffffff813487ff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffffffff8134b01a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8134e2cc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff8134e924)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff813585f1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/root.c (ffffffff8135b5af)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8135c6e4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff813619bf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff8136cac7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/kernfs/file.c (ffffffff8136e85c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/sysfs/mount.c (ffffffff813709ac)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffffffff81371a21)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81372fda)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81375092)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff81390a45)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8139d95f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813a4a42)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813abf51)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff813b4b35)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff813b58c1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813d12da)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813d4d2d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (ffffffff813d7fb9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813d9a33)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffffffff813dce6d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813e6bb9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813e9175)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecd9b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813fdb1c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813fdfd4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81409634)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff814136bc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/inode.c (ffffffff81416b78)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81419a95)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (ffffffff8142a763)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8142d3b6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffffffff81432e08)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8143465e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814349d5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8143560b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81473495)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff81475e02)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff81488050)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8148f886)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffffffff814c81b8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-ioc.c (ffffffff814d33f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In block/partition-generic.c (ffffffff814e3bef)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814e648c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e7026)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e745d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814e7fea)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e9a72)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814eb6a2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814ebda5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ebfc8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ec2da)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ec567)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ec845)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814ed7dd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814eda51)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a00c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81610e87)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161af6d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164b4ee)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff816643a9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8166b8ad)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816ae8c7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffffffff816b5103)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffffffff816cb465)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/nvdimm/bus.c (ffffffff816da9f4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816f4d7f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f8457)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff816fb83e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/storvsc_drv.c (ffffffff8171347a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
```
```
In drivers/net/tun.c (ffffffff8176ac6a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d8cc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/usb/core/devio.c (ffffffff817a59c2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81803a3f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff81811a22)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff81814706)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff8181fd39)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff818209c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852045)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:check_ready_for_suspend_event
  - drivers/hv/channel_mgmt.c:check_ready_for_resume_event
```
```
In net/core/sock.c (ffffffff8186e25d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81873dfa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffffffff8187fdc2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81886426)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff8189adc5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff818b7994)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818bc22e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818c12d2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff818c3293)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff818f78e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff81907fc4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff8190b38e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff8191cf3c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81928ac7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819357f1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff8193d77f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819434a4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff81957c34)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff819605c4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff819705ea)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffffffff81973a6d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197ff79)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffffffff819816a0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff8198890b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81989824)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff8199051f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff8199417b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81998a36)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff819adc08)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffffffff819c14d4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d20d6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff819eae00)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff819fd96d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In lib/dec_and_lock.c (ffffffff81a0a377)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
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
In init/do_mounts.c (ffffffff8289e76f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/core.c (ffffffff8100638e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b2de)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065719)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff8109a730)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff8109fc60)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a7e3f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810a9403)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffffffff810b7b76)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810b9cc6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/nsproxy.c (ffffffff810c6205)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810c775f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffffffff810ca0f2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810d43c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (ffffffff810ed0be)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff810f9b4c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/power/swap.c (ffffffff8110401e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff8110d8d5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/rcu/srcutree.c (ffffffff8111b865)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff8111cc95)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/futex.c (ffffffff81140c24)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff8114619d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff811560b1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115dc52)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e6ec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/utsname.c (ffffffff811679dc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811684be)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffffffff8116937a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffffffff8116a234)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/bpf/syscall.c (ffffffff811d4a05)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffffffff811f6a95)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff811f9870)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81201487)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff81212e3f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffffffff81213f80)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (ffffffff8121540f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/filemap.c (ffffffff8121a1c6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff8122001d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8122472d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81225fe9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81227ed6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81229fa7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812309b3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81239abf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffffffff8124068a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffffffff8124f881)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125b2e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff8125bef4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8125d2b2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126ae57)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffffffff81271251)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/page_alloc.c (ffffffff812759dd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (ffffffff8127a6ad)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127dd45)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81282770)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff812856da)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128e1b4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff81291385)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffffffff81293ef3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81296765)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff812a241e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a6993)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b0248)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b4c30)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812bc2ae)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c2a1f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812c6cf5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812c88b7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812c9d16)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812ca1e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812ca8c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:devmap_managed_enable_put
```
```
In fs/open.c (ffffffff812cf4e6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffffffff812d1bdc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/file_table.c (ffffffff812d4eac)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff812d6164)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff812dab0f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff812dd73f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e01cc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff812ef3ef)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff812f6675)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/namespace.c (ffffffff812f7e3e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffffffff81302657)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff81305e5d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/splice.c (ffffffff8130e74c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff813138d2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffffffff8131745d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8131bb38)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffffffff8131fc5e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff81321989)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/mark.c (ffffffff81323923)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8132e3cb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/aio.c (ffffffff81330ec9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8133b0e2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
```
```
In fs/verity/enable.c (ffffffff813457da)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff813473e3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81351a22)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81355249)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffffffff8135561f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffffffff81357e3a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8135b0fc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff8135b754)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff81365421)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/root.c (ffffffff813685ef)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff81369724)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff8136e9ff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff81379ac7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/kernfs/file.c (ffffffff8137b87c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/sysfs/mount.c (ffffffff8137d9ec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffffffff8137ea61)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8138001a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813820d2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff8139d815)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813aa72f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813b1812)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813b8d21)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff813c1545)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff813c22d1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813ddbda)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813e162d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (ffffffff813e48b9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813e6333)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffffffff813e976d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813f34b9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813f5a75)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813f969b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a41c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8140a8d4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81414d54)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8141eddc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/inode.c (ffffffff81422298)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff814251b5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (ffffffff81435e93)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81438ae6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffffffff8143e558)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8143fdae)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81440045)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81440c5b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8147eb15)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff81481482)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff814936d0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8149af06)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffffffff814d3888)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-ioc.c (ffffffff814deaf5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In block/partition-generic.c (ffffffff814ef76f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814f200c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f2ba6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f2fdd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814f3b6a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f55f2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814f7222)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814f7925)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814f7b48)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814f7e5a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814f80e7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814f83c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814f935d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814f95d1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b14c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff8164a737)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816548bd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8165814f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169a62e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff816b4af9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816bc12d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81701b77)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffffffff81708413)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffffffff8171ea45)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/nvdimm/bus.c (ffffffff81745d44)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8175a6ef)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175ddf7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff817611de)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817bb6ba)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c869c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/usb/core/devio.c (ffffffff817f0a32)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff8188ba0f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff81899a12)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff8189c716)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff818a7d59)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a89e5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In net/core/sock.c (ffffffff8190530d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8190aeaa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffffffff81916e82)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff8191d396)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff81931fb5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff8194eb94)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff8195342e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819584f2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8195a4b3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff8198ef75)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199eb10)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_update
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
  - net/netfilter/nf_conntrack_core.c:destroy_conntrack
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a17ee)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2e8f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a456a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
  - net/netfilter/nf_conntrack_proto.c:getorigdst
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a7a17)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_inet_error
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a9263)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:ecache_work_evict_list
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b0f0e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_done_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_done
```
```
In net/ipv4/ip_input.c (ffffffff819b8ca4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff819bc06e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff819cdc1c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819d97a7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e6501)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819ee48f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f41b4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff81a08a14)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81a113a4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81a1e85a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a216fd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2dc09)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f330)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81a3659b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a374b4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff81a3e1df)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff81a41e3b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81a466f6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a5b8c8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffffffff81a6f194)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a7fd96)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff81a997c0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff81aacc2d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In lib/dec_and_lock.c (ffffffff81ab9637)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
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
In init/do_mounts.c (ffffffff8289e774)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/events/core.c (ffffffff810064ee)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c79e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81066cf9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810a23ac)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffff810a7bd0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810aff6f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b162e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffffffff810bfee6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810c137e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/nsproxy.c (ffffffff810ce650)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff810cfc2f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffffffff810d2642)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff810df7d5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (ffffffff810f80fe)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff81104cbc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/power/swap.c (ffffffff8110f40e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff81118ff5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/rcu/srcutree.c (ffffffff81126abc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff81129815)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/futex.c (ffffffff8114de7f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff81152dad)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff811636d1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8116aeb2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116bb1c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/utsname.c (ffffffff811750bc)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81175bae)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffffffff81176a6a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffffffff81177984)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/bpf/syscall.c (ffffffff811e2d35)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffffffff81204d85)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81208324)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81210807)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff81221db6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffffffff812231c0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (ffffffff812243ff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/filemap.c (ffffffff8122929d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffffffff8122f11d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812339fd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff812352e9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81237216)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81239394)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123fe03)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812491af)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffffffff8124fde2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffffffff8125f1f1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8126acaf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff8126b8e4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8126cca2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8127a7d0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffffffff81280cc1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In mm/page_alloc.c (ffffffff8128559d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (ffffffff8128a28d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d8f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81292457)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff81294cfe)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8129df52)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff812a1193)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffffffff812a4133)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff812a654f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff812b277e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b6cc3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812c0588)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c4a6b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff812cca7f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812d34bf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812d7343)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812d9574)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812daa11)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812daee5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812db5f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:devmap_managed_enable_put
```
```
In fs/open.c (ffffffff812e02f6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffffffff812e2a1a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/file_table.c (ffffffff812e5d0c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff812e6d74)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff812eba0f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff812ee6bf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812f1aac)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff81300700)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff813078a5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/namespace.c (ffffffff8130960e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffffffff81313c77)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff8131739d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/splice.c (ffffffff8131ff4c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff81325122)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffffffff8132904d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8132d918)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffffffff8133197e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffff813336e9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/mark.c (ffffffff813355d3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81340ccb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
```
In fs/aio.c (ffffffff813438a9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8134e292)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
```
```
In fs/verity/enable.c (ffffffff81358aba)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff8135a6e3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81364fbd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81368824)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffffffff81368bff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffffffff8136b51a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8136e878)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff8136eea4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff81378b01)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/root.c (ffffffff8137bc3f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8137cf94)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff8138235f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff8138d3fd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/kernfs/file.c (ffffffff8138f51c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/sysfs/mount.c (ffffffff813914ec)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffffffff8139255f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81393b0a)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81395bf7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff813b1d85)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813bf01c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813c6342)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813cda41)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff813d66a5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff813d744d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813f2ffa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813f6a3e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (ffffffff813f9cf6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813fb823)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffffffff813ff071)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff814090c9)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8140b6c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f2f6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81420120)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81420594)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8142b5b2)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81435b3c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/inode.c (ffffffff81439118)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff8143c08c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (ffffffff8144e963)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8144fc56)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffffffff814556c6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81456f5e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814572c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81457f4b)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81496645)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff81499006)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffffffff814ab6c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff814b3275)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffffffff814ec418)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-ioc.c (ffffffff814f7965)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In block/partition-generic.c (ffffffff815087ff)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8150b06c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8150bc06)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8150c03d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8150cbca)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8150e652)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff81510282)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff81510985)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81510ba8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81510eba)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81511147)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81511425)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff815123bd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81512631)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815caf35)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81664cd7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f33d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8167274f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b522e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff816ceda0)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816d6a1d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8171bdb7)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffffffff81722e43)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffffffff81739e75)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/nvdimm/bus.c (ffffffff81761184)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81775caf)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81779457)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8177c83e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817d46f5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e293c)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/usb/core/devio.c (ffffffff8180ac72)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff818aac7f)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffff818b5552)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff818b8956)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff818c3f99)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c4c25)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819069e8)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff819263fd)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8192bfaa)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffffffff81938092)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff8193e8b6)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffffffff81953685)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81970564)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81974f41)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff8197a622)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8197c6d3)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff819b1834)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ip_input.c (ffffffff819c2524)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffffffff819c597e)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffffffff819d77ac)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819e3407)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819f01c1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff819f84ef)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fe374)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffffffff81a13174)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81a1bd14)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffffffff81a29c90)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2ca4d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a393c5)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ac80)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41eda)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42e44)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff81a49c92)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff81a4dacb)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81a52426)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffffffff81a67b82)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffffffff81a7b7c4)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c656)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffffffff81aa45c1)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/dns_resolver/dns_key.c (ffffffff81ab8f9d)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In lib/dec_and_lock.c (ffffffff81ac5a87)
Location: arch/x86/include/asm/atomic.h:123
Inline: True
```
</details>
</li>
</ul>

## Differences
