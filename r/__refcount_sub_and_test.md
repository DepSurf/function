# Function: <code>__refcount_sub_and_test</code>

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
In arch/x86/kernel/ioport.c (ffffffff8103821c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055b43)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ebd9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff810657fc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065eaf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068a80)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810a0934)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/fork.c:wait_for_vfork_done
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
```
```
In kernel/exit.c (ffffffff810a7b69)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810b11c3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810bf442)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810c8448)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff810cb319)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810d0c9d)
Location: include/linux/refcount.h:270
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
In kernel/cred.c (ffffffff810d22f7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (ffffffff810d431e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (ffffffff810e08b9)
Location: include/linux/refcount.h:270
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
In kernel/sched/fair.c (ffffffff810f1691)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f7519)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f977f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/autogroup.c (ffffffff81103746)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff8110b0ab)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c6fe)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff8110d65e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8112150d)
Location: include/linux/refcount.h:270
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
In kernel/rcu/update.c (ffffffff8112c5f3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_del_holdout
```
```
In kernel/kcmp.c (ffffffff8113c21e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/namespace.c (ffffffff81156590)
Location: include/linux/refcount.h:270
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
In kernel/futex.c (ffffffff81158cb4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff81173e9b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
```
```
In kernel/cgroup/namespace.c (ffffffff81175e5f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177646)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff8118057a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81181680)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81181fc6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/audit.c (ffffffff811838a5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff811892a8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff8118e7a5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/audit_tree.c (ffffffff8119163e)
Location: include/linux/refcount.h:270
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
In kernel/kprobes.c (ffffffff81192d04)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kprobes.c:free_rp_inst_rcu
```
```
In kernel/hung_task.c (ffffffff811a147c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff811a3a0c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff811a6392)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffff811a7b94)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_pid
```
```
In kernel/trace/trace.c (ffffffff811b90b0)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c855f)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fb70a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff81218682)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In kernel/bpf/trampoline.c (ffffffff812229b8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/bpf/btf.c (ffffffff812292cd)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/dispatcher.c (ffffffff8122ce7f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/net_namespace.c (ffffffff81232bc2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81238645)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_delete_elem
```
```
In kernel/events/core.c (ffffffff8124d1b7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In kernel/events/ring_buffer.c (ffffffff8124e415)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff81250175)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/watch_queue.c (ffffffff812578e5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/oom_kill.c (ffffffff812617ea)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
```
```
In mm/backing-dev.c (ffffffff81282568)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
```
In mm/process_vm_access.c (ffffffff812b8bdd)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/madvise.c (ffffffff812c19e4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/page_io.c (ffffffff812c345b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff812ce16f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff812d3920)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
```
```
In mm/mempolicy.c (ffffffff812d9cb1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812ed159)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memcontrol.c (ffffffff813033f1)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130c4e0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/super.c (ffffffff81321b58)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/exec.c (ffffffff81326f3f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namei.c (ffffffff8132ce68)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/inode.c (ffffffff81340e63)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/namespace.c (ffffffff81346775)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff81363f13)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc_namespace.c (ffffffff81372f70)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff81374245)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffffffff81374c03)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventfd.c (ffffffff8137f7cb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffff813802f5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/aio.c (ffffffff81385f9e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8138f5fe)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_remove_personalities
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_free_work
  - fs/io_uring.c:io_sq_thread_stop
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_identity_cow
  - fs/io_uring.c:io_identity_cow
  - fs/io_uring.c:io_req_clean_work
```
```
In fs/io-wq.c (ffffffff8139c865)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_destroy
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_worker_exit
  - fs/io-wq.c:io_worker_exit
```
```
In fs/crypto/keyring.c (ffffffff813a3a73)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff813a474d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/posix_acl.c (ffffffff813b7b65)
Location: include/linux/refcount.h:270
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
In fs/proc/task_mmu.c (ffffffff813c8a7d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/root.c (ffffffff813cc37c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff813ce4ba)
Location: include/linux/refcount.h:270
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
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/generic.c (ffffffff813d2e25)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/proc/fd.c (ffffffff813d59ef)
Location: include/linux/refcount.h:270
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
In fs/proc/namespaces.c (ffffffff813d81b4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff813db903)
Location: include/linux/refcount.h:270
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
In fs/sysfs/mount.c (ffffffff813e4324)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff813e9696)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
```
In fs/ext4/ialloc.c (ffffffff813fe444)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_xattr_credits_for_new_inode
```
```
In fs/ext4/acl.c (ffffffff81457d92)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In fs/hugetlbfs/inode.c (ffffffff8146ce86)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/dev.c (ffffffff81488bec)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In fs/fuse/file.c (ffffffff8149510e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (ffffffff81498115)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/fuse/dax.c (ffffffff8149d134)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_upgrade_dax_mapping
```
```
In fs/debugfs/inode.c (ffffffff8149ead4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff8149fb2f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In ipc/util.c (ffffffff814a47d5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffff814abc22)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (ffffffff814b268f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814b2b41)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In security/keys/key.c (ffffffff814b3925)
Location: include/linux/refcount.h:270
Inline: True
```
```
In security/keys/keyring.c (ffffffff814b662f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/selinux/netlabel.c (ffffffff814eebca)
Location: include/linux/refcount.h:270
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
In security/smack/smack_lsm.c (ffffffff814f0543)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/apparmor/apparmorfs.c (ffffffff81509bc7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/audit.c (ffffffff8150db64)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_rule_free
```
```
In security/apparmor/capability.c (ffffffff8150de4f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff8150e793)
Location: include/linux/refcount.h:270
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
In security/apparmor/lib.c (ffffffff8150fc43)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff8150ff2a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff8151679f)
Location: include/linux/refcount.h:270
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
In security/apparmor/policy.c (ffffffff81519609)
Location: include/linux/refcount.h:270
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
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8151c226)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8151c474)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8152105e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
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
In security/apparmor/resource.c (ffffffff815229d3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff815244b7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffff81525084)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff81529a60)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__label_update
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
```
```
In security/apparmor/mount.c (ffffffff8152b76f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffff8152c261)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8152e31d)
Location: include/linux/refcount.h:270
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
In security/yama/yama_lsm.c (ffffffff8152ede9)
Location: include/linux/refcount.h:270
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
In crypto/api.c (ffffffff8153b4ea)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff8153e23f)
Location: include/linux/refcount.h:270
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
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff81545b00)
Location: include/linux/refcount.h:270
Inline: True
```
```
In crypto/rng.c (ffffffff8154fe2d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
```
```
In block/blk-flush.c (ffffffff81563d14)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8156b81e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/bsg.c (ffffffff8158342f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/bsg.c:bsg_put_device
```
```
In block/bsg-lib.c (ffffffff81584245)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffff81586a21)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In lib/refcount.c (ffffffff815ac410)
Location: include/linux/refcount.h:270
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815fce70)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In lib/klist.c (ffffffff8160efe9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffff8160f7b9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In drivers/pinctrl/core.c (ffffffff81627c8e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81675870)
Location: include/linux/refcount.h:270
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
In drivers/acpi/ec.c (ffffffff816ad390)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff8171fa55)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff8172463f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173c8f2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/reset/core.c (ffffffff8174ee72)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_array_put
```
```
In drivers/tty/tty_io.c (ffffffff817544c2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
```
In drivers/tty/tty_port.c (ffffffff8175b872)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/tty/tty_ldsem.c (ffffffff81c44e47)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/char/virtio_console.c (ffffffff8179128f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff81793b52)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
```
In drivers/iommu/ioasid.c (ffffffff817bf92c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_put
```
```
In drivers/connector/cn_queue.c (ffffffff817c1605)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff817c40e5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
```
In drivers/base/core.c (ffffffff817c81d3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/firmware_loader/main.c (ffffffff817e9cac)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff8181d913)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81821f9f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffff81833d81)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81836862)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818380ff)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818384d0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81839428)
Location: include/linux/refcount.h:270
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
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183b859)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183d119)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184afb5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8185ae34)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (ffffffff8185e5a8)
Location: include/linux/refcount.h:270
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
In drivers/ata/libata-core.c (ffffffff81863361)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/net/tun.c (ffffffff81899bdd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a003a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_bridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/vfio/vfio.c (ffffffff818aa2ff)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ade35)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
```
In drivers/usb/core/hub.c (ffffffff818c7f47)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818c8de2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818cbee7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff818cde10)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff818d2e7b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff818d3803)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/md/dm.c (ffffffff8197c0b0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_put_table_device
```
```
In drivers/md/dm-table.c (ffffffff81980a5f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81991382)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_unregister
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca41e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819ccb74)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
```
In drivers/nvmem/core.c (ffffffff819d95b5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
```
In net/core/sock.c (ffffffff819e6558)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_efree
  - net/core/sock.c:sock_efree
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_free_unlock_clone
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/request_sock.c (ffffffff819e95ca)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff819eb78a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff819f4937)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f87e2)
Location: include/linux/refcount.h:270
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
In net/core/dev.c (ffffffff81a056bd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81a10e8b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81a16104)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_rcu_free_parms
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81a21a40)
Location: include/linux/refcount.h:270
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
In net/core/filter.c (ffffffff81a2cfb7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/flow_offload.c (ffffffff81a38f1b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
```
```
In net/core/page_pool.c (ffffffff81a3d122)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/skmsg.c (ffffffff81a3ffde)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff81a40d7a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffff81a43d11)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_cleanup_ops
```
```
In net/core/sock_map.c (ffffffff81a54685)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/devlink.c (ffffffff81a58f95)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_put
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_netns_get
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6a022)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81a6ce76)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffff81a76c35)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_put
```
```
In net/sched/act_api.c (ffffffff81a7b9b1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_delete_index
  - net/sched/act_api.c:tcf_del_walker
```
```
In net/netlink/af_netlink.c (ffffffff81a81b8c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_detachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netfilter/nf_queue.c (ffffffff81a99653)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81a9b6b4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffff81aa13d3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa3435)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa9c18)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad585)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf335)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0b08)
Location: include/linux/refcount.h:270
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
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81ab863d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81abef82)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81acce1e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdc5f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4c5d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad59fd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad924e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ae3c47)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5354)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff81ae6d4f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81aec860)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81af34ba)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afa702)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81b028b7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (ffffffff81b051e5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff81b0ac46)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv4/fib_rules.c (ffffffff81b0d866)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffff81b1204c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/syncookies.c (ffffffff81b15d1c)
Location: include/linux/refcount.h:270
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
In net/ipv4/tcp_bpf.c (ffffffff81b17c82)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b18289)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b1a7d0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b24700)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
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
In net/xfrm/xfrm_state.c (ffffffff81b270cd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
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
In net/unix/af_unix.c (ffffffff81b33bca)
Location: include/linux/refcount.h:270
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
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/af_inet6.c (ffffffff81b394ac)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/anycast.c (ffffffff81b3a2bb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81b4b50d)
Location: include/linux/refcount.h:270
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
  - net/ipv6/addrconf.c:fixup_permanent_addr
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81b53155)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5db6a)
Location: include/linux/refcount.h:270
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
In net/ipv6/ipv6_sockglue.c (ffffffff81b5ff18)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81b62b7d)
Location: include/linux/refcount.h:270
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
In net/ipv6/udp.c (ffffffff81b66ecb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81b6b610)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81b71687)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
```
```
In net/ipv6/reassembly.c (ffffffff81b74c2f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7934f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81b8432c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b87456)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87791)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffff81b8af9d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b8bdd2)
Location: include/linux/refcount.h:270
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
In net/packet/af_packet.c (ffffffff81b9a56f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb6600)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8420)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9c0f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff81bbe4e3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff81bc1597)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:subflow_req_destructor
```
```
In net/mptcp/token.c (ffffffff81bc5ad8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc873f)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/mptcp/syncookies.c (ffffffff81bc9574)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81039d5c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810573c3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f3f9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81065ecc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810671df)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068cc4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810a3d0c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
```
```
In kernel/exit.c (ffffffff810a99aa)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810b24f9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810c0e17)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810c9ef4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff810ccd45)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810d2879)
Location: include/linux/refcount.h:270
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
In kernel/cred.c (ffffffff810d3ee5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (ffffffff810d5f5e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (ffffffff810e26d9)
Location: include/linux/refcount.h:270
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
In kernel/sched/fair.c (ffffffff810f397e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f9a29)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810fb8d6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/autogroup.c (ffffffff81105a42)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff8110ce2b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e52a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff81c36443)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811217ed)
Location: include/linux/refcount.h:270
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
In kernel/rcu/update.c (ffffffff8112ce07)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
```
In kernel/kcmp.c (ffffffff8113d3c7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/namespace.c (ffffffff81157990)
Location: include/linux/refcount.h:270
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
In kernel/futex.c (ffffffff8115a014)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff81174a6b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
```
```
In kernel/cgroup/namespace.c (ffffffff811769df)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811781c3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff811815da)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811827a4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81183116)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/audit.c (ffffffff81184915)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8118a117)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff8118f725)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/audit_tree.c (ffffffff811929b5)
Location: include/linux/refcount.h:270
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
In kernel/kprobes.c (ffffffff81193c66)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kprobes.c:free_rp_inst_rcu
```
```
In kernel/hung_task.c (ffffffff811a20d4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff811a461c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff811a72b2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffff811a8838)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace.c (ffffffff811b9970)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c97ff)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fc42a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff8121bce3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_stop
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In kernel/bpf/trampoline.c (ffffffff81227158)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/bpf/btf.c (ffffffff8122db6d)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/dispatcher.c (ffffffff81231cdf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/net_namespace.c (ffffffff81236d67)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123ce25)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_delete_elem
```
```
In kernel/events/core.c (ffffffff81251a77)
Location: include/linux/refcount.h:270
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
In kernel/events/ring_buffer.c (ffffffff81252d15)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff81254935)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/watch_queue.c (ffffffff8125bd45)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/oom_kill.c (ffffffff81266007)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
```
```
In mm/backing-dev.c (ffffffff81287678)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
```
In mm/process_vm_access.c (ffffffff812be0a9)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/madvise.c (ffffffff812c88e2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/page_io.c (ffffffff812ca29f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff812d4836)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff812da8d7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
```
```
In mm/mempolicy.c (ffffffff812e1529)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812f34f5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff813005c4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memcontrol.c (ffffffff81309911)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/memory-failure.c (ffffffff81312c3b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/super.c (ffffffff81327c28)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/exec.c (ffffffff8132cff5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namei.c (ffffffff81332aa5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/inode.c (ffffffff81347253)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/namespace.c (ffffffff8134f4d4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
```
```
In fs/fs_context.c (ffffffff8136a993)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc_namespace.c (ffffffff813798f9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff8137ab45)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffffffff8137b5c3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventfd.c (ffffffff8138644b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffff81386d75)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/aio.c (ffffffff8138d0ee)
Location: include/linux/refcount.h:270
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
In fs/io_uring.c (ffffffff8139aeee)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_free_work
  - fs/io_uring.c:io_sq_thread_finish
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_complete_post
```
```
In fs/io-wq.c (ffffffff813a3a2b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/io-wq.c:io_wqe_activate_free_worker
Direct callers:
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/crypto/keyring.c (ffffffff813aacaf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff813ab88d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/posix_acl.c (ffffffff813bebfc)
Location: include/linux/refcount.h:270
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
In fs/proc/task_mmu.c (ffffffff813cfabc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/root.c (ffffffff813d3338)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff813d5141)
Location: include/linux/refcount.h:270
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
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/generic.c (ffffffff813d9cb5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/proc/fd.c (ffffffff813dc7ac)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff813df064)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff813e2828)
Location: include/linux/refcount.h:270
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
In fs/sysfs/mount.c (ffffffff813eaf24)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff813f01f6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
```
In fs/ext4/ialloc.c (ffffffff814065fc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff8145d742)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In fs/hugetlbfs/inode.c (ffffffff8147257d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/dev.c (ffffffff8148e4ec)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In fs/fuse/file.c (ffffffff8149a16b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (ffffffff8149d345)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/fuse/dax.c (ffffffff814a3c21)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In fs/debugfs/inode.c (ffffffff814a4ab4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff814a5b2f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In ipc/util.c (ffffffff814aa795)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffff814b1ab4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (ffffffff814b84fb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff814b8731)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff814b9755)
Location: include/linux/refcount.h:270
Inline: True
```
```
In security/keys/keyring.c (ffffffff814bc47f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/selinux/netlabel.c (ffffffff814f592a)
Location: include/linux/refcount.h:270
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
In security/smack/smack_lsm.c (ffffffff814f74c3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/apparmor/apparmorfs.c (ffffffff815105e7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/audit.c (ffffffff81514574)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_rule_free
```
```
In security/apparmor/capability.c (ffffffff81514800)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff81515193)
Location: include/linux/refcount.h:270
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
In security/apparmor/lib.c (ffffffff81516623)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff815167ba)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff8151d0e9)
Location: include/linux/refcount.h:270
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
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
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
In security/apparmor/policy.c (ffffffff8151ff11)
Location: include/linux/refcount.h:270
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
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8152298d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81522c4e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8152731d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
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
In security/apparmor/resource.c (ffffffff81528baf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8152a693)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffff8152b234)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/apparmor/label.c (ffffffff8152d006)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
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
```
```
In security/apparmor/mount.c (ffffffff81531a9a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffff815324fd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8153463c)
Location: include/linux/refcount.h:270
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
In security/yama/yama_lsm.c (ffffffff81535585)
Location: include/linux/refcount.h:270
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
In security/landlock/ruleset.c (ffffffff81538312)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
  - security/landlock/ruleset.c:free_ruleset
```
```
In crypto/api.c (ffffffff81543bda)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff815469fc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff8154e180)
Location: include/linux/refcount.h:270
Inline: True
```
```
In block/blk-flush.c (ffffffff8156c435)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81575a41)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/bsg.c (ffffffff8158a26f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/bsg-lib.c (ffffffff8158afd5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffff8158d731)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In lib/refcount.c (ffffffff815b70e0)
Location: include/linux/refcount.h:270
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815dfbe0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In lib/klist.c (ffffffff815f2769)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffff815f2ef9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In drivers/pinctrl/core.c (ffffffff8160b76e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81657da0)
Location: include/linux/refcount.h:270
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
In drivers/acpi/ec.c (ffffffff8168f9b0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff81700ca5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff817058ff)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81720452)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/reset/core.c (ffffffff81732d5d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
```
```
In drivers/tty/tty_io.c (ffffffff817351ea)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
```
In drivers/tty/tty_port.c (ffffffff8173f712)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/tty/tty_ldsem.c (ffffffff81c380ac)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/char/virtio_console.c (ffffffff8177431f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff81776732)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
```
In drivers/iommu/ioasid.c (ffffffff817a2b4c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_put
```
```
In drivers/connector/cn_queue.c (ffffffff817a4ad5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff817a81aa)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
```
In drivers/base/core.c (ffffffff817ab6e3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ce3dc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81800b83)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818052af)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffff81816f71)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81819a2a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8181b3ec)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b7ad)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c6d4)
Location: include/linux/refcount.h:270
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
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181ea79)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818202df)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182e315)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8183de24)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (ffffffff818415c8)
Location: include/linux/refcount.h:270
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
In drivers/ata/libata-core.c (ffffffff81845ef1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/net/tun.c (ffffffff8187c38d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882b4a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/vfio/vfio.c (ffffffff8188d50f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
  - drivers/vfio/vfio.c:vfio_device_put
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890e29)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
```
In drivers/usb/core/hub.c (ffffffff818ab5b7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818ac392)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818af507)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff818b1450)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff818b640b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff818b6d63)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/md/dm.c (ffffffff819630d0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_put_table_device
```
```
In drivers/md/dm-table.c (ffffffff81964c9f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/edac/ghes_edac.c (ffffffff819758f2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_unregister
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af42e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819b1d24)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
```
In drivers/nvmem/core.c (ffffffff819bf855)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
```
In net/core/sock.c (ffffffff819cbf7f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_efree
  - net/core/sock.c:sock_efree
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_free_unlock_clone
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/request_sock.c (ffffffff819cf6ea)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff819d1d7a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__msg_zerocopy_callback
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff819daa80)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819df012)
Location: include/linux/refcount.h:270
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
In net/core/dev.c (ffffffff819edee5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff819f7cfb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff819fcc73)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_rcu_free_parms
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81a08d2f)
Location: include/linux/refcount.h:270
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
In net/core/filter.c (ffffffff81a14007)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/flow_offload.c (ffffffff81a201cb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
```
```
In net/core/page_pool.c (ffffffff81a23f42)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/netpoll.c (ffffffff81a25a3a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffff81a28ad2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/devlink.c (ffffffff81a3bdb5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_put
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
```
```
In net/core/skmsg.c (ffffffff81a4e873)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81a515dd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/bpf_sk_storage.c (ffffffff81a5251e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81a55686)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffff81a5ea05)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_put
```
```
In net/sched/act_api.c (ffffffff81a64806)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_delete
  - net/sched/act_api.c:tcf_del_walker
```
```
In net/netlink/af_netlink.c (ffffffff81a6ac74)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_detachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netfilter/nf_queue.c (ffffffff81a84963)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81a869c4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c323)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e5a2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a94de8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98655)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a645)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bbb4)
Location: include/linux/refcount.h:270
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
In net/ipv4/tcp.c (ffffffff81aa393d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81aab3b6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7fee)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8fcf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfcf4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a5c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4649)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81acee37)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/udp_offload.c (ffffffff81ad066d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff81ad201e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81ad7eb4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81adec7a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae5d02)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee1c7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (ffffffff81af0a02)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff81af84d6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv4/fib_rules.c (ffffffff81afb656)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffff81aff791)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/syncookies.c (ffffffff81b03b23)
Location: include/linux/refcount.h:270
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
In net/ipv4/tcp_bpf.c (ffffffff81b05850)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05dea)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b05fd9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b08460)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1231c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
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
In net/xfrm/xfrm_state.c (ffffffff81b14ced)
Location: include/linux/refcount.h:270
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
In net/unix/af_unix.c (ffffffff81b2170b)
Location: include/linux/refcount.h:270
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
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/af_inet6.c (ffffffff81b2717c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/anycast.c (ffffffff81b27fa3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81b3906f)
Location: include/linux/refcount.h:270
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
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81b40ae5)
Location: include/linux/refcount.h:270
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
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4bcf9)
Location: include/linux/refcount.h:270
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
In net/ipv6/ipv6_sockglue.c (ffffffff81b4e1f9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81b50e90)
Location: include/linux/refcount.h:270
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
In net/ipv6/udp.c (ffffffff81b550a1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81b5995a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81b5f3e4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
```
```
In net/ipv6/reassembly.c (ffffffff81b6375d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67e81)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81b72fbe)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b76106)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b76441)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffff81b79e00)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b7ac4a)
Location: include/linux/refcount.h:270
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
In net/packet/af_packet.c (ffffffff81b894de)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba55c0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff81ba75e0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8daf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff81bb0ac9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff81bb1e0f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_req_destructor
```
```
In net/mptcp/token.c (ffffffff81bb664f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb071)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
```
In net/mptcp/syncookies.c (ffffffff81bbceac)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
```
**Symbols:**

```
ffffffff813a2000-ffffffff813a2039: __refcount_sub_and_test.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff8103f70c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810601d3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068d49)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8106ffec)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107151f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810730ab)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810b5529)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
```
```
In kernel/exit.c (ffffffff810bb4b6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810c47c9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/ptrace.c:__x64_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810d3907)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810dcce4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff810dfe85)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810e59b9)
Location: include/linux/refcount.h:270
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
In kernel/cred.c (ffffffff810e7065)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (ffffffff810e9172)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/ucount.c (ffffffff810e9ef5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810f8cea)
Location: include/linux/refcount.h:270
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
In kernel/sched/fair.c (ffffffff8110d21e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff8111293c)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff8111873f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/autogroup.c (ffffffff811236d2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/core_sched.c (ffffffff8112c50b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
  - kernel/sched/core_sched.c:sched_core_free
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112dc8a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d54f6c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81141d8d)
Location: include/linux/refcount.h:270
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
In kernel/rcu/update.c (ffffffff8114dacf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
```
In kernel/kcmp.c (ffffffff81160547)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/namespace.c (ffffffff8117c829)
Location: include/linux/refcount.h:270
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
In kernel/futex.c (ffffffff8117f272)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff8119bb3b)
Location: include/linux/refcount.h:270
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
In kernel/cgroup/namespace.c (ffffffff8119e25f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119fb2a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff811a954a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811aa774)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811ab1c6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/audit.c (ffffffff811acd85)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff811b2b88)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff811b8605)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/audit_tree.c (ffffffff811bb845)
Location: include/linux/refcount.h:270
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
In kernel/kprobes.c (ffffffff811bcb26)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kprobes.c:free_rp_inst_rcu
```
```
In kernel/hung_task.c (ffffffff811cb889)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff811cde6c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff811d0b42)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffff811d2398)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace.c (ffffffff811e4170)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f528c)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff8122dd5a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff81252be0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_stop
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In kernel/bpf/trampoline.c (ffffffff8125f258)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/bpf/btf.c (ffffffff8126659d)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/dispatcher.c (ffffffff8126ad37)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/net_namespace.c (ffffffff81271347)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812778a5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
```
```
In kernel/events/core.c (ffffffff8128d299)
Location: include/linux/refcount.h:270
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
In kernel/events/ring_buffer.c (ffffffff8128e605)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff812903a5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/padata.c (ffffffff81294064)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
```
In kernel/watch_queue.c (ffffffff81297bf5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/oom_kill.c (ffffffff812a3263)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
```
```
In mm/backing-dev.c (ffffffff812c67f8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
```
In mm/process_vm_access.c (ffffffff8130084c)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/madvise.c (ffffffff8130d943)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/page_io.c (ffffffff8130f2bf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff8131aafe)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8132187d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
```
```
In mm/mempolicy.c (ffffffff813287f9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff8133d965)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff8134a264)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memcontrol.c (ffffffff81353151)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/memory-failure.c (ffffffff8135e6c8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/super.c (ffffffff813751f8)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/exec.c (ffffffff8137a6f5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namei.c (ffffffff81380235)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/inode.c (ffffffff81394cb3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/namespace.c (ffffffff8139d7a3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
```
```
In fs/fs_context.c (ffffffff813b9653)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc_namespace.c (ffffffff813c6459)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff813c7825)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffffffff813c832d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventfd.c (ffffffff813d371b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffff813d4005)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/aio.c (ffffffff813da84e)
Location: include/linux/refcount.h:270
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
In fs/io_uring.c (ffffffff813e5507)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_uring_drop_tctx_refs
```
```
In fs/io-wq.c (ffffffff813f30e6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_worker_release
Direct callers:
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/crypto/keyring.c (ffffffff813fa53f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff813fb11d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/posix_acl.c (ffffffff8140ea2c)
Location: include/linux/refcount.h:270
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
In fs/proc/task_mmu.c (ffffffff81420e9c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/root.c (ffffffff81424888)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff81426a81)
Location: include/linux/refcount.h:270
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
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/generic.c (ffffffff8142b3e5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/proc/fd.c (ffffffff8142dd9c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff81430a14)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff81434338)
Location: include/linux/refcount.h:270
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
In fs/sysfs/mount.c (ffffffff8143cca4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff814420e3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
```
In fs/ext4/ialloc.c (ffffffff81458e71)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff814b2c02)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In fs/hugetlbfs/inode.c (ffffffff814c8da0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/dev.c (ffffffff814e5f5c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In fs/fuse/file.c (ffffffff814f1c04)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (ffffffff814f4d95)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/fuse/dax.c (ffffffff814fac72)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_end
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In fs/debugfs/inode.c (ffffffff814fc7f4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff814fdccf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In ipc/util.c (ffffffff81502c55)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffff8150a064)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (ffffffff81510d2b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff81510f61)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff81511f85)
Location: include/linux/refcount.h:270
Inline: True
```
```
In security/keys/keyring.c (ffffffff81514e9f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/selinux/netlabel.c (ffffffff8155032a)
Location: include/linux/refcount.h:270
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
In security/smack/smack_lsm.c (ffffffff81552063)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/apparmor/apparmorfs.c (ffffffff8156e1e7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/audit.c (ffffffff81572434)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_rule_free
```
```
In security/apparmor/capability.c (ffffffff815726d6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff81573143)
Location: include/linux/refcount.h:270
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
In security/apparmor/lib.c (ffffffff81574623)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff815747ba)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff8157b209)
Location: include/linux/refcount.h:270
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
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
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
In security/apparmor/policy.c (ffffffff8157e0b1)
Location: include/linux/refcount.h:270
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
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81580bec)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81580ebe)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff815855ad)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
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
In security/apparmor/resource.c (ffffffff81586ec8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81588a33)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffff815895d4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In security/apparmor/label.c (ffffffff8158b3f6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
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
```
```
In security/apparmor/mount.c (ffffffff8158feed)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffff81590a7d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81592bbc)
Location: include/linux/refcount.h:270
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
In security/yama/yama_lsm.c (ffffffff81593b55)
Location: include/linux/refcount.h:270
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
In security/landlock/ruleset.c (ffffffff81596a8d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
  - security/landlock/ruleset.c:free_ruleset
```
```
In security/integrity/evm/evm_main.c (ffffffff815a2a73)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_xattr_change
```
```
In crypto/api.c (ffffffff815a437a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff815a6fac)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff815ae9f0)
Location: include/linux/refcount.h:270
Inline: True
```
```
In block/blk-flush.c (ffffffff815d08d5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff815d9f67)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/bsg-lib.c (ffffffff815f0045)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffff815f31b1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In lib/refcount.c (ffffffff8161d710)
Location: include/linux/refcount.h:270
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff8164b6f0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In lib/klist.c (ffffffff8165f649)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffff816600c9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In drivers/pinctrl/core.c (ffffffff8167a47e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c9dd2)
Location: include/linux/refcount.h:270
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
In drivers/video/fbdev/core/fbmem.c (ffffffff816de275)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81705480)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff8177b4b5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff81780f0f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179f272)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/reset/core.c (ffffffff817b366d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
```
```
In drivers/tty/tty_io.c (ffffffff817b8b21)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
```
In drivers/tty/tty_port.c (ffffffff817bff72)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/tty/tty_ldsem.c (ffffffff81d5696e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/char/virtio_console.c (ffffffff817fa70c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff817fc6f2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
```
```
In drivers/iommu/ioasid.c (ffffffff8182be8c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_put
```
```
In drivers/connector/cn_queue.c (ffffffff81830455)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/base/core.c (ffffffff81834923)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/firmware_loader/main.c (ffffffff81858c8c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff8188af93)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188f38f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffff818a15c1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818a41cb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_excl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818a585c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a5c3d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6a9b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a9109)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa9af)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff818ba0e5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
```
```
In drivers/scsi/sr.c (ffffffff818ca8e4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (ffffffff818ce268)
Location: include/linux/refcount.h:270
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
In drivers/ata/libata-core.c (ffffffff818d2a11)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/net/tun.c (ffffffff8190d8e6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819144ea)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/vfio/vfio.c (ffffffff81920a6f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
  - drivers/vfio/vfio.c:vfio_device_put
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192492b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
```
In drivers/usb/core/hub.c (ffffffff81940537)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff819413e2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81944657)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff819466a0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff8194bce7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff8194c762)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/md/dm.c (ffffffff81a0a0f0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_put_table_device
```
```
In drivers/md/dm-table.c (ffffffff81a0cc0f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81a1e613)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_unregister
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5da5e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81a60484)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
```
In drivers/nvmem/core.c (ffffffff81a6eea5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
```
In net/core/sock.c (ffffffff81a7b5df)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_efree
  - net/core/sock.c:sock_efree
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sk_free_unlock_clone
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/request_sock.c (ffffffff81a7f22a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81a819dc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:msg_zerocopy_callback
  - net/core/skbuff.c:msg_zerocopy_callback
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81a8b100)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81a8f3f2)
Location: include/linux/refcount.h:270
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
In net/core/dev.c (ffffffff81a9f185)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81aa992b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81aaecb3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_rcu_free_parms
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81abab4f)
Location: include/linux/refcount.h:270
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
In net/core/filter.c (ffffffff81acdfd1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/flow_offload.c (ffffffff81ad435b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
```
```
In net/core/page_pool.c (ffffffff81ad8f74)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/netpoll.c (ffffffff81ada77a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffff81add8c2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/devlink.c (ffffffff81af3035)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_put
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_put
```
```
In net/core/skmsg.c (ffffffff81b05223)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81b0955d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b627)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81b0e206)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffff81b17bd5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_put
```
```
In net/sched/act_api.c (ffffffff81b1f820)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_del_walker
```
```
In net/netlink/af_netlink.c (ffffffff81b24282)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_detachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81b41104)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffff81b472f3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49792)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b50248)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b53b35)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55ab5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b572b6)
Location: include/linux/refcount.h:270
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
In net/ipv4/tcp.c (ffffffff81b5faed)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81b672d7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81b751ae)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81b763cf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79d48)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e41c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82c86)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81b8d813)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f08b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff81b90c6e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81b969b1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81b9e15a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba55c2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae577)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (ffffffff81bb086f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff81bb9676)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv4/fib_rules.c (ffffffff81bbcad3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffff81bc1525)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/syncookies.c (ffffffff81bc5dd0)
Location: include/linux/refcount.h:270
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
In net/ipv4/tcp_bpf.c (ffffffff81bc83ad)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc8ab2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc8cc9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81bcb36c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd602d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
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
In net/xfrm/xfrm_state.c (ffffffff81bd8d1d)
Location: include/linux/refcount.h:270
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
In net/unix/af_unix.c (ffffffff81be68c4)
Location: include/linux/refcount.h:270
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
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/unix_bpf.c (ffffffff81beb837)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81becdb9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/anycast.c (ffffffff81bedef2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81bff80f)
Location: include/linux/refcount.h:270
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81c07115)
Location: include/linux/refcount.h:270
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
In net/ipv6/ip6_fib.c (ffffffff81c1303e)
Location: include/linux/refcount.h:270
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
In net/ipv6/ipv6_sockglue.c (ffffffff81c15532)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81c18240)
Location: include/linux/refcount.h:270
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
In net/ipv6/udp.c (ffffffff81c1db7a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81c20f83)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81c26ba4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
```
```
In net/ipv6/reassembly.c (ffffffff81c2b21d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2fb0c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d507)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c40b76)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c40eb1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffff81c44ab8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81c4590a)
Location: include/linux/refcount.h:270
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
In net/packet/af_packet.c (ffffffff81c555ee)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c73148)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff81c75260)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c76b6f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff81c7eb8a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff81c8009f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_req_destructor
```
```
In net/mptcp/token.c (ffffffff81c8565f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8ab45)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
**Symbols:**

