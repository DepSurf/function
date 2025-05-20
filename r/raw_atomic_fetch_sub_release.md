# Function: <code>raw_atomic_fetch_sub_release</code>

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
In arch/x86/kernel/ioport.c (ffffffff81051ca4)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107cf5e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088bc9)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091d73)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109422e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096f0b)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810f4acf)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:__vm_area_free
```
```
In kernel/exit.c (ffffffff810fc8a8)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff81107add)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff811177d0)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff811260ac)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff8112a9c2)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff811317c5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff81133945)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (ffffffff81136aff)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/ucount.c (ffffffff811374b7)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff8115009c)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff811620dd)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8116f61d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8118cff5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_exit
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_free
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118e89e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff821569a6)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811ab4d3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
In kernel/rcu/update.c (ffffffff811bd3c1)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff811c3143)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811e4d5e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd35f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running
```
```
In kernel/time/namespace.c (ffffffff812075b2)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/futex/core.c (ffffffff81208868)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/futex/core.c:wait_for_owner_exiting
```
```
In kernel/futex/pi.c (ffffffff8120a834)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff81224c62)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
```
```
In kernel/cgroup/namespace.c (ffffffff812277cf)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812294da)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff8123608e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81237ab0)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81238866)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/audit.c (ffffffff8123ab32)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8124151a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff81248595)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In kernel/audit_tree.c (ffffffff8124c042)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/hung_task.c (ffffffff8125e0f5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff81260c4c)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff812643e2)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffff8126613c)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace.c (ffffffff8127c000)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129260c)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff81296ea5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_release
  - kernel/trace/trace_osnoise.c:stop_kthread
```
```
In kernel/trace/trace_events_user.c (ffffffff812c7268)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
  - kernel/trace/trace_events_user.c:delayed_destroy_user_event
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8c30)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
```
In kernel/trace/rethook.c (ffffffff812ded20)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/trace/rethook.c:free_rethook_node_rcu
  - kernel/trace/rethook.c:rethook_free_rcu
```
```
In kernel/bpf/syscall.c (ffffffff812ed331)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/helpers.c (ffffffff81320d10)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_obj_drop_impl
```
```
In kernel/bpf/task_iter.c (ffffffff8132532d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_get_next
  - kernel/bpf/task_iter.c:task_group_seq_get_next
  - kernel/bpf/task_iter.c:task_group_seq_get_next
```
```
In kernel/bpf/trampoline.c (ffffffff81337209)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8134323d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In kernel/bpf/dispatcher.c (ffffffff8134c7f1)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/net_namespace.c (ffffffff81353e9e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In kernel/bpf/cpumask.c (ffffffff8135d645)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_release
```
```
In kernel/events/core.c (ffffffff8137b511)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:_free_event
```
```
In kernel/events/ring_buffer.c (ffffffff8137cb75)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff813800d5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In kernel/padata.c (ffffffff81385158)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
```
In kernel/watch_queue.c (ffffffff81389b07)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/oom_kill.c (ffffffff81396948)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/backing-dev.c (ffffffff813cb177)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/process_vm_access.c (ffffffff81418948)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In mm/madvise.c (ffffffff814296b5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/page_io.c (ffffffff8142a2cb)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_bdev_sync
```
```
In mm/zswap.c (ffffffff81436e2c)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff814406d2)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:__unmap_hugepage_range_final
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:clear_vma_resv_huge_pages
```
```
In mm/mempolicy.c (ffffffff8144abb9)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff814671b0)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-tiers.c (ffffffff8146d241)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/memory-tiers.c:clear_node_memory_type
  - mm/memory-tiers.c:destroy_memory_type
