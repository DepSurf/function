# Function: <code>atomic_dec_return_relaxed</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8134de3b)
Location: include/linux/atomic/atomic-instrumented.h:285
Inline: True
```
```
In mm/rmap.c (ffffffff813d7fd6)
Location: include/linux/atomic/atomic-instrumented.h:285
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
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
In kernel/events/hw_breakpoint.c (ffffffff8137eed1)
Location: include/linux/atomic/atomic-instrumented.h:660
Inline: True
```
```
In mm/rmap.c (ffffffff8140ca78)
Location: include/linux/atomic/atomic-instrumented.h:660
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
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
In kernel/events/hw_breakpoint.c (ffffffff813a8131)
Location: include/linux/atomic/atomic-instrumented.h:660
Inline: True
```
```
In mm/rmap.c (ffffffff814391cc)
Location: include/linux/atomic/atomic-instrumented.h:660
Inline: True
Inline callers:
  - mm/rmap.c:folio_remove_rmap_ptes
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (c000000001344c88)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/powerpc/kernel/rtas.c (c00000000003d868)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_cpu
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_last_cpu
```
```
In arch/powerpc/kernel/iommu.c (c000000000051d78)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_tce_table_put
```
```
In arch/powerpc/mm/pgtable-frag.c (c000000000089378)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_free
```
```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000091148)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:pmd_fragment_free
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000096544)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0ecc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_free
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In arch/powerpc/perf/core-book3s.c (c000000000128990)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In kernel/fork.c (c00000000013b990)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
```
```
In kernel/exit.c (c000000000142cd8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (c00000000014f968)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_compat_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c000000000152034)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (c000000000160e9c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
```
```
In kernel/umh.c (c000000000162578)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (c000000000166f34)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/pid.c (c00000000016dce8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/pid.c:put_pid
```
```
In kernel/kthread.c (c000000000173208)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (c00000000017425c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (c0000000001763e0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:abort_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (c000000000178814)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In kernel/groups.c (c00000000017a8e8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (c00000000018be9c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (c00000000019ae70)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (c0000000001a2488)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c0000000001a7aec)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/topology.c (c0000000001af048)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/autogroup.c (c0000000001b4c0c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (c0000000001bff7c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
```
In kernel/locking/mutex.c (c0000000001c0688)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/rtmutex.c (c0000000001c2f58)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (c0000000001d48ac)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (c0000000001e317c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c0000000001e556c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (c0000000001e9ae4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In kernel/kcmp.c (c0000000001f79d8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (c00000000021130c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (c00000000021dc18)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:put_pi_state
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/cgroup.c (c00000000023aeb4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
```
```
In kernel/cgroup/namespace.c (c00000000024747c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (c0000000002490b8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (c0000000002558c4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c000000000256650)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (c0000000002579e8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (c000000000258fb4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/audit.c (c00000000025d254)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/audit_watch.c (c000000000267be4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In kernel/audit_tree.c (c00000000026bbc0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/hung_task.c (c000000000283430)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/seccomp.c (c000000000285e6c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
```
```
In kernel/relay.c (c0000000002892bc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (c00000000028b928)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/trace.c (c0000000002a4790)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bab70)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In kernel/trace/trace_events.c (c0000000002c5824)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d5074)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In kernel/bpf/syscall.c (c00000000030a288)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
```
In kernel/bpf/btf.c (c00000000032e148)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In kernel/bpf/cpumap.c (c000000000333288)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In kernel/bpf/stackmap.c (c000000000337c58)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (c000000000353218)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/ring_buffer.c (c000000000355008)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (c00000000035bcb8)
Location: arch/powerpc/include/asm/atomic.h:175
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
In kernel/padata.c (c00000000035d6fc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (c00000000035effc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In mm/filemap.c (c000000000367528)
Location: arch/powerpc/include/asm/atomic.h:175
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
In mm/oom_kill.c (c00000000036fa60)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (c000000000375dd8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (c000000000378084)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (c00000000037b550)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (c00000000037e864)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c000000000388514)
Location: arch/powerpc/include/asm/atomic.h:175
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
In mm/shmem.c (c0000000003958cc)
Location: arch/powerpc/include/asm/atomic.h:175
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
In mm/backing-dev.c (c00000000039e838)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_put
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmu_context.c (c00000000039f81c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (c0000000003b76bc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
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
In mm/memory.c (c0000000003c6db4)
Location: arch/powerpc/include/asm/atomic.h:175
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
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (c0000000003c7c6c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (c0000000003c990c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c0000000003da2ec)
Location: arch/powerpc/include/asm/atomic.h:175
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
In mm/process_vm_access.c (c0000000003e317c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In mm/page_alloc.c (c0000000003e95ec)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (c0000000003f28e8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
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
In mm/page_io.c (c0000000003f4fa8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/swap_state.c (c0000000003f7eb0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c0000000003fe91c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (c000000000404058)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_pool_put
```
```
In mm/hugetlb.c (c0000000004109e4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (c000000000414300)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/mmu_notifier.c (c0000000004186a8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (c00000000041c474)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
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
In mm/memory_hotplug.c (c00000000042e2ac)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (c0000000004368c4)
Location: arch/powerpc/include/asm/atomic.h:175
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
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
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
In mm/huge_memory.c (c000000000444260)
Location: arch/powerpc/include/asm/atomic.h:175
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
  - mm/huge_memory.c:mm_put_huge_zero_page
```
```
In mm/khugepaged.c (c00000000044b190)
Location: arch/powerpc/include/asm/atomic.h:175
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
In mm/memcontrol.c (c000000000457028)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (c000000000461ddc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:kill_procs
```
```
In mm/zsmalloc.c (c0000000004686f8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (c00000000046aed4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c00000000046c940)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046d120)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (c00000000046dc54)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:devmap_managed_enable_put
```
```
In fs/open.c (c000000000473f24)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (c0000000004772d8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/file_table.c (c00000000047b130)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (c00000000047cab4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (c000000000483b44)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (c000000000487970)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (c00000000048c83c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (c0000000004a1bd4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/inode.c (c0000000004a8694)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (c0000000004adad4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In fs/namespace.c (c0000000004b0084)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (c0000000004bf1b4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (c0000000004c5298)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In fs/splice.c (c0000000004d17b8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (c0000000004d80f4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (c0000000004de978)
Location: arch/powerpc/include/asm/atomic.h:175
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
In fs/block_dev.c (c0000000004e4fc8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (c0000000004eb320)
Location: arch/powerpc/include/asm/atomic.h:175
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
In fs/mpage.c (c0000000004ed3fc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/proc_namespace.c (c0000000004ee26c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (c0000000004efa08)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (c0000000004f0454)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventfd.c (c0000000004fdd24)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_put
```
```
In fs/userfaultfd.c (c0000000004fea7c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
```
```
In fs/aio.c (c000000000507534)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (c00000000050fd68)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
```
In fs/crypto/keyring.c (c00000000051b2c8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (c00000000051bc70)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/verity/enable.c (c00000000051ec70)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (c0000000005211ec)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (c00000000052fcd8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c0000000005338f8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (c00000000053436c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/posix_acl.c (c0000000005371b4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/coredump.c (c00000000053863c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (c00000000053ce6c)
Location: arch/powerpc/include/asm/atomic.h:175
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
In fs/iomap/direct-io.c (c00000000053d9e4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (c00000000054bac4)
Location: arch/powerpc/include/asm/atomic.h:175
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
In fs/proc/inode.c (c00000000054eee4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/root.c (c0000000005506b0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (c0000000005541ac)
Location: arch/powerpc/include/asm/atomic.h:175
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
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/generic.c (c000000000559658)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In fs/proc/array.c (c00000000055a4cc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (c00000000055cc38)
Location: arch/powerpc/include/asm/atomic.h:175
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
In fs/proc/namespaces.c (c00000000055f624)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (c000000000564a00)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (c00000000056aa9c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In fs/kernfs/file.c (c00000000056e634)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In fs/sysfs/mount.c (c000000000571fb8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (c000000000573964)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c000000000576118)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c0000000005794a8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/configfs/item.c (c000000000579c98)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_put
```
```
In fs/ext4/ialloc.c (c00000000059696c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (c00000000059e600)
Location: arch/powerpc/include/asm/atomic.h:175
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
In fs/ext4/inode.c (c0000000005afda4)
Location: arch/powerpc/include/asm/atomic.h:175
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
In fs/ext4/mballoc.c (c0000000005ba81c)
Location: arch/powerpc/include/asm/atomic.h:175
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
In fs/ext4/move_extent.c (c0000000005c4f88)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (c0000000005d0c60)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (c0000000005d1efc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (c0000000005f7884)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In fs/ext4/xattr.c (c0000000005fc4cc)
Location: arch/powerpc/include/asm/atomic.h:175
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
In fs/ext4/acl.c (c0000000006004d0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
```
```
In fs/ext4/verity.c (c000000000600928)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (c000000000603380)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (c0000000006081ac)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (c000000000616e6c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c000000000619e28)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (c00000000061d63c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (c000000000637140)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (c000000000637670)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c0000000006476fc)
Location: arch/powerpc/include/asm/atomic.h:175
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
In fs/fuse/file.c (c000000000655298)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (c000000000659928)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In fs/fuse/readdir.c (c00000000065ded4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In fs/debugfs/inode.c (c00000000065edd8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In fs/debugfs/file.c (c0000000006600ac)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In ipc/util.c (c000000000666aa8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (c00000000066fc70)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (c000000000677838)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c000000000678db4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (c00000000067a4fc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In security/keys/keyring.c (c00000000067ddf0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In security/keys/keyctl.c (c000000000681a04)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (c00000000068388c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c0000000006843b8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c000000000684e9c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In security/selinux/netlabel.c (c0000000006d1168)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (c0000000006d886c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/tomoyo/common.c (c0000000006e9634)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (c0000000006edbe8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/apparmorfs.c (c0000000006fc584)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:put_multi_transaction
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/capability.c (c00000000070107c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (c0000000007019d4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lib.c (c000000000703904)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (c000000000703a04)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/domain.c (c00000000070b198)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/policy.c (c00000000070e41c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (c00000000071146c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (c0000000007116d8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c000000000715654)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
```
```
In security/apparmor/resource.c (c000000000718794)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (c00000000071a7e0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (c00000000071b7ac)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (c00000000071de78)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_free_or_put_new
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:free_proxy
```
```
In security/apparmor/mount.c (c00000000072344c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (c000000000724188)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (c000000000726f68)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In security/yama/yama_lsm.c (c0000000007281dc)
Location: arch/powerpc/include/asm/atomic.h:175
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
In crypto/api.c (c00000000073c770)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_destroy
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (c0000000007413b4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (c00000000074f018)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/bio.c (c00000000076c6bc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-core.c (c000000000774e78)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In block/blk-flush.c (c00000000077b808)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (c00000000077d5a8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In block/blk-mq.c (c00000000078336c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/partition-generic.c (c0000000007967a8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (c0000000007996cc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c00000000079a644)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c00000000079acc8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c00000000079bc90)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c00000000079e914)
Location: arch/powerpc/include/asm/atomic.h:175
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
In block/partitions/msdos.c (c0000000007a0730)
Location: arch/powerpc/include/asm/atomic.h:175
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
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (c0000000007a0edc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c0000000007a12f4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c0000000007a1744)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c0000000007a1abc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c0000000007a1e74)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c0000000007a3350)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c0000000007a370c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/bsg.c (c0000000007a5f70)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/bsg-lib.c (c0000000007a6f98)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_put
```
```
In block/blk-cgroup.c (c0000000007ab964)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-wbt.c (c0000000007c0ed8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/refcount.c (c0000000007ddd90)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In lib/cpu_rmap.c (c00000000081682c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_put
```
```
In lib/sbitmap.c (c00000000081eb0c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/core.c (c000000000824918)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_put
```
```
In drivers/pci/pci.c (c000000000860fa0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a4b54)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In drivers/dma/dmaengine.c (c0000000008c9188)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d67f8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/reset/core.c (c0000000008ea9f8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_put_internal
```
```
In drivers/tty/tty_io.c (c0000000008efaa0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_driver_kref_put
  - drivers/tty/tty_io.c:tty_kref_put
```
```
In drivers/tty/tty_port.c (c0000000008fd948)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/tty/tty_ldsem.c (c000000000ee956c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/serial/serial_core.c (c000000000924538)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
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
In drivers/char/virtio_console.c (c00000000094e004)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (c000000000950cf0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
```
```
In drivers/char/agp/generic.c (c000000000955cf4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In drivers/connector/cn_queue.c (c000000000970a98)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In drivers/lightnvm/core.c (c000000000975d18)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
```
```
In drivers/base/core.c (c000000000977a3c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/power/runtime.c (c00000000099aba0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (c0000000009a498c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/base/firmware_loader/main.c (c0000000009ac4cc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/block/loop.c (c0000000009c6558)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/mfd/mfd-core.c (c0000000009e88d4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_disable
```
```
In drivers/nvdimm/core.c (c0000000009fc460)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/bus.c (c0000000009fffc0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a02680)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (c000000000a1a4d8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_put
```
```
In drivers/dma-buf/dma-buf.c (c000000000a1d4c4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (c000000000a1f7e8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a1fe74)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (c000000000a21278)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (c000000000a224e4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (c000000000a24208)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sync_timeline_put
```
```
In drivers/dma-buf/udmabuf.c (c000000000a253e8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (c000000000a29f44)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (c000000000a3323c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/scsi_scan.c (c000000000a36e8c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
```
```
In drivers/scsi/sd.c (c000000000a46d60)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sr.c (c000000000a4d46c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (c000000000a510d0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io_usercontext
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (c000000000a5a2d0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_put
```
```
In drivers/net/tun.c (c000000000aa36a0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa6550)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/vfio/vfio.c (c000000000aae274)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_container_put
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (c000000000ab2cd0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_clear
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_release
```
```
In drivers/vfio/pci/vfio_pci_nvlink2.c (c000000000abe1bc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_release
```
```
In drivers/usb/core/hub.c (c000000000ad312c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (c000000000ad514c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (c000000000ada194)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_free_urb
```
```
In drivers/usb/core/message.c (c000000000add218)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (c000000000ae4784)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (c000000000ae5650)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/usb/core/devio.c (c000000000aeb5c8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/media/cec/cec-notifier.c (c000000000ba5f34)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
```
```
In drivers/power/supply/power_supply_core.c (c000000000badbd0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/md.c (c000000000bd7364)
Location: arch/powerpc/include/asm/atomic.h:175
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
In drivers/md/md-bitmap.c (c000000000be6ea8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (c000000000beac28)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-table.c (c000000000bf0f60)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/md/dm-io.c (c000000000bfbe38)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (c000000000bfcb78)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/edac/edac_pci_sysfs.c (c000000000c08c34)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In drivers/opp/core.c (c000000000c0a728)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5dd2c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
```
In drivers/remoteproc/remoteproc_virtio.c (c000000000c60230)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
```
In drivers/devfreq/devfreq.c (c000000000c63ae8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In drivers/nvmem/core.c (c000000000c723c4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:nvmem_unregister
```
```
In net/core/sock.c (c000000000c833e4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_efree
  - net/core/sock.c:sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/request_sock.c (c000000000c85e80)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (c000000000c8a0bc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/datagram.c (c000000000c948f4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/core/net_namespace.c (c000000000c9a098)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:net_drop_ns
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (c000000000c9d388)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/dev.c (c000000000ca50c8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (c000000000cc15f8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (c000000000cc9888)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_rcu_free_parms
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (c000000000cd5f58)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (c000000000ce2d94)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:sk_filter_release
```
```
In net/core/xdp.c (c000000000cf1484)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (c000000000cf83b4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c000000000cf9d08)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/core/netpoll.c (c000000000cfd1ac)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (c000000000d01164)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/sock_map.c (c000000000d13158)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (c000000000d229c8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_group_item_put
```
```
In net/core/bpf_sk_storage.c (c000000000d2aa08)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (c000000000d3115c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (c000000000d3dfd8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_put
```
```
In net/sched/act_api.c (c000000000d4624c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (c000000000d4be60)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_detachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/netfilter/nf_queue.c (c000000000d56200)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (c000000000d5959c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (c000000000d6024c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/ip_input.c (c000000000d615a4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c000000000d62bc0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_output.c (c000000000d6569c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (c000000000d6a3d0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e718)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d71248)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72f18)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c000000000d7dc3c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c000000000d8534c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (c000000000d8cd80)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_pace_kick
```
```
In net/ipv4/tcp_timer.c (c000000000d95b44)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9da28)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9ea20)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (c000000000da4184)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/raw.c (c000000000da9f4c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1590)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/arp.c (c000000000db6b60)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (c000000000dbc4ec)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (c000000000dc59cc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
```
```
In net/ipv4/fib_semantics.c (c000000000dce3b8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/inet_fragment.c (c000000000dd8d58)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (c000000000ddd334)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (c000000000de2864)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv4/fib_rules.c (c000000000de5898)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (c000000000dedcac)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/syncookies.c (c000000000df0a74)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (c000000000df3304)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (c000000000df52ac)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (c000000000df6ec4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (c000000000e03a44)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (c000000000e07978)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (c000000000e0ef28)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e10554)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (c000000000e16ba4)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/af_inet6.c (c000000000e1bddc)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/anycast.c (c000000000e1dc40)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/ip6_output.c (c000000000e2045c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (c000000000e259d0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (c000000000e32808)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/ipv6/route.c (c000000000e3c768)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (c000000000e4a580)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4bf28)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (c000000000e4f6e0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (c000000000e54f10)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (c000000000e5b32c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (c000000000e6345c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
```
```
In net/ipv6/reassembly.c (c000000000e67ad0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cac0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e73054)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (c000000000e797e8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7d86c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e444)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (c000000000e83208)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (c000000000e85dec)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_cache_entry_free
```
```
In net/packet/af_packet.c (c000000000e97e50)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/rfkill/core.c (c000000000ea90e8)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In net/dns_resolver/dns_key.c (c000000000eb210c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/xdp/xsk.c (c000000000ebf46c)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (c000000000ec10a0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/dec_and_lock.c (c000000000ec3a98)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (c000000000ecadb0)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (c000000000ecb864)
Location: arch/powerpc/include/asm/atomic.h:175
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
</details>
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