```
ffffffff813f0da0-ffffffff813f0dd9: __refcount_sub_and_test.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81046e24)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106aebe)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075eb9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8107d913)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107f48e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810816a3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810cb89d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:vm_area_free
```
```
In kernel/exit.c (ffffffff810d1e8b)
Location: include/linux/refcount.h:270
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
In kernel/ptrace.c (ffffffff810db96d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810e9f35)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810f655c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff810fa97d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810ff795)
Location: include/linux/refcount.h:270
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
In kernel/cred.c (ffffffff81101345)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (ffffffff81103ef5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/ucount.c (ffffffff81104b77)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff811150ba)
Location: include/linux/refcount.h:270
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
In kernel/sched/fair.c (ffffffff81128dfd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff81134a0d)
Location: include/linux/refcount.h:270
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
In kernel/sched/build_utility.c (ffffffff8114d2aa)
Location: include/linux/refcount.h:270
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
In kernel/locking/percpu-rwsem.c (ffffffff8114ea5e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f26b0d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811658a1)
Location: include/linux/refcount.h:270
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
In kernel/rcu/update.c (ffffffff8117484e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff81e5f562)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811932a8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/namespace.c (ffffffff811b211e)
Location: include/linux/refcount.h:270
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
In kernel/futex/core.c (ffffffff811b31c8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/futex/core.c:wait_for_owner_exiting
```
```
In kernel/futex/pi.c (ffffffff811b4f44)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff811cbd82)
Location: include/linux/refcount.h:270
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
In kernel/cgroup/namespace.c (ffffffff811ce61f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0138)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff811da88e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811dbdb0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811dc8f6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/audit.c (ffffffff811de9a2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff811e4f00)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff811eb515)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/audit_tree.c (ffffffff811eec95)
Location: include/linux/refcount.h:270
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
In kernel/hung_task.c (ffffffff811ff650)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff81201b6c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff81204fc2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffff81206a5c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace.c (ffffffff8121b420)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122eaac)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff81268e30)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/trace/rethook.c:free_rethook_node_rcu
  - kernel/trace/rethook.c:rethook_free_rcu
```
```
In kernel/bpf/syscall.c (ffffffff81270767)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff8129b12d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In kernel/bpf/trampoline.c (ffffffff812a98b6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/bpf/btf.c (ffffffff812b313d)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/dispatcher.c (ffffffff812b9926)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/net_namespace.c (ffffffff812c043f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c7565)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
```
```
In kernel/events/core.c (ffffffff812e1fa1)
Location: include/linux/refcount.h:270
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
In kernel/events/ring_buffer.c (ffffffff812e34a5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff812e5535)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/padata.c (ffffffff812ea098)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
```
In kernel/watch_queue.c (ffffffff812edeb8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/oom_kill.c (ffffffff812fb15a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/backing-dev.c (ffffffff8132398a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/process_vm_access.c (ffffffff81367c28)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/madvise.c (ffffffff81378e1e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/page_io.c (ffffffff813794d9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81386230)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8138e827)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:clear_vma_resv_huge_pages
```
```
In mm/mempolicy.c (ffffffff81397a49)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff813b0c20)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff813c0e0c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memcontrol.c (ffffffff813cdc51)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/memory-failure.c (ffffffff813d8ea8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/super.c (ffffffff813f4508)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/exec.c (ffffffff813fa471)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namei.c (ffffffff814016fc)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/inode.c (ffffffff81417066)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/namespace.c (ffffffff8142075e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
```
```
In fs/fs_context.c (ffffffff8143f0ad)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc_namespace.c (ffffffff8144ccdd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff8144ec05)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffffffff8144f4c0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventfd.c (ffffffff8145cf89)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffff8145db45)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/aio.c (ffffffff8146523b)
Location: include/linux/refcount.h:270
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
In fs/crypto/keyring.c (ffffffff8146d67c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff8146e432)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/posix_acl.c (ffffffff814841c4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
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
In fs/proc/task_mmu.c (ffffffff81498d19)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/root.c (ffffffff8149d498)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff814a0411)
Location: include/linux/refcount.h:270
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
In fs/proc/generic.c (ffffffff814a4ac5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/proc/fd.c (ffffffff814a7598)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff814aa744)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff814ae40a)
Location: include/linux/refcount.h:270
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
In fs/sysfs/mount.c (ffffffff814b84c4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff814bdd55)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff814d6a6e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/page-io.c (ffffffff81509115)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
```
```
In fs/ext4/acl.c (ffffffff8153b875)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In fs/hugetlbfs/inode.c (ffffffff815544fe)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/dev.c (ffffffff8157439b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In fs/fuse/file.c (ffffffff81581655)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (ffffffff81584965)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/fuse/dax.c (ffffffff8158b382)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_end
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In fs/debugfs/inode.c (ffffffff8158cf4e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff8158e88f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In ipc/util.c (ffffffff81594235)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffff8159bda4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (ffffffff815a2f30)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff815a3415)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In security/keys/key.c (ffffffff815a441a)
Location: include/linux/refcount.h:270
Inline: True
```
```
In security/keys/keyring.c (ffffffff815a75ff)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/selinux/netlabel.c (ffffffff815e97b2)
Location: include/linux/refcount.h:270
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
In security/smack/smack_lsm.c (ffffffff815eba6a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/apparmor/apparmorfs.c (ffffffff8160d61e)
Location: include/linux/refcount.h:270
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
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
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
In security/apparmor/audit.c (ffffffff8160f383)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_rule_free
```
```
In security/apparmor/capability.c (ffffffff8160f6c3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff81610433)
Location: include/linux/refcount.h:270
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
In security/apparmor/lib.c (ffffffff81611ef3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff8161226a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff81619577)
Location: include/linux/refcount.h:270
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
In security/apparmor/policy.c (ffffffff8161c823)
Location: include/linux/refcount.h:270
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
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8161fc0c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8162005d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81624135)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid_obj
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
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
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff816272dd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816290ea)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffff81629e34)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff8162c96b)
Location: include/linux/refcount.h:270
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
In security/apparmor/mount.c (ffffffff81630e3b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffff81631bdf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81634998)
Location: include/linux/refcount.h:270
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
In security/yama/yama_lsm.c (ffffffff816355f1)
Location: include/linux/refcount.h:270
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
In security/landlock/ruleset.c (ffffffff81638efb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
  - security/landlock/ruleset.c:free_ruleset
```
```
In security/integrity/evm/evm_main.c (ffffffff816491a3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_xattr_change
```
```
In crypto/api.c (ffffffff8164ad34)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff8164e10c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff81657010)
Location: include/linux/refcount.h:270
Inline: True
```
```
In block/bsg-lib.c (ffffffff816a0fd5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffff816a4625)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff816cb36f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_put_task
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
```
```
In io_uring/io-wq.c (ffffffff816dbc4e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_worker_release
```
```
In lib/refcount.c (ffffffff816eb33a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff81762192)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In lib/klist.c (ffffffff81778d99)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffff81779bd7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In drivers/pinctrl/core.c (ffffffff81795a7e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817f00cc)
Location: include/linux/refcount.h:270
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81808225)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8183379e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff818b1d0d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff818b7bf8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d8e82)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/reset/core.c (ffffffff818eeefd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
```
```
In drivers/tty/tty_io.c (ffffffff818f4aeb)
Location: include/linux/refcount.h:270
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
In drivers/tty/tty_port.c (ffffffff818fc682)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff81f28b06)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/char/virtio_console.c (ffffffff81938d3e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff8193b442)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
```
```
In drivers/connector/cn_queue.c (ffffffff81971715)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/base/core.c (ffffffff819762e3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199f9ab)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff819d46e3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d88ff)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffff819eacd1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ed469)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff819ef6c5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819efb94)
Location: include/linux/refcount.h:270
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
In drivers/dma-buf/dma-resv.c (ffffffff819f10cf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
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
In drivers/dma-buf/sync_file.c (ffffffff819f3076)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f5052)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a05b08)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
```
```
In drivers/scsi/sg.c (ffffffff81a1c7bc)
Location: include/linux/refcount.h:270
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
In drivers/ata/libata-core.c (ffffffff81a22fc1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/net/tun.c (ffffffff81a608eb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69c01)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/vfio/vfio.c (ffffffff81a77179)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
  - drivers/vfio/vfio.c:vfio_device_put
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7a29b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
```
In drivers/usb/core/hub.c (ffffffff81a9878d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81a99b82)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81a9d121)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81a9eea0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff81aa4775)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff81aa5272)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/md/dm.c (ffffffff81b735d0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_put_table_device
```
```
In drivers/md/dm-table.c (ffffffff81b754ff)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81b86d8d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_unregister
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcdb89)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81bd0994)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
```
In drivers/nvmem/core.c (ffffffff81bdff25)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
```
In net/core/sock.c (ffffffff81befed3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
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
In net/core/request_sock.c (ffffffff81bf34ea)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81bf61bc)
Location: include/linux/refcount.h:270
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
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81c00891)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81c05252)
Location: include/linux/refcount.h:270
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
In net/core/dev.c (ffffffff81c0f3f4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81c21d66)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81c27a4f)
Location: include/linux/refcount.h:270
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
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81c35356)
Location: include/linux/refcount.h:270
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
In net/core/filter.c (ffffffff81c4bdd1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/flow_offload.c (ffffffff81c528d3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
```
```
In net/core/gro.c (ffffffff81c53833)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/page_pool.c (ffffffff81c5a0f4)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/netpoll.c (ffffffff81c5be4a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffff81c5f24e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/core/devlink.c (ffffffff81c7e630)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_linecard_destroy
  - net/core/devlink.c:devlink_health_reporter_put
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_put
```
```
In net/core/skmsg.c (ffffffff81c8d506)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81c8f687)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91c3b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81c95c32)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffff81c9fa55)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ca767d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_notify
```
```
In net/netlink/af_netlink.c (ffffffff81cadba2)
Location: include/linux/refcount.h:270
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
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81cce3f6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffff81cd4433)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81cd5596)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6d75)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_output.c (ffffffff81cd9c7e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cde747)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1615)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3a4d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5235)
Location: include/linux/refcount.h:270
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
In net/ipv4/tcp.c (ffffffff81cee59c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81cf68dd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81d0499e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05ba1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09a98)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
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
In net/ipv4/tcp_minisocks.c (ffffffff81d0e394)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d132c9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81d14d14)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81d17b58)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1e96f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/udp_offload.c (ffffffff81d1fd25)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff81d235cc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81d28645)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81d3040a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d37f83)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41767)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (ffffffff81d42b06)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff81d4d655)
Location: include/linux/refcount.h:270
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
In net/ipv4/fib_rules.c (ffffffff81d510e0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffff81d5864f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/syncookies.c (ffffffff81d5b064)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5dc1d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5e164)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5e468)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81d60dac)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c7ae)
Location: include/linux/refcount.h:270
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
In net/xfrm/xfrm_state.c (ffffffff81d6f7f8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
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
In net/xfrm/xfrm_input.c (ffffffff81d7621b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77eed)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff81d7db24)
Location: include/linux/refcount.h:270
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
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/unix_bpf.c (ffffffff81d83b24)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81d852a3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/anycast.c (ffffffff81d86453)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/ip6_output.c (ffffffff81d88251)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d118)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81d992fb)
Location: include/linux/refcount.h:270
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81da17af)
Location: include/linux/refcount.h:270
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
In net/ipv6/ip6_fib.c (ffffffff81dae793)
Location: include/linux/refcount.h:270
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
In net/ipv6/ipv6_sockglue.c (ffffffff81db0d39)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81db4269)
Location: include/linux/refcount.h:270
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
```
```
In net/ipv6/udp.c (ffffffff81dba19e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81dbdd4f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/mcast.c (ffffffff81dc4634)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
```
```
In net/ipv6/reassembly.c (ffffffff81dc84c8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccf3a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81ddbe8f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddf296)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf5e2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffff81de3ab9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81de4a20)
Location: include/linux/refcount.h:270
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
In net/ipv6/seg6_iptunnel.c (ffffffff81de6938)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81de869b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff81df537f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/xdp/xsk.c (ffffffff81e16eaa)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff81e193df)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1b513)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff81e24330)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff81e25cff)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_req_destructor
```
```
In net/mptcp/token.c (ffffffff81e2b87b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff81e31a02)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff81e360a7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/af_mctp.c (ffffffff81e37a64)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
```
```
In net/mctp/device.c (ffffffff81e3872b)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/mctp/route.c (ffffffff81e39425)
Location: include/linux/refcount.h:270
Inline: True
```
**Symbols:**

```
ffffffff816ca2c0-ffffffff816ca316: __refcount_sub_and_test.constprop.0 (STB_LOCAL)
ffffffff81a690e0-ffffffff81a69120: __refcount_sub_and_test.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81050f74)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107ae0e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810860e9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8108ee83)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810912ee)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093f83)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810e8eb4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:vm_area_free
```
```
In kernel/exit.c (ffffffff810f08eb)
Location: include/linux/refcount.h:270
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
In kernel/ptrace.c (ffffffff810fba3d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff8110a745)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff81118bec)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff8111d7d2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff811244c5)
Location: include/linux/refcount.h:270
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
In kernel/cred.c (ffffffff81126495)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (ffffffff8112965f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/ucount.c (ffffffff8112a467)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff8113c45a)
Location: include/linux/refcount.h:270
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
In kernel/sched/fair.c (ffffffff8115283d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8115ef2d)
Location: include/linux/refcount.h:270
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
In kernel/sched/build_utility.c (ffffffff8117c34a)
Location: include/linux/refcount.h:270
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
In kernel/locking/percpu-rwsem.c (ffffffff8117dbfe)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d25dc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811997f1)
Location: include/linux/refcount.h:270
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
In kernel/rcu/update.c (ffffffff811ab4a1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff811b147d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811d0ae8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/namespace.c (ffffffff811f2f4e)
Location: include/linux/refcount.h:270
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
In kernel/futex/core.c (ffffffff811f40d8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/futex/core.c:wait_for_owner_exiting
```
```
In kernel/futex/pi.c (ffffffff811f6034)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff8120f252)
Location: include/linux/refcount.h:270
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
In kernel/cgroup/namespace.c (ffffffff81211e6f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81213b9e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff8121fe9e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81221600)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81222236)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/audit.c (ffffffff81224562)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8122af20)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff81231905)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81235365)
Location: include/linux/refcount.h:270
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
In kernel/hung_task.c (ffffffff81247065)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff8124995c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff8124ce42)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffff8124ed8c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace.c (ffffffff81264f40)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127aaac)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6b70)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
```
In kernel/trace/rethook.c (ffffffff812bb120)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/trace/rethook.c:free_rethook_node_rcu
  - kernel/trace/rethook.c:rethook_free_rcu
```
```
In kernel/bpf/syscall.c (ffffffff812c6271)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/helpers.c (ffffffff812f424f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_release
```
```
In kernel/bpf/task_iter.c (ffffffff812f7457)
Location: include/linux/refcount.h:270
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
In kernel/bpf/trampoline.c (ffffffff81308429)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8131356d)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/dispatcher.c (ffffffff8131caf2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/net_namespace.c (ffffffff81323c70)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132cf45)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
```
```
In kernel/events/core.c (ffffffff8134a4d1)
Location: include/linux/refcount.h:270
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
In kernel/events/ring_buffer.c (ffffffff8134bb25)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff8134ef15)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/padata.c (ffffffff81353f58)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
```
In kernel/watch_queue.c (ffffffff813582d8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/oom_kill.c (ffffffff81364477)
Location: include/linux/refcount.h:270
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
In mm/backing-dev.c (ffffffff813981f7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/process_vm_access.c (ffffffff813e3bf8)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/madvise.c (ffffffff813f66d0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/page_io.c (ffffffff813f6ef9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81404060)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8140d2f5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:__unmap_hugepage_range_final
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:clear_vma_resv_huge_pages
```
```
In mm/mempolicy.c (ffffffff81417629)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff81431770)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-tiers.c (ffffffff81437581)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/memory-tiers.c:clear_node_memory_type
  - mm/memory-tiers.c:destroy_memory_type
```
```
In mm/huge_memory.c (ffffffff81442cdc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memcontrol.c (ffffffff81452311)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/memory-failure.c (ffffffff8145e9b9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/super.c (ffffffff8147d598)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/exec.c (ffffffff81483f75)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namei.c (ffffffff8148b7ef)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/inode.c (ffffffff814a2666)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/namespace.c (ffffffff814acd00)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:free_vfsmnt
```
```
In fs/fs_context.c (ffffffff814cdd2d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc_namespace.c (ffffffff814db24d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff814dd3a5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffffffff814ddd30)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventfd.c (ffffffff814ec719)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffff814ed595)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/aio.c (ffffffff814f527b)
Location: include/linux/refcount.h:270
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
In fs/crypto/keyring.c (ffffffff814feb1b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
```
In fs/posix_acl.c (ffffffff81517634)
Location: include/linux/refcount.h:270
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
In fs/proc/task_mmu.c (ffffffff8152d023)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/root.c (ffffffff81531f98)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff81535331)
Location: include/linux/refcount.h:270
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
In fs/proc/generic.c (ffffffff81539fe5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/proc/fd.c (ffffffff8153cc78)
Location: include/linux/refcount.h:270
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
In fs/proc/namespaces.c (ffffffff81540394)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff81544a1a)
Location: include/linux/refcount.h:270
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
In fs/sysfs/mount.c (ffffffff8154fad4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff81555ac5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8156f813)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/page-io.c (ffffffff815a3cb5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
```
```
In fs/ext4/acl.c (ffffffff815d9ea5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In fs/hugetlbfs/inode.c (ffffffff815f5e6e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/fuse/dev.c (ffffffff81619c2b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In fs/fuse/file.c (ffffffff816274b5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (ffffffff8162aaa5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/fuse/dax.c (ffffffff81631ba2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_end
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In fs/debugfs/inode.c (ffffffff8163394e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff8163590f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In ipc/util.c (ffffffff8163ce35)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffff816451a4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (ffffffff8164ca90)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8164d005)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In security/keys/key.c (ffffffff8164e18a)
Location: include/linux/refcount.h:270
Inline: True
```
```
In security/keys/keyring.c (ffffffff8165161f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/selinux/netlabel.c (ffffffff816990f2)
Location: include/linux/refcount.h:270
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
In security/smack/smack_lsm.c (ffffffff8169b68a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/apparmor/apparmorfs.c (ffffffff816bf59e)
Location: include/linux/refcount.h:270
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
In security/apparmor/audit.c (ffffffff816c1733)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_rule_free
```
```
In security/apparmor/capability.c (ffffffff816c20c1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff816c2e93)
Location: include/linux/refcount.h:270
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
In security/apparmor/lib.c (ffffffff816c4c03)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff83ed36ba)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff816cc470)
Location: include/linux/refcount.h:270
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
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/policy.c (ffffffff816cfac3)
Location: include/linux/refcount.h:270
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
In security/apparmor/policy_unpack.c (ffffffff816d305d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff816d355a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff816d9f7f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - security/apparmor/lsm.c:apparmor_sb_mount
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
In security/apparmor/resource.c (ffffffff816db2e1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816dd9ba)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffff83ed3f25)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff816e141b)
Location: include/linux/refcount.h:270
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
In security/apparmor/mount.c (ffffffff816e5b76)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffff816e6907)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff816e98df)
Location: include/linux/refcount.h:270
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
In security/apparmor/notify.c (ffffffff816eb568)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:build_unotif
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:__listener_complete_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:aa_free_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/yama/yama_lsm.c (ffffffff816ec2d1)
Location: include/linux/refcount.h:270
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
In security/landlock/ruleset.c (ffffffff816f041b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
  - security/landlock/ruleset.c:free_ruleset
```
```
In crypto/api.c (ffffffff81703ef4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff8170758c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
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
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff817113c0)
Location: include/linux/refcount.h:270
Inline: True
```
```
In block/blk-core.c (ffffffff817346e5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-core.c:blk_put_queue
```
```
In block/bsg-lib.c (ffffffff8175fbc5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffff81763355)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff8178ba25)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:__io_put_task
```
```
In io_uring/net.c (ffffffff81797dba)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
```
```
In io_uring/sqpoll.c (ffffffff8179aa95)
Location: include/linux/refcount.h:270
Inline: True
```
```
In io_uring/notif.c (ffffffff817a51a3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - io_uring/notif.c:io_tx_ubuf_callback_ext
```
```
In io_uring/io-wq.c (ffffffff817a7d52)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_worker_release
```
```
In lib/refcount.c (ffffffff817db9ea)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff81890eb2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In drivers/pinctrl/core.c (ffffffff818aad7e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8191828c)
Location: include/linux/refcount.h:270
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
In drivers/video/fbdev/core/fbmem.c (ffffffff819371e5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8196735e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff819fe345)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff81a04e78)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2b902)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/reset/core.c (ffffffff81a46b9d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
```
```
In drivers/tty/tty_io.c (ffffffff81a4d117)
Location: include/linux/refcount.h:270
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
In drivers/tty/tty_port.c (ffffffff81a55cb2)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff820d4766)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/char/virtio_console.c (ffffffff81a98e2d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff81a9bba2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
```
```
In drivers/connector/cn_queue.c (ffffffff81adc915)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/base/core.c (ffffffff81ae23c3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b1144b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81b4ef73)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b5384f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffff81b677e1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b6a6ee)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81b6cc95)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d1d4)
Location: include/linux/refcount.h:270
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
In drivers/dma-buf/dma-resv.c (ffffffff81b6eaaf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
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
In drivers/dma-buf/sync_file.c (ffffffff81b70dc6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b72512)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/scsi/hosts.c (ffffffff81b76f20)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b84868)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b88475)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
```
In drivers/scsi/sg.c (ffffffff81b9da4c)
Location: include/linux/refcount.h:270
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
In drivers/ata/libata-core.c (ffffffff81ba4cd1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/net/pse-pd/pse_core.c (ffffffff81bea22f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/pse-pd/pse_core.c:pse_control_put
```
```
In drivers/net/tun.c (ffffffff81bee881)
Location: include/linux/refcount.h:270
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
In drivers/net/ppp/ppp_generic.c (ffffffff81bfc7c1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/core/hub.c (ffffffff81c1b649)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81c1dd22)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c221b1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81c242e0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff81c2aef5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c2bc62)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/md/dm.c (ffffffff81d10160)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_put_table_device
```
```
In drivers/md/dm-table.c (ffffffff81d127d9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/edac/ghes_edac.c (ffffffff842b2d36)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
```
```
In drivers/nvmem/core.c (ffffffff81d8b6e5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
```
In net/core/sock.c (ffffffff81d9c46a)
Location: include/linux/refcount.h:270
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
In net/core/request_sock.c (ffffffff81da124a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81da4a9c)
Location: include/linux/refcount.h:270
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
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81dafb8d)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81db4ae2)
Location: include/linux/refcount.h:270
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
In net/core/dev.c (ffffffff81dbf182)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81dd3fa6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81dda60f)
Location: include/linux/refcount.h:270
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
In net/core/rtnetlink.c (ffffffff81de8896)
Location: include/linux/refcount.h:270
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
In net/core/filter.c (ffffffff81dfd0e3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/flow_offload.c (ffffffff81e07e83)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
```
```
In net/core/gro.c (ffffffff81e08f0a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/page_pool.c (ffffffff81e0fbb4)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e122ca)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffff81e15ade)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/core/devlink.c (ffffffff81e37270)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_linecard_destroy
  - net/core/devlink.c:devlink_health_reporter_put
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_post_doit
```
```
In net/core/skmsg.c (ffffffff81e45b46)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81e4aac1)
Location: include/linux/refcount.h:270
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
In net/core/bpf_sk_storage.c (ffffffff81e4d20b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81e517d2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffff81e5bd15)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/sched/act_api.c (ffffffff81e643bd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_del_notify
```
```
In net/netlink/af_netlink.c (ffffffff81e6b182)
Location: include/linux/refcount.h:270
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
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81e8e606)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffff81e946e3)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81e95a68)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81e97305)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_output.c (ffffffff81e9a40e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9e657)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea2795)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5fb5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8425)
Location: include/linux/refcount.h:270
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
In net/ipv4/tcp.c (ffffffff81eb17dc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ebb2ed)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81ec997e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecacf1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece567)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_realloc_batch
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
In net/ipv4/tcp_minisocks.c (ffffffff81ed3e44)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed9239)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81edae54)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81ede3f9)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee5a9d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6f15)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff81eeabcc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81ef0075)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81ef853a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f007d3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a567)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (ffffffff81f0b9d6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff81f16f55)
Location: include/linux/refcount.h:270
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
In net/ipv4/fib_rules.c (ffffffff81f1af20)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffff81f22ae1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/syncookies.c (ffffffff81f254d4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f278cd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f2886b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f28b68)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f2b65c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f37b41)
Location: include/linux/refcount.h:270
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
In net/xfrm/xfrm_state.c (ffffffff81f3af98)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
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
In net/xfrm/xfrm_input.c (ffffffff81f42967)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f4478d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff81f4ac74)
Location: include/linux/refcount.h:270
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
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/unix_bpf.c (ffffffff81f51324)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81f52cf3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/anycast.c (ffffffff81f53fa3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/ip6_output.c (ffffffff81f56001)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b20f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81f6801b)
Location: include/linux/refcount.h:270
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81f70b0f)
Location: include/linux/refcount.h:270
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
In net/ipv6/ip6_fib.c (ffffffff81f7e2a2)
Location: include/linux/refcount.h:270
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
In net/ipv6/ipv6_sockglue.c (ffffffff81f80bd2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81f83d5a)
Location: include/linux/refcount.h:270
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
```
```
In net/ipv6/udp.c (ffffffff81f8a24e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81f8e25f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/mcast.c (ffffffff81f95292)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
```
```
In net/ipv6/reassembly.c (ffffffff81f99258)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e05e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81faf09f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb14e6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1892)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffff81fb6139)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81fb7190)
Location: include/linux/refcount.h:270
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
In net/ipv6/seg6_iptunnel.c (ffffffff81fb974a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb7db)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff81fc7cff)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/xdp/xsk.c (ffffffff81fee87a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff81ff06bf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2ad3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff81ffbe10)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff81ffdacf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/subflow.c:subflow_req_destructor
```
```
In net/mptcp/token.c (ffffffff82003a4b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff8200a047)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff8200edc7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
```
In net/mctp/af_mctp.c (ffffffff82010cbf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
```
```
In net/mctp/device.c (ffffffff820119eb)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/mctp/route.c (ffffffff82012935)
Location: include/linux/refcount.h:270
Inline: True
```
```
In lib/klist.c (ffffffff82021ba9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffff82022bd7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81bfbbf0-ffffffff81bfbc30: __refcount_sub_and_test.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81051ca4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107cf5e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088bc9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091d73)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109422e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096f0b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810f4acf)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff811177d0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff811260ac)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff8112a9c2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff811317c5)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (ffffffff81136aff)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/ucount.c (ffffffff811374b7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff8115009c)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8116f61d)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff821569a6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811ab4d3)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff811c3143)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811e4d5e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd35f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running
```
```
In kernel/time/namespace.c (ffffffff812075b2)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/futex/core.c:wait_for_owner_exiting
```
```
In kernel/futex/pi.c (ffffffff8120a834)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff81224c62)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812294da)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff8123608e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81237ab0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81238866)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/audit.c (ffffffff8123ab32)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8124151a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff81248595)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/audit_tree.c (ffffffff8124c042)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff81260c4c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff812643e2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffff8126613c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace.c (ffffffff8127c000)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129260c)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff81296ea5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_release
  - kernel/trace/trace_osnoise.c:stop_kthread
```
```
In kernel/trace/trace_events_user.c (ffffffff812c7268)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
  - kernel/trace/trace_events_user.c:delayed_destroy_user_event
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8c30)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
```
In kernel/trace/rethook.c (ffffffff812ded20)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/trace/rethook.c:free_rethook_node_rcu
  - kernel/trace/rethook.c:rethook_free_rcu