```
```
In mm/huge_memory.c (ffffffff8147859c)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memcontrol.c (ffffffff81487e21)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In mm/memory-failure.c (ffffffff81494809)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/super.c (ffffffff814b2350)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In fs/exec.c (ffffffff814b87b7)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namei.c (ffffffff814bf830)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In fs/inode.c (ffffffff814d77c6)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/namespace.c (ffffffff814df6fd)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff81503f1d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/mnt_idmapping.c (ffffffff81506ba1)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In fs/proc_namespace.c (ffffffff8150f72e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff81513c05)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffffffff81514552)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventpoll.c (ffffffff8151d445)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In fs/eventfd.c (ffffffff81523669)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffff815242b5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In fs/aio.c (ffffffff8152c04b)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
In fs/crypto/keyring.c (ffffffff81535bf5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In fs/posix_acl.c (ffffffff8154ef0a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
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
In fs/proc/task_mmu.c (ffffffff81564d2e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/root.c (ffffffff8156a168)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8156d501)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_task_lookup
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
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/base.c:timens_offsets_show
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/generic.c (ffffffff81572285)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In fs/proc/fd.c (ffffffff81574f38)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff81578334)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff8157c60d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/sysfs/mount.c (ffffffff81587734)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff8158d865)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff815a766c)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/page-io.c (ffffffff815da735)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
```
```
In fs/ext4/acl.c (ffffffff81611a85)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In fs/hugetlbfs/inode.c (ffffffff8162dd3d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/fuse/dev.c (ffffffff81651d7b)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_put_request
```
```
In fs/fuse/file.c (ffffffff8165f878)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (ffffffff81662cc5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In fs/fuse/dax.c (ffffffff81669de2)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_end
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In fs/debugfs/inode.c (ffffffff8166bc4e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff8166dc1f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In ipc/util.c (ffffffff81675345)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffff8167d6a4)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (ffffffff816851f0)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff816857a7)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In security/keys/key.c (ffffffff816869ea)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In security/keys/keyring.c (ffffffff81689ebf)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/selinux/netlabel.c (ffffffff816d15a2)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
In security/smack/smack_lsm.c (ffffffff816d3e9a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/apparmor/apparmorfs.c (ffffffff816f80ae)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:listener_release
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/audit.c (ffffffff816fab6e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
  - security/apparmor/audit.c:aa_audit_rule_free
```
```
In security/apparmor/capability.c (ffffffff816facd8)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff816fba43)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
In security/apparmor/lib.c (ffffffff816fd7d3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/domain.c (ffffffff81704fbf)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/policy.c (ffffffff817086e3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
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
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8170c09d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8170c42a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff836f8be4)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid_obj
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_task_prctl
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff817149c9)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81716fda)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffff836f9065)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff8171aa13)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8171f293)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffff81720038)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff817230cb)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81723799)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_v3_unotif
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:knotif_update_from_uresp_perm
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:aa_free_listener_proxy
  - security/apparmor/notify.c:__listener_del_knotif
  - security/apparmor/notify.c:__listener_del_knotif
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/yama/yama_lsm.c (ffffffff81726701)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
In security/landlock/ruleset.c (ffffffff8172a7b6)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
  - security/landlock/ruleset.c:free_ruleset
```
```
In crypto/api.c (ffffffff8173e2d4)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff8173fea1)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff8174beb0)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In block/blk-core.c (ffffffff81770b55)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - block/blk-core.c:blk_put_queue
```
```
In block/bsg-lib.c (ffffffff8179eaa5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffff817a24a5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff817ccb6f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_put_task_remote
```
```
In io_uring/net.c (ffffffff817d8b3a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
```
```
In io_uring/sqpoll.c (ffffffff817dbb45)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In io_uring/notif.c (ffffffff817e6173)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - io_uring/notif.c:io_tx_ubuf_callback_ext
```
```
In io_uring/io-wq.c (ffffffff817e8bcf)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_worker_release
```
```
In rust/helpers.c (ffffffff81805ae5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_put_task_struct
  - rust/helpers.c:rust_helper_refcount_dec_and_test
```
```
In lib/refcount.c (ffffffff8181ac5a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff818d39b3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In drivers/pinctrl/core.c (ffffffff818edc5e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195b8ac)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197b285)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff819ad92e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff81a46fc5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff81a4dcd8)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a750a2)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/reset/core.c (ffffffff81a90d3d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
```
```
In drivers/tty/tty_io.c (ffffffff81a97417)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
```
In drivers/tty/tty_port.c (ffffffff81aa0292)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff82158976)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/char/virtio_console.c (ffffffff81ae464d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7502)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
```
```
In drivers/connector/cn_queue.c (ffffffff81b2ab85)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In drivers/base/core.c (ffffffff81b302e3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5f6db)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81ba23c3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6d4f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffff81bba3ed)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/dax/bus.c:__free_dev_dax_id
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbdb3e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc03d4)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0900)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc239f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_set_deadline
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff81bc45f6)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5f16)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/scsi/hosts.c (ffffffff81bcabb0)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd85d8)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc355)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
```
In drivers/scsi/sg.c (ffffffff81bf407a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
In drivers/ata/libata-core.c (ffffffff81bfb491)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/net/pse-pd/pse_core.c (ffffffff81c4265f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/net/pse-pd/pse_core.c:pse_control_put
```
```
In drivers/net/tun.c (ffffffff81c46db1)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/virtio_net.c (ffffffff81c50fff)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61e41)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/usb/core/hub.c (ffffffff81c8256e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81c84c22)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c89121)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81c8b2c0)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff81c91e85)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c92bf2)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/md/dm.c (ffffffff81d795d0)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_put_table_device
```
```
In drivers/md/dm-table.c (ffffffff81d7bb99)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/edac/ghes_edac.c (ffffffff83af5a46)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
```
```
In drivers/nvmem/core.c (ffffffff81df9c45)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
```
In net/core/sock.c (ffffffff81e0acba)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_efree
  - net/core/sock.c:sock_efree
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_free_unlock_clone
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/request_sock.c (ffffffff81e0fb1a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81e1370c)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81e2094c)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/net_namespace.c (ffffffff81e25182)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81e2ee52)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/dst.c (ffffffff81e44c06)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81e4b37f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_rcu_free_parms
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81e5a111)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81e6d7d3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/flow_offload.c (ffffffff81e7a7a3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
```
```
In net/core/gro.c (ffffffff81e7b62b)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/page_pool.c (ffffffff81e833f4)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e85b0a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffff81e893ee)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/core/skmsg.c (ffffffff81ea115f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81ea61b9)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea8914)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81ead022)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffff81eb8515)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ebdc73)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec6cba)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_detachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/bpf/test_run.c (ffffffff81ecedf5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_release
```
```
In net/ipv4/route.c (ffffffff81eecd26)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffff81ef2eb3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81ef42a8)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5b35)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_output.c (ffffffff81ef8d68)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efce57)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f02568)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04765)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06ca5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81f0b14b)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81f19179)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81f25070)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29821)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2da5e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:nf_conntrack_put
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32e38)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f38338)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81f39f26)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81f3bb47)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3fdde)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_next
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/udp_offload.c (ffffffff81f467bc)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff81f4a4ba)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81f4fac5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81f5ac62)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f60253)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a964)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (ffffffff81f6b597)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff81f76c35)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv4/fib_rules.c (ffffffff81f7ab90)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffff81f82617)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/syncookies.c (ffffffff81f85064)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87678)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f883ca)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f886d8)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f8b2d1)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f97539)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a9b8)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa2159)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3f8e)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff81faa924)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_stop
  - net/unix/af_unix.c:bpf_iter_unix_seq_next
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/unix/unix_bpf.c (ffffffff81fb0c7d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81fb26dc)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/anycast.c (ffffffff81fb3993)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/ip6_output.c (ffffffff81fb59cd)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb055)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81fc806a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_add_linklocal
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
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81fd0bff)
Location: include/linux/atomic/atomic-arch-fallback.h:932
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
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv6/ip6_fib.c (ffffffff81fde4a9)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe0a47)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81fe40aa)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81fe9e8d)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81feea3f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81ff86df)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/reassembly.c (ffffffff81ff9c28)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffeacf)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff8200ee74)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff82011b96)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff82011f33)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffff82016851)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff820178cd)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_cache_entry_free
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019e99)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff8201be9b)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024782)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff82028aef)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/devlink/leftover.c (ffffffff820331ba)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_rate_nodes_destroy
  - net/devlink/leftover.c:devl_rate_leaf_destroy
  - net/devlink/leftover.c:devlink_nl_cmd_rate_del_doit
  - net/devlink/leftover.c:devlink_nl_rate_parent_node_set
  - net/devlink/leftover.c:devlink_nl_rate_parent_node_set
```
```
In net/devlink/core.c (ffffffff820422c5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In net/devlink/dev.c (ffffffff82044c72)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
```
In net/xdp/xsk.c (ffffffff8206a84a)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff8206c86f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206ecf3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff820781e0)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff82079dc5)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcp_subflow_drop_ctx
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_req_destructor
```
```
In net/mptcp/token.c (ffffffff8207fbd3)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff82086d40)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b9b7)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/af_mctp.c (ffffffff8208d52f)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/device.c (ffffffff8208e7db)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In net/mctp/route.c (ffffffff8208f725)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
```
```
In net/handshake/request.c (ffffffff8209384b)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
```
```
In lib/klist.c (ffffffff820a1be9)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffff820a2c47)
Location: include/linux/atomic/atomic-arch-fallback.h:932
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In arch/x86/kernel/ioport.c (ffffffff81058ec4)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8108443e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108ec0e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81099153)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109b70e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e47b)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810fde6f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:__vm_area_free
```
```
In kernel/exit.c (ffffffff81105fa8)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff8111147d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff811211c0)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff811306ac)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff8113519c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop_put
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff8113c5b7)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:exit_task_namespaces
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff8113e87b)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/ucount.c (ffffffff81142697)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/groups.c (ffffffff81143b4d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff8115bf6c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff8116ebad)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8117c401)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_contending
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8119b9a5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_exit
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_free
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119d24e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff822397e6)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811b825e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffff811cda06)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_holdout_task
```
```
In kernel/rcu/tree.c (ffffffff811d3383)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811faaae)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121355f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running
```
```
In kernel/time/namespace.c (ffffffff8121e7c2)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
  - kernel/time/namespace.c:free_time_ns