```
```
In kernel/bpf/syscall.c (ffffffff812ed331)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/helpers.c (ffffffff81320d10)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_obj_drop_impl
```
```
In kernel/bpf/task_iter.c (ffffffff8132532d)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8134323d)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/bpf/dispatcher.c (ffffffff8134c7f1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/net_namespace.c (ffffffff81353e9e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In kernel/bpf/cpumask.c (ffffffff8135d645)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_release
```
```
In kernel/events/core.c (ffffffff8137b511)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff813800d5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In kernel/padata.c (ffffffff81385158)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
```
In kernel/watch_queue.c (ffffffff81389b07)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/process_vm_access.c (ffffffff81418948)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/madvise.c (ffffffff814296b5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/page_io.c (ffffffff8142a2cb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_bdev_sync
```
```
In mm/zswap.c (ffffffff81436e2c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff814406d2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:__unmap_hugepage_range_final
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:clear_vma_resv_huge_pages
```
```
In mm/mempolicy.c (ffffffff8144abb9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff814671b0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-tiers.c (ffffffff8146d241)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/memory-tiers.c:clear_node_memory_type
  - mm/memory-tiers.c:destroy_memory_type
```
```
In mm/huge_memory.c (ffffffff8147859c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memcontrol.c (ffffffff81487e21)
Location: include/linux/refcount.h:270
Inline: True
```
```
In mm/memory-failure.c (ffffffff81494809)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/super.c (ffffffff814b2350)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/exec.c (ffffffff814b87b7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namei.c (ffffffff814bf830)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/inode.c (ffffffff814d77c6)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/namespace.c (ffffffff814df6fd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff81503f1d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/mnt_idmapping.c (ffffffff81506ba1)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/proc_namespace.c (ffffffff8150f72e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff81513c05)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffffffff81514552)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventpoll.c (ffffffff8151d445)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/eventfd.c (ffffffff81523669)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffff815242b5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/aio.c (ffffffff8152c04b)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/posix_acl.c (ffffffff8154ef0a)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff8156d501)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/proc/fd.c (ffffffff81574f38)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff8157c60d)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff8158d865)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff815a766c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/page-io.c (ffffffff815da735)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
```
```
In fs/ext4/acl.c (ffffffff81611a85)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In fs/hugetlbfs/inode.c (ffffffff8162dd3d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/fuse/dev.c (ffffffff81651ddb)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In fs/fuse/file.c (ffffffff8165f878)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (ffffffff81662cc5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In fs/fuse/dax.c (ffffffff81669de2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_end
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In fs/debugfs/inode.c (ffffffff8166bc4e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff8166dc1f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In ipc/util.c (ffffffff81675345)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffff8167d6a4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (ffffffff816851f0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff816857a7)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In security/keys/key.c (ffffffff816869ea)
Location: include/linux/refcount.h:270
Inline: True
```
```
In security/keys/keyring.c (ffffffff81689ebf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/selinux/netlabel.c (ffffffff816d15a2)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/apparmor/apparmorfs.c (ffffffff816f80ae)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
  - security/apparmor/audit.c:aa_audit_rule_free
```
```
In security/apparmor/capability.c (ffffffff816facd8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff816fba43)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/domain.c (ffffffff81704fbf)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff836f8be4)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81716fda)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffff836f9065)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff8171aa13)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffff81720038)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff817230cb)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
  - security/landlock/ruleset.c:free_ruleset
```
```
In crypto/api.c (ffffffff8173e2d4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff8173fea1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff8174beb0)
Location: include/linux/refcount.h:270
Inline: True
```
```
In block/blk-core.c (ffffffff81770b55)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-core.c:blk_put_queue
```
```
In block/bsg-lib.c (ffffffff8179eaa5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffff817a24a5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff817ccb6f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_put_task_remote
```
```
In io_uring/net.c (ffffffff817d8b3a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
```
```
In io_uring/sqpoll.c (ffffffff817dbb45)
Location: include/linux/refcount.h:270
Inline: True
```
```
In io_uring/notif.c (ffffffff817e6173)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - io_uring/notif.c:io_tx_ubuf_callback_ext
```
```
In io_uring/io-wq.c (ffffffff817e8bcf)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_worker_release
```
```
In rust/helpers.c (ffffffff81805ae5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_put_task_struct
  - rust/helpers.c:rust_helper_refcount_dec_and_test
```
```
In lib/refcount.c (ffffffff8181ac5a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff818d39b3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In drivers/pinctrl/core.c (ffffffff818edc5e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195b8ac)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff819ad92e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff81a46fc5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff81a4dcd8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a750a2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/reset/core.c (ffffffff81a90d3d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
```
```
In drivers/tty/tty_io.c (ffffffff81a97417)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff82158976)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/char/virtio_console.c (ffffffff81ae464d)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7502)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
```
```
In drivers/connector/cn_queue.c (ffffffff81b2ab85)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/base/core.c (ffffffff81b302e3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5f6db)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81ba23c3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6d4f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffff81bba3ed)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/dax/bus.c:__free_dev_dax_id
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbdb3e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc03d4)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0900)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5f16)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd85d8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc355)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
```
In drivers/scsi/sg.c (ffffffff81bf407a)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/net/pse-pd/pse_core.c (ffffffff81c4265f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/pse-pd/pse_core.c:pse_control_put
```
```
In drivers/net/tun.c (ffffffff81c46db1)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61e41)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/core/hub.c (ffffffff81c8256e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81c84c22)
Location: include/linux/refcount.h:270
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c89121)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81c8b2c0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff81c91e85)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c92bf2)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/md/dm.c (ffffffff81d795d0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_put_table_device
```
```
In drivers/md/dm-table.c (ffffffff81d7bb99)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/edac/ghes_edac.c (ffffffff83af5a46)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
```
```
In drivers/nvmem/core.c (ffffffff81df9c45)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
```
In net/core/sock.c (ffffffff81e0acba)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81e1370c)
Location: include/linux/refcount.h:270
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
In net/core/datagram.c (ffffffff81e1fdfd)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81e25182)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/dst.c (ffffffff81e44c06)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81e4b37f)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/flow_offload.c (ffffffff81e7a7a3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
```
```
In net/core/gro.c (ffffffff81e7b62b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/page_pool.c (ffffffff81e833f4)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e85b0a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffff81e893ee)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/core/skmsg.c (ffffffff81ea115f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81ea61b9)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81ead022)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffff81eb8515)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ebdc73)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec6cba)
Location: include/linux/refcount.h:270
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
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81eecd26)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffff81ef2eb3)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81ef42a8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5b35)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_output.c (ffffffff81ef8d68)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efce57)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00fb5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04765)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06ca5)
Location: include/linux/refcount.h:270
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
In net/ipv4/tcp.c (ffffffff81f0fe6c)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81f19179)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81f284ce)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29821)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2da57)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f38338)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81f3d730)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3fdde)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_next
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/udp_offload.c (ffffffff81f467bc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff81f4a4ba)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81f4fac5)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81f57faa)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f60253)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a097)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/nexthop.c (ffffffff81f76c35)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffff81f82617)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/syncookies.c (ffffffff81f85064)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87678)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f886d8)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f8b2d1)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f97539)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3f8e)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffff81faa924)
Location: include/linux/refcount.h:270
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
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/unix_bpf.c (ffffffff81fb0c7d)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81fb26dc)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/anycast.c (ffffffff81fb3993)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/ip6_output.c (ffffffff81fb59cd)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb055)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81fc806a)
Location: include/linux/refcount.h:270
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
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81fd0bff)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81fe40aa)
Location: include/linux/refcount.h:270
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
```
```
In net/ipv6/udp.c (ffffffff81fe9e8d)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81ff5c39)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
```
```
In net/ipv6/reassembly.c (ffffffff81ff9c28)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffeacf)
Location: include/linux/refcount.h:270
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
In net/ipv6/ip6mr.c (ffffffff8200ee70)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff82011b96)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff82011f33)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffff82016851)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff820178cd)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff8201be9b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff82028ca3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/devlink/core.c (ffffffff820422c5)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/devlink/dev.c (ffffffff82044c72)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
```
In net/xdp/xsk.c (ffffffff8206a98a)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff8206c86f)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206ecf3)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff820781e0)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff82079dc5)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff82086d40)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b9b7)
Location: include/linux/refcount.h:270
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
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
```
```
In net/mctp/device.c (ffffffff8208e7db)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/mctp/route.c (ffffffff8208f725)
Location: include/linux/refcount.h:270
Inline: True
```
```
In net/handshake/request.c (ffffffff8209384b)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
```
```
In lib/klist.c (ffffffff820a1be9)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffff820a2c47)
Location: include/linux/refcount.h:270
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81c61180-ffffffff81c611c0: __refcount_sub_and_test.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81058ec4)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8108443e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108ec0e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81099153)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109b70e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_free
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e47b)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810fde6f)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff811211c0)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff811306ac)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff8113519c)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop_put
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff8113c5b7)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/ucount.c (ffffffff81142697)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/groups.c (ffffffff81143b4d)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff8115bf6c)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8117c401)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff822397e6)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811b825e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffff811cda06)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_holdout_task
```
```
In kernel/rcu/tree.c (ffffffff811d3383)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811faaae)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121355f)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running
```
```
In kernel/time/namespace.c (ffffffff8121e7c2)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/futex/core.c:wait_for_owner_exiting
```
```
In kernel/futex/pi.c (ffffffff81221d94)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/futex/waitwake.c (ffffffff812238e1)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_mark
```
```
In kernel/uid16.c (ffffffff8122775a)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/uid16.c:__do_sys_setgroups16
  - kernel/uid16.c:__do_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff8123c958)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8124132a)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff8124fd0e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81251303)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81252536)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/audit.c (ffffffff81254822)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8125b34e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff812624b5)
Location: include/linux/refcount.h:259
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81265f42)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff8127ae1c)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
  - kernel/seccomp.c:__seccomp_filter_orphan
```
```
In kernel/relay.c (ffffffff8127e1d2)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffff8128002c)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace.c (ffffffff81296cf0)
Location: include/linux/refcount.h:259
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812adc4c)
Location: include/linux/refcount.h:259
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b24f5)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_release
  - kernel/trace/trace_osnoise.c:stop_kthread
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3c28)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
  - kernel/trace/trace_events_user.c:delayed_destroy_user_event
```
```
In kernel/trace/bpf_trace.c (ffffffff812ea606)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_dealloc
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
```
In kernel/bpf/syscall.c (ffffffff8130be21)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/helpers.c (ffffffff813434b6)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_obj_drop_impl
```
```
In kernel/bpf/task_iter.c (ffffffff81349a1c)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8136916d)
Location: include/linux/refcount.h:259
Inline: True
```
```
In kernel/bpf/dispatcher.c (ffffffff81373d11)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/net_namespace.c (ffffffff8137b3bd)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In kernel/bpf/cpumask.c (ffffffff813863a5)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_release
```
```
In kernel/events/core.c (ffffffff813a4711)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff813a9485)
Location: include/linux/refcount.h:259
Inline: True
```
```
In kernel/padata.c (ffffffff813ae4c8)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
```
In kernel/watch_queue.c (ffffffff813b3557)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_free
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/backing-dev.c (ffffffff813f5982)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/process_vm_access.c (ffffffff8144549a)
Location: include/linux/refcount.h:259
Inline: True
```
```
In mm/madvise.c (ffffffff81462ee5)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/page_io.c (ffffffff81463691)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_bdev_sync
```
```
In mm/zswap.c (ffffffff8147097d)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:__hugetlb_zap_end
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:clear_vma_resv_huge_pages
```
```
In mm/mempolicy.c (ffffffff814845f8)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff814963f0)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-tiers.c (ffffffff8149c335)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - mm/memory-tiers.c:clear_node_memory_type
```
```
In mm/huge_memory.c (ffffffff814a7ccc)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memcontrol.c (ffffffff814b7ff1)
Location: include/linux/refcount.h:259
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c4119)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/super.c (ffffffff814e3a6e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/super.c:destroy_super_work
```
```
In fs/exec.c (ffffffff814eacc7)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/namei.c (ffffffff814f1d20)
Location: include/linux/refcount.h:259
Inline: True
```
```
In fs/inode.c (ffffffff81509ad6)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/namespace.c (ffffffff8151248d)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/namespace.c:finish_mount_kattr
  - fs/namespace.c:free_mnt_ns
```
```
In fs/fs_context.c (ffffffff81538bdd)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/mnt_idmapping.c (ffffffff8153b9c6)
Location: include/linux/refcount.h:259
Inline: True
```
```
In fs/proc_namespace.c (ffffffff81543c2e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff815480d5)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffffffff81548a22)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventpoll.c (ffffffff81551a25)
Location: include/linux/refcount.h:259
Inline: True
```
```
In fs/eventfd.c (ffffffff81557d99)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffff81558865)
Location: include/linux/refcount.h:259
Inline: True
```
```
In fs/aio.c (ffffffff81560f2b)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
```
```
In fs/backing-file.c (ffffffff81581745)
Location: include/linux/refcount.h:259
Inline: True
```
```
In fs/posix_acl.c (ffffffff81584d4a)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffff815a5e79)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
```
```
In fs/proc/fd.c (ffffffff815ad908)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff815b4f1d)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff815c65a5)
Location: include/linux/refcount.h:259
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff815e049b)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/page-io.c (ffffffff81612ef5)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
```
```
In fs/ext4/acl.c (ffffffff8164a835)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In fs/hugetlbfs/inode.c (ffffffff81667231)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/fuse/dev.c (ffffffff8168b3eb)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In fs/fuse/file.c (ffffffff816996e7)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (ffffffff8169d1b3)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/fuse/inode.c:delayed_release
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/dax.c (ffffffff816a4122)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_end
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In fs/debugfs/inode.c (ffffffff816a6017)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff816a8372)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In fs/tracefs/event_inode.c (ffffffff816abac7)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_remove_rec
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/tracefs/event_inode.c:eventfs_create_dir
  - fs/tracefs/event_inode.c:eventfs_d_release