```
```
In kernel/futex/core.c (ffffffff8121f6f8)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/futex/core.c:wait_for_owner_exiting
```
```
In kernel/futex/pi.c (ffffffff81221d94)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/futex/waitwake.c (ffffffff812238e1)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_mark
```
```
In kernel/uid16.c (ffffffff8122775a)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/uid16.c:__do_sys_setgroups16
  - kernel/uid16.c:__do_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff8123c958)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
```
```
In kernel/cgroup/namespace.c (ffffffff8123f5df)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8124132a)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff8124fd0e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81251303)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81252536)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/audit.c (ffffffff81254822)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8125b34e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff812624b5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81265f42)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/hung_task.c (ffffffff81278035)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff8127ae1c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff8127e1d2)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffff8128002c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace.c (ffffffff81296cf0)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812adc4c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b24f5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_release
  - kernel/trace/trace_osnoise.c:stop_kthread
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3c28)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
  - kernel/trace/trace_events_user.c:delayed_destroy_user_event
```
```
In kernel/trace/bpf_trace.c (ffffffff812ea606)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_dealloc
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
```
In kernel/bpf/syscall.c (ffffffff8130be21)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/helpers.c (ffffffff813434b6)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_obj_drop_impl
```
```
In kernel/bpf/task_iter.c (ffffffff81349a1c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_destroy
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In kernel/bpf/trampoline.c (ffffffff8135d089)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8136916d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In kernel/bpf/dispatcher.c (ffffffff81373d11)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/net_namespace.c (ffffffff8137b3bd)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In kernel/bpf/cpumask.c (ffffffff813863a5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_release
```
```
In kernel/events/core.c (ffffffff813a4711)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:_free_event
```
```
In kernel/events/ring_buffer.c (ffffffff813a5dd5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff813a9485)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In kernel/padata.c (ffffffff813ae4c8)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
```
In kernel/watch_queue.c (ffffffff813b3557)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/oom_kill.c (ffffffff813c0258)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/shrinker.c (ffffffff813e3e5a)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_free
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/backing-dev.c (ffffffff813f5982)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/process_vm_access.c (ffffffff8144549a)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In mm/madvise.c (ffffffff81462ee5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/page_io.c (ffffffff81463691)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_bdev_sync
```
```
In mm/zswap.c (ffffffff8147097d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:shrink_memcg
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8147a7cb)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:__hugetlb_zap_end
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:clear_vma_resv_huge_pages
```
```
In mm/mempolicy.c (ffffffff814845f8)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff814963f0)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-tiers.c (ffffffff8149c335)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/memory-tiers.c:clear_node_memory_type
```
```
In mm/huge_memory.c (ffffffff814a7ccc)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memcontrol.c (ffffffff814b7ff1)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c4119)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/super.c (ffffffff814e3a6e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/super.c:destroy_super_work
```
```
In fs/exec.c (ffffffff814eacc7)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namei.c (ffffffff814f1d20)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In fs/inode.c (ffffffff81509ad6)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/namespace.c (ffffffff8151248d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff81538bdd)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/mnt_idmapping.c (ffffffff8153b9c6)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In fs/proc_namespace.c (ffffffff81543c2e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff815480d5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffffffff81548a22)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventpoll.c (ffffffff81551a25)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In fs/eventfd.c (ffffffff81557d99)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffff81558865)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In fs/aio.c (ffffffff81560f2b)
Location: include/linux/atomic/atomic-arch-fallback.h:941
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
In fs/crypto/keyring.c (ffffffff8156abc5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In fs/backing-file.c (ffffffff81581745)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In fs/posix_acl.c (ffffffff81584d4a)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
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
In fs/proc/task_mmu.c (ffffffff8159b7ed)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/root.c (ffffffff815a27e8)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff815a5e79)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_task_lookup
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
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/base.c:timens_offsets_show
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:lstats_write
  - fs/proc/base.c:lstats_show_proc
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/generic.c (ffffffff815aac35)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In fs/proc/fd.c (ffffffff815ad908)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff815b0a64)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff815b4f1d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:bpf_iter_fini_seq_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/sysfs/mount.c (ffffffff815c02f3)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff815c65a5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff815e049b)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/page-io.c (ffffffff81612ef5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
```
```
In fs/ext4/acl.c (ffffffff8164a835)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In fs/hugetlbfs/inode.c (ffffffff81667231)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/fuse/dev.c (ffffffff8168b38b)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_put_request
```
```
In fs/fuse/file.c (ffffffff816996e7)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (ffffffff8169d1b3)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/fuse/inode.c:delayed_release
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/dax.c (ffffffff816a4122)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_end
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In fs/debugfs/inode.c (ffffffff816a6017)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff816a8372)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In fs/tracefs/event_inode.c (ffffffff816abac7)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_remove_rec
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/tracefs/event_inode.c:eventfs_create_dir
  - fs/tracefs/event_inode.c:eventfs_d_release
```
```
In ipc/util.c (ffffffff816b1705)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffff816b9a74)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (ffffffff816c1610)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff816c1bc7)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In security/keys/key.c (ffffffff816c2efa)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In security/keys/keyring.c (ffffffff816c63bf)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/selinux/netlabel.c (ffffffff8170dbd2)
Location: include/linux/atomic/atomic-arch-fallback.h:941
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
In security/smack/smack_lsm.c (ffffffff81711b74)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/apparmor/apparmorfs.c (ffffffff81734e24)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:listener_release
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/audit.c (ffffffff8173777e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
```
```
In security/apparmor/capability.c (ffffffff817378e8)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff81739132)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
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
In security/apparmor/lib.c (ffffffff8173ad33)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/domain.c (ffffffff8174288b)
Location: include/linux/atomic/atomic-arch-fallback.h:941
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
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
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
In security/apparmor/policy.c (ffffffff81746173)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
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
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81749de0)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8174a173)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8392c107)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:aa_setup_dfa_engine
  - security/apparmor/lsm.c:aa_setup_dfa_engine
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getlsmblob_obj
  - security/apparmor/lsm.c:apparmor_current_getlsmblob_subj
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:do_setattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
```
```
In security/apparmor/resource.c (ffffffff817533dc)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755b3d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffff8392c475)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff817594c3)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8175dcc3)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffff8175ea6e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81761b6c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/af_inet.c (ffffffff817641c9)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:aa_inet_sock_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_msg_perm
  - security/apparmor/af_inet.c:aa_inet_accept_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_connect_perm
  - security/apparmor/af_inet.c:aa_inet_bind_perm
  - security/apparmor/af_inet.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81764a93)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_v3_unotif
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:aa_free_ruleset
  - security/apparmor/notify.c:knotif_update_from_uresp_perm
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:aa_free_listener_proxy
  - security/apparmor/notify.c:__listener_del_knotif
  - security/apparmor/notify.c:__listener_del_knotif
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/yama/yama_lsm.c (ffffffff81767921)
Location: include/linux/atomic/atomic-arch-fallback.h:941
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
In security/safesetid/lsm.c (ffffffff81768251)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
```
```
In security/landlock/ruleset.c (ffffffff8176be5e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
  - security/landlock/ruleset.c:free_ruleset
```
```
In crypto/api.c (ffffffff8177f154)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff81780d21)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff8178dd90)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In block/blk-core.c (ffffffff817b2dc5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - block/blk-core.c:blk_put_queue
```
```
In block/bsg-lib.c (ffffffff817e2585)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffff817e5fe5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff818112d9)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_put_task_remote
```
```
In io_uring/net.c (ffffffff8181ce4a)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
```
```
In io_uring/sqpoll.c (ffffffff8181fec5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In io_uring/notif.c (ffffffff8182a393)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - io_uring/notif.c:io_tx_ubuf_callback_ext
```
```
In io_uring/io-wq.c (ffffffff8182e97f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_worker_release
```
```
In rust/helpers.c (ffffffff81842855)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_put_task_struct
  - rust/helpers.c:rust_helper_refcount_dec_and_test
```
```
In lib/refcount.c (ffffffff8185ffda)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff81925ac2)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In lib/stackdepot.c (ffffffff8192857d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In drivers/pinctrl/core.c (ffffffff8193542e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a4ecc)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c44c5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff819f7dae)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff81a92a65)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff81a99978)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac7232)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/reset/core.c (ffffffff81ae3843)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_put_internal
```
```
In drivers/tty/tty_io.c (ffffffff81ae9e56)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
```
In drivers/tty/tty_port.c (ffffffff81af2ce2)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff8223c1f6)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/char/virtio_console.c (ffffffff81b37a1d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a8d2)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b80df4)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_unbind_device
```
```
In drivers/connector/cn_queue.c (ffffffff81b81e35)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In drivers/base/core.c (ffffffff81b87ae3)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb30eb)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81bf6583)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfafff)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffff81c0e7bd)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/dax/bus.c:__free_dev_dax_id
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c1228e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14b54)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15080)
Location: include/linux/atomic/atomic-arch-fallback.h:941
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
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16b2f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_set_deadline
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c18d76)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1aa20)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/scsi/hosts.c (ffffffff81c1f7e0)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2d2d8)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c31085)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
```
In drivers/scsi/sg.c (ffffffff81c499ba)
Location: include/linux/atomic/atomic-arch-fallback.h:941
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
In drivers/ata/libata-core.c (ffffffff81c50f21)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7a585)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_default_clear
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_default_clear
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7df4f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7eeee)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_master_release
  - drivers/gpu/drm/drm_auth.c:drm_master_release
  - drivers/gpu/drm/drm_auth.c:drm_dropmaster_ioctl
  - drivers/gpu/drm/drm_auth.c:drm_new_set_master