```
```
In ipc/util.c (ffffffff816b1705)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffff816b9a74)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (ffffffff816c1610)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff816c1bc7)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipc
```
```
In security/keys/key.c (ffffffff816c2efa)
Location: include/linux/refcount.h:259
Inline: True
```
```
In security/keys/keyring.c (ffffffff816c63bf)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/selinux/netlabel.c (ffffffff8170dbd2)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/apparmor/apparmorfs.c (ffffffff81734e24)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
```
```
In security/apparmor/capability.c (ffffffff817378e8)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff81739132)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/domain.c (ffffffff8174288b)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8392c107)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755b3d)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffff8392c475)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff817594c3)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffff8175ea6e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81761b6c)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
```
```
In security/landlock/ruleset.c (ffffffff8176be5e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
  - security/landlock/ruleset.c:free_ruleset
```
```
In crypto/api.c (ffffffff8177f154)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff81780d21)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff8178dd90)
Location: include/linux/refcount.h:259
Inline: True
```
```
In block/blk-core.c (ffffffff817b2dc5)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_put_queue
```
```
In block/bsg-lib.c (ffffffff817e2585)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffff817e5fe5)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In io_uring/io_uring.c (ffffffff818112d9)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_put_task_remote
```
```
In io_uring/net.c (ffffffff8181ce4a)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
```
```
In io_uring/sqpoll.c (ffffffff8181fec5)
Location: include/linux/refcount.h:259
Inline: True
```
```
In io_uring/notif.c (ffffffff8182a393)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - io_uring/notif.c:io_tx_ubuf_callback_ext
```
```
In io_uring/io-wq.c (ffffffff8182e97f)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_worker_release
```
```
In rust/helpers.c (ffffffff81842855)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_put_task_struct
  - rust/helpers.c:rust_helper_refcount_dec_and_test