```
```
In drivers/gpu/drm/drm_client.c (ffffffff81c81c48)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client.c:drm_client_buffer_delete
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c82674)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_commit_atomic
```
```
In drivers/gpu/drm/drm_color_mgmt.c (ffffffff81c85085)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87582)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:__drm_connector_put_safe
  - drivers/gpu/drm/drm_connector.c:drm_connector_cleanup
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c32b)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:devm_drm_dev_init_release
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97314)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_send_event_helper
  - drivers/gpu/drm/drm_file.c:drm_event_cancel_free
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9992d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c4c4)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj
  - drivers/gpu/drm/drm_gem.c:drm_gem_vm_close
  - drivers/gpu/drm/drm_gem.c:drm_gem_open_ioctl
  - drivers/gpu/drm/drm_gem.c:drm_gem_flink_ioctl
  - drivers/gpu/drm/drm_gem.c:drm_gem_dma_resv_wait
  - drivers/gpu/drm/drm_gem.c:drm_gem_dumb_map_offset
  - drivers/gpu/drm/drm_gem.c:drm_gem_object_handle_put_unlocked
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca480a)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81caca39)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_mmap
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_fd_to_handle
  - drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_release
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb20a7)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_timeline_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_eventfd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:syncobj_eventfd_entry_fence_func
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_array_free
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_array_find
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_destroy_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_release_handle
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_file_release
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_handle
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_free
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_replace_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fence_add_wait
```
```
In drivers/gpu/drm/drm_writeback.c (ffffffff81cb8980)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_signal_completion
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_cleanup_job
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (ffffffff81cbe374)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_dumb_create
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc35ab)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_page_flip_target
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_page_flip
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_resume
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_suspend
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_duplicate_state
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_disable_all
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_set_config
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_disable_plane
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_update_plane
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_hw_done
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:release_crtc_commit
  - drivers/gpu/drm/drm_atomic_helper.c:commit_tail
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_fences
```
```
In drivers/gpu/drm/drm_atomic_state_helper.c (ffffffff81cc58bd)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_connector_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_crtc_destroy_state
```
```
In drivers/gpu/drm/drm_damage_helper.c (ffffffff81cc8404)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb
```
```
In drivers/gpu/drm/drm_gem_atomic_helper.c (ffffffff81ccb1e6)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
```
```
In drivers/gpu/drm/drm_gem_framebuffer_helper.c (ffffffff81ccc097)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_destroy
```
```
In drivers/gpu/drm/drm_self_refresh_helper.c (ffffffff81ccfb22)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_entry_work
```
```
In drivers/gpu/drm/drm_fb_helper.c (ffffffff81cd3735)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In drivers/net/netkit.c (ffffffff81ce5cb5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
```
```
In drivers/net/pse-pd/pse_core.c (ffffffff81cf7d1f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/net/pse-pd/pse_core.c:pse_control_put
```
```
In drivers/net/tun.c (ffffffff81cfc6d1)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/virtio_net.c (ffffffff81d0703c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18841)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/usb/core/hub.c (ffffffff81d36eae)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81d39622)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81d3db71)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81d3fd40)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff81d46a45)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/md/dm.c (ffffffff81e30780)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_put_table_device
```
```
In drivers/md/dm-table.c (ffffffff81e32b5e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/edac/ghes_edac.c (ffffffff83d51806)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
```
```
In drivers/nvmem/core.c (ffffffff81eb1073)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb747d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_unregister
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_register
  - drivers/dpll/dpll_core.c:dpll_pin_put
  - drivers/dpll/dpll_core.c:dpll_device_put
```
```
In net/core/sock.c (ffffffff81ec76aa)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_efree
  - net/core/sock.c:sock_efree
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_free_unlock_clone
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/request_sock.c (ffffffff81ecc5ca)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81ed073c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81ede81c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/net_namespace.c (ffffffff81ee30e2)
Location: include/linux/atomic/atomic-arch-fallback.h:941
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
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81eedad2)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/dst.c (ffffffff81f03885)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81f0a09f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_rcu_free_parms
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81f194be)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffff81f2d013)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/flow_offload.c (ffffffff81f3a943)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
```
```
In net/core/gro.c (ffffffff81f3b8bb)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/page_pool.c (ffffffff81f44c52)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In net/core/netpoll.c (ffffffff81f47aea)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffff81f4b3fe)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/core/skmsg.c (ffffffff81f6383f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81f68c79)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6b3d4)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81f6fac2)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffff81f7b5e5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In net/sched/act_api.c (ffffffff81f84263)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
```
```
In net/netlink/af_netlink.c (ffffffff81f89f33)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_detachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/bpf/test_run.c (ffffffff81f92695)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_release
```
```
In net/ipv4/route.c (ffffffff81fb0db6)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffff81fb6e43)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81fb8228)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9ae5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_output.c (ffffffff81fbcc88)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc0da7)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc82ba)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8a65)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcafc5)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81fcee1b)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81fdda0f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81fe994c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee39e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff26ee)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:nf_conntrack_put
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8f88)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe3f8)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff82000016)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff82001c67)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff82005a9e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_next
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/udp_offload.c (ffffffff8200c8fc)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff820105ca)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff82015c3d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff820211a2)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff82026823)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff82031014)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (ffffffff82032a87)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff8203d405)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv4/fib_rules.c (ffffffff82041290)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffff82048c96)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/syncookies.c (ffffffff8204b77f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204d154)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_release
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204ecf8)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff8204faea)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8204fd98)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff820529d1)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/ipv4/tcp_ao.c (ffffffff8205633d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_destroy_sock
```
```
In net/xfrm/xfrm_policy.c (ffffffff820648ac)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff82067d18)
Location: include/linux/atomic/atomic-arch-fallback.h:941
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f530)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff820712be)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_state_bpf.c (ffffffff82075f35)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_xfrm_state_release
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_get_xfrm_state
```
```
In net/unix/af_unix.c (ffffffff82077d14)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_stop
  - net/unix/af_unix.c:bpf_iter_unix_seq_next
  - net/unix/af_unix.c:bpf_iter_unix_realloc_batch
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/unix/unix_bpf.c (ffffffff8207e31d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff8207fe6c)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/anycast.c (ffffffff82081238)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/ip6_output.c (ffffffff8208309d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff82088465)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff82095777)
Location: include/linux/atomic/atomic-arch-fallback.h:941
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
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_add_linklocal
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
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff8209e4ef)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv6/ip6_fib.c (ffffffff820ac029)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820add58)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff820b1fb1)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff820b7d0f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff820bc616)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff820c6347)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/reassembly.c (ffffffff820c7898)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd82d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:nf_conntrack_put
```
```
In net/ipv6/ip6mr.c (ffffffff820dde04)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0a2e)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e10a3)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffff820e587d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff820e689d)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_cache_entry_free
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8e69)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff820eae6b)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3a92)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff820f852f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/devlink/core.c (ffffffff820fec95)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/devlink/core.c:__devlink_rel_put
```
```
In net/devlink/dev.c (ffffffff82104532)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
```
```
In net/devlink/rate.c (ffffffff82117fca)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/devlink/rate.c:devl_rate_nodes_destroy
  - net/devlink/rate.c:devl_rate_leaf_destroy
  - net/devlink/rate.c:devlink_nl_rate_del_doit
  - net/devlink/rate.c:devlink_nl_rate_parent_node_set
  - net/devlink/rate.c:devlink_nl_rate_parent_node_set
```
```
In net/xdp/xsk.c (ffffffff8213e47b)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff8214068f)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142dd3)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff8214d397)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_tout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff8214f225)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcp_subflow_drop_ctx
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_req_destructor
```
```
In net/mptcp/token.c (ffffffff821550c3)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c4f0)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mptcp/pm_userspace.c (ffffffff821617b7)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
```
```
In net/mctp/af_mctp.c (ffffffff821639ef)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/device.c (ffffffff82164ccb)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In net/mctp/route.c (ffffffff82165c05)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
```
```
In net/handshake/request.c (ffffffff8216a0fb)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
```
```
In lib/klist.c (ffffffff82179c69)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffff8217acc7)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In lib/objpool.c (ffffffff82191def)
Location: include/linux/atomic/atomic-arch-fallback.h:941
Inline: True
Inline callers:
  - lib/objpool.c:objpool_drop
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