```
```
In lib/refcount.c (ffffffff8185ffda)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff81925ac2)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In lib/stackdepot.c (ffffffff8192857d)
Location: include/linux/refcount.h:259
Inline: True
```
```
In drivers/pinctrl/core.c (ffffffff8193542e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a4ecc)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff819f7dae)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff81a92a65)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff81a99978)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac7232)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/reset/core.c (ffffffff81ae3843)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_put_internal
```
```
In drivers/tty/tty_io.c (ffffffff81ae9e56)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffffffff8223c1f6)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/char/virtio_console.c (ffffffff81b37a1d)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a8d2)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b80df4)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_unbind_device
```
```
In drivers/connector/cn_queue.c (ffffffff81b81e35)
Location: include/linux/refcount.h:259
Inline: True
```
```
In drivers/base/core.c (ffffffff81b87ae3)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb30eb)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81bf6583)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfafff)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffff81c0e7bd)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/dax/bus.c:__free_dev_dax_id
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c1228e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14b54)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15080)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1aa20)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2d2d8)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c31085)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
```
In drivers/scsi/sg.c (ffffffff81c499ba)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7a585)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_default_clear
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_default_clear
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7df4f)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7eeee)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_master_release
  - drivers/gpu/drm/drm_auth.c:drm_master_release
  - drivers/gpu/drm/drm_auth.c:drm_dropmaster_ioctl
  - drivers/gpu/drm/drm_auth.c:drm_new_set_master
```
```
In drivers/gpu/drm/drm_client.c (ffffffff81c81c48)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client.c:drm_client_buffer_delete
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c82674)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_commit_atomic
```
```
In drivers/gpu/drm/drm_color_mgmt.c (ffffffff81c85085)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_color_mgmt.c:drm_crtc_legacy_gamma_set
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87582)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:__drm_connector_put_safe
  - drivers/gpu/drm/drm_connector.c:drm_connector_cleanup
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c32b)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:devm_drm_dev_init_release
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97314)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_send_event_helper
  - drivers/gpu/drm/drm_file.c:drm_event_cancel_free
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9992d)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:atomic_remove_fb
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c4c4)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_obj_set_property_ioctl
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81caca39)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_mmap
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_fd_to_handle
  - drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_release
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb20a7)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_signal_completion
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_cleanup_job
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (ffffffff81cbe374)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_dumb_create
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc35ab)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_damage_helper.c:drm_atomic_helper_dirtyfb
```
```
In drivers/gpu/drm/drm_gem_atomic_helper.c (ffffffff81ccb1e6)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
```
```
In drivers/gpu/drm/drm_gem_framebuffer_helper.c (ffffffff81ccc097)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_destroy
```
```
In drivers/gpu/drm/drm_self_refresh_helper.c (ffffffff81ccfb22)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_entry_work
```
```
In drivers/gpu/drm/drm_fb_helper.c (ffffffff81cd3735)
Location: include/linux/refcount.h:259
Inline: True
```
```
In drivers/net/netkit.c (ffffffff81ce5cb5)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
```
```
In drivers/net/pse-pd/pse_core.c (ffffffff81cf7d1f)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/net/pse-pd/pse_core.c:pse_control_put
```
```
In drivers/net/tun.c (ffffffff81cfc6d1)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18841)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/core/hub.c (ffffffff81d36eae)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81d39622)
Location: include/linux/refcount.h:259
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81d3db71)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81d3fd40)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff81d46a45)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/md/dm.c (ffffffff81e30780)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_put_table_device
```
```
In drivers/md/dm-table.c (ffffffff81e32b5e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/edac/ghes_edac.c (ffffffff83d51806)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
```
```
In drivers/nvmem/core.c (ffffffff81eb1073)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb6ea9)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_put
  - drivers/dpll/dpll_core.c:dpll_device_put
```
```
In net/core/sock.c (ffffffff81ec76aa)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81ed073c)
Location: include/linux/refcount.h:259
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
In net/core/datagram.c (ffffffff81edd4ad)
Location: include/linux/refcount.h:259
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81ee30e2)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/dst.c (ffffffff81f03885)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81f0a09f)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/flow_offload.c (ffffffff81f3a943)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
```
```
In net/core/gro.c (ffffffff81f3b8bb)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/core/gro.c:napi_reuse_skb
```
```
In net/core/page_pool.c (ffffffff81f44c52)
Location: include/linux/refcount.h:259
Inline: True
```
```
In net/core/netpoll.c (ffffffff81f47aea)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffff81f4b3fe)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/core/skmsg.c (ffffffff81f6383f)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/sock_map.c (ffffffff81f68c79)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81f6fac2)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffff81f7b5e5)
Location: include/linux/refcount.h:259
Inline: True
```
```
In net/sched/act_api.c (ffffffff81f84263)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
```
```
In net/netlink/af_netlink.c (ffffffff81f89f33)
Location: include/linux/refcount.h:259
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
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81fb0db6)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffff81fb6e43)
Location: include/linux/refcount.h:259
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81fb8228)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9ae5)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_output.c (ffffffff81fbcc88)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc0da7)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc5315)
Location: include/linux/refcount.h:259
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8a65)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcafc5)
Location: include/linux/refcount.h:259
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
In net/ipv4/tcp.c (ffffffff81fd406c)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81fdda0f)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81fecdbe)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee39e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff26e7)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe3f8)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff82003840)
Location: include/linux/refcount.h:259
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82005a9e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_realloc_batch
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_next
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/udp_offload.c (ffffffff8200c8fc)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff820105ca)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff82015c3d)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff8201e45a)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff82026823)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff82030747)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (ffffffff82032a87)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/nexthop.c (ffffffff8203d405)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffff82048c96)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/syncookies.c (ffffffff8204b77f)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_release
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204ecf8)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8204fd98)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff820529d1)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/ipv4/tcp_ao.c (ffffffff8205633d)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_destroy_sock
```
```
In net/xfrm/xfrm_policy.c (ffffffff820648ac)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff820712be)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_state_bpf.c (ffffffff82075f35)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_xfrm_state_release
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_get_xfrm_state
```
```
In net/unix/af_unix.c (ffffffff82077d14)
Location: include/linux/refcount.h:259
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
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/unix_bpf.c (ffffffff8207e31d)
Location: include/linux/refcount.h:259
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff8207fe6c)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
```
```
In net/ipv6/anycast.c (ffffffff82081238)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/ip6_output.c (ffffffff8208309d)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff82088465)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff82095777)
Location: include/linux/refcount.h:259
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
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff8209e4ef)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff820b1fb1)
Location: include/linux/refcount.h:259
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
```
```
In net/ipv6/udp.c (ffffffff820b7d0f)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff820c3849)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_gq_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
```
```
In net/ipv6/reassembly.c (ffffffff820c7898)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd82d)
Location: include/linux/refcount.h:259
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
In net/ipv6/ip6mr.c (ffffffff820dde00)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0a2e)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e10a3)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffff820e587d)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff820e689d)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/seg6_local.c (ffffffff820eae6b)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/packet/af_packet.c (ffffffff820f86e3)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/devlink/core.c (ffffffff820fec95)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/devlink/core.c:__devlink_rel_put
```
```
In net/devlink/dev.c (ffffffff82104532)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
```
```
In net/xdp/xsk.c (ffffffff8213e5bb)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff8214068f)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142dd3)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff8214d397)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_tout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff8214f225)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c4f0)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
```
```
In net/mptcp/pm_userspace.c (ffffffff821617b7)
Location: include/linux/refcount.h:259
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
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
```
```
In net/mctp/device.c (ffffffff82164ccb)
Location: include/linux/refcount.h:259
Inline: True
```
```
In net/mctp/route.c (ffffffff82165c05)
Location: include/linux/refcount.h:259
Inline: True
```
```
In net/handshake/request.c (ffffffff8216a0fb)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
```
```
In lib/klist.c (ffffffff82179c69)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffff8217acc7)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In lib/objpool.c (ffffffff82191def)
Location: include/linux/refcount.h:259
Inline: True
Inline callers:
  - lib/objpool.c:objpool_drop
```
**Symbols:**

```
ffffffff81d17b60-ffffffff81d17ba0: __refcount_sub_and_test.constprop.0 (STB_LOCAL)
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
