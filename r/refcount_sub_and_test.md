# Function: <code>refcount_sub_and_test</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b5909)
Location: include/linux/refcount.h:76
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81832187)
Location: include/linux/refcount.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
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
In net/core/sock.c (ffffffff8182ddfa)
Location: arch/x86/include/asm/refcount.h:67
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff818b19c7)
Location: arch/x86/include/asm/refcount.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1fba)
Location: arch/x86/include/asm/refcount.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
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
In net/core/sock.c (ffffffff818781da)
Location: arch/x86/include/asm/refcount.h:67
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81907054)
Location: arch/x86/include/asm/refcount.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff81917c3d)
Location: arch/x86/include/asm/refcount.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81921019)
Location: arch/x86/include/asm/refcount.h:67
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In mm/memcontrol.c (ffffffff812944c5)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
```
```
In net/core/sock.c (ffffffff818986ba)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81934c44)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff8194636b)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8194fb83)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
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
In mm/memcontrol.c (ffffffff812b1055)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
```
```
In net/core/sock.c (ffffffff818e2c79)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81998a06)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa9a4)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819b4401)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff819cef61)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In mm/memcontrol.c (ffffffff812c2ab5)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
```
```
In net/core/sock.c (ffffffff81914e59)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff819cf537)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1674)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819eb131)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05b01)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In arch/x86/kernel/ioport.c (ffffffff8103715c)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_exit
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056c28)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061bd8)
Location: include/linux/refcount.h:264
Inline: True
```
```
In kernel/fork.c (ffffffff810a5214)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/fork.c:wait_for_vfork_done
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:put_task_stack
```
```
In kernel/exit.c (ffffffff810ac4b0)
Location: include/linux/refcount.h:264
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
In kernel/ptrace.c (ffffffff810b5fd3)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810c406a)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810cd927)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff810d0a99)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810d5d46)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
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
In kernel/smpboot.c (ffffffff810d917e)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (ffffffff810e55b8)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff810f3451)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f9327)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810fb034)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/autogroup.c (ffffffff811050c6)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff8110dd5b)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f53e)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff811104ae)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811256ad)
Location: include/linux/refcount.h:264
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
In kernel/rcu/update.c (ffffffff81131185)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/kcmp.c (ffffffff8113fed4)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/namespace.c (ffffffff8115a537)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_put
```
```
In kernel/futex.c (ffffffff8115ccc6)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff811771bb)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
```
```
In kernel/cgroup/namespace.c (ffffffff8117912e)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117a84c)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff8118363d)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff811851ca)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
```
In kernel/audit.c (ffffffff811866eb)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/auditfilter.c (ffffffff8118c08f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff811915f5)
Location: include/linux/refcount.h:264
Inline: True
```
```
In kernel/audit_tree.c (ffffffff811944ce)
Location: include/linux/refcount.h:264
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
In kernel/hung_task.c (ffffffff811a4327)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff811a63dc)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
```
```
In kernel/relay.c (ffffffff811a8ba2)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffff811aa5e4)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_pid
```
```
In kernel/trace/trace.c (ffffffff811bb4b0)
Location: include/linux/refcount.h:264
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cae7f)
Location: include/linux/refcount.h:264
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fc71b)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff81216745)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
```
```
In kernel/bpf/trampoline.c (ffffffff8121f0b8)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
```
In kernel/bpf/btf.c (ffffffff81222fcd)
Location: include/linux/refcount.h:264
Inline: True
```
```
In kernel/bpf/dispatcher.c (ffffffff8122628f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/net_namespace.c (ffffffff8122ad14)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81230195)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_delete_elem
```
```
In kernel/events/core.c (ffffffff81242a66)
Location: include/linux/refcount.h:264
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
In kernel/events/ring_buffer.c (ffffffff81243d85)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (ffffffff81245c75)
Location: include/linux/refcount.h:264
Inline: True
```
```
In kernel/watch_queue.c (ffffffff8124d478)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/oom_kill.c (ffffffff81256bda)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
```
```
In mm/backing-dev.c (ffffffff812783d8)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
```
In mm/process_vm_access.c (ffffffff812acfba)
Location: include/linux/refcount.h:264
Inline: True
```
```
In mm/page_io.c (ffffffff812b7dab)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff812c23d9)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff812c7dbb)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
```
```
In mm/mempolicy.c (ffffffff812cd1cc)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812e7414)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memcontrol.c (ffffffff812f7575)
Location: include/linux/refcount.h:264
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130022b)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/namei.c (ffffffff813218c8)
Location: include/linux/refcount.h:264
Inline: True
```
```
In fs/inode.c (ffffffff813354ee)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/fs_context.c (ffffffff81357560)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/proc_namespace.c (ffffffff8136607e)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff81366ef5)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffffffff813678a3)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventfd.c (ffffffff81371a0b)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffff813724a5)
Location: include/linux/refcount.h:264
Inline: True
```
```
In fs/aio.c (ffffffff81378299)
Location: include/linux/refcount.h:264
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
In fs/io_uring.c (ffffffff81385ddd)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_put_req
  - fs/io_uring.c:__io_fail_links
  - fs/io_uring.c:__io_req_aux_free
```
```
In fs/io-wq.c (ffffffff8138b685)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_destroy
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_worker_exit
  - fs/io-wq.c:io_worker_exit
```
```
In fs/crypto/keyring.c (ffffffff813926f7)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff8139335d)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/posix_acl.c (ffffffff813a6da5)
Location: include/linux/refcount.h:264
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
In fs/proc/task_mmu.c (ffffffff813b70ee)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813bca0a)
Location: include/linux/refcount.h:264
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
  - fs/proc/base.c:proc_setgroups_open
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
In fs/proc/generic.c (ffffffff813c0f35)
Location: include/linux/refcount.h:264
Inline: True
```
```
In fs/proc/fd.c (ffffffff813c3848)
Location: include/linux/refcount.h:264
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
In fs/proc/namespaces.c (ffffffff813c6214)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff813c9c90)
Location: include/linux/refcount.h:264
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
In fs/configfs/item.c (ffffffff813d79f6)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
```
In fs/ext4/ialloc.c (ffffffff813edadf)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/acl.c (ffffffff8143ba62)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
```
```
In fs/hugetlbfs/inode.c (ffffffff81450976)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/dev.c (ffffffff8146e465)
Location: include/linux/refcount.h:264
Inline: True
```
```
In fs/fuse/file.c (ffffffff8147a41b)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (ffffffff8147cd15)
Location: include/linux/refcount.h:264
Inline: True
```
```
In fs/debugfs/inode.c (ffffffff81481194)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff8148249f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In ipc/util.c (ffffffff814871b5)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffff8148e4e2)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In security/keys/key.c (ffffffff81495ec5)
Location: include/linux/refcount.h:264
Inline: True
```
```
In security/keys/keyring.c (ffffffff81498bbf)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/selinux/netlabel.c (ffffffff814d16ba)
Location: include/linux/refcount.h:264
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
In security/smack/smack_lsm.c (ffffffff814d691f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/apparmor/apparmorfs.c (ffffffff814ec3a7)
Location: include/linux/refcount.h:264
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
  - security/apparmor/apparmorfs.c:ns_revision_open
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
In security/apparmor/audit.c (ffffffff814f08d4)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_rule_free
```
```
In security/apparmor/capability.c (ffffffff814f0bcf)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff814f14f3)
Location: include/linux/refcount.h:264
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
In security/apparmor/lib.c (ffffffff814f2a43)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff814f2d5a)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff814f965a)
Location: include/linux/refcount.h:264
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
In security/apparmor/policy.c (ffffffff814fc399)
Location: include/linux/refcount.h:264
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
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:update_to_newest_parent
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
In security/apparmor/policy_unpack.c (ffffffff814fefc6)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff814ff234)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8150530c)
Location: include/linux/refcount.h:264
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
In security/apparmor/resource.c (ffffffff8150589e)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81507407)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffff81508084)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff8150cba0)
Location: include/linux/refcount.h:264
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
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_proxy_kref
```
```
In security/apparmor/mount.c (ffffffff8150e8ff)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffff8150f41c)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff815114cd)
Location: include/linux/refcount.h:264
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
In security/yama/yama_lsm.c (ffffffff81512044)
Location: include/linux/refcount.h:264
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
In crypto/api.c (ffffffff8151e75a)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff815211ef)
Location: include/linux/refcount.h:264
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
In crypto/algboss.c (ffffffff81528b30)
Location: include/linux/refcount.h:264
Inline: True
```
```
In crypto/rng.c (ffffffff81532ebd)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
```
```
In block/blk-flush.c (ffffffff8154800b)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8154f4e6)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/bsg.c (ffffffff81568aff)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - block/bsg.c:bsg_put_device
```
```
In block/bsg-lib.c (ffffffff81569905)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffff8156bd21)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In lib/refcount.c (ffffffff8158f8e0)
Location: include/linux/refcount.h:264
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815df6d0)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In lib/klist.c (ffffffff815ea6a9)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffff815eae99)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In drivers/pinctrl/core.c (ffffffff81602d7e)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81652eb0)
Location: include/linux/refcount.h:264
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
In drivers/acpi/ec.c (ffffffff8168f6c0)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff81702775)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff8170750f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171f992)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/reset/core.c (ffffffff81732cb2)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_array_put
```
```
In drivers/tty/tty_io.c (ffffffff817352ca)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
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
In drivers/tty/tty_port.c (ffffffff8173f942)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/tty/tty_ldsem.c (ffffffff81bcc027)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/char/virtio_console.c (ffffffff8177655f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff817792f2)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
```
In drivers/connector/cn_queue.c (ffffffff817aca35)
Location: include/linux/refcount.h:264
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff817af565)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_register
  - drivers/lightnvm/core.c:nvm_register
```
```
In drivers/base/core.c (ffffffff817b362a)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d53dc)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff8180eda3)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81812d4f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffff818243fe)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81825e66)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8182766f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827a50)
Location: include/linux/refcount.h:264
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
In drivers/dma-buf/dma-resv.c (ffffffff8182973d)
Location: include/linux/refcount.h:264
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182ab99)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182c0b9)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8183a5f5)
Location: include/linux/refcount.h:264
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8184a984)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (ffffffff8184dff8)
Location: include/linux/refcount.h:264
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
In drivers/ata/libata-core.c (ffffffff81853091)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/net/tun.c (ffffffff8188b94d)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81891cfa)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/vfio/vfio.c (ffffffff8189b55f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189ed5d)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
```
In drivers/usb/core/hub.c (ffffffff818b9667)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818bc022)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818c051a)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff818c1b40)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff818c723b)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff818c8653)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/md/dm.c (ffffffff819774a0)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_put_table_device
```
```
In drivers/md/dm-table.c (ffffffff8197c46f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/edac/ghes_edac.c (ffffffff8198d6a0)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_unregister
```
```
In drivers/opp/core.c (ffffffff8198f159)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all_static
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9c1d)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819cd324)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
```
In drivers/nvmem/core.c (ffffffff819da725)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
```
In net/core/sock.c (ffffffff819e6d28)
Location: include/linux/refcount.h:264
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
In net/core/request_sock.c (ffffffff819e982a)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff819ebf7a)
Location: include/linux/refcount.h:264
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
In net/core/datagram.c (ffffffff819f4f17)
Location: include/linux/refcount.h:264
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f8d0f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a0493d)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81a10adb)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81a15e24)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_rcu_free_parms
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81a20fdd)
Location: include/linux/refcount.h:264
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
In net/core/filter.c (ffffffff81a2ba27)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/filter.c:sk_select_reuseport
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/flow_offload.c (ffffffff81a36b6b)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_unregister
```
```
In net/core/page_pool.c (ffffffff81a3ad02)
Location: include/linux/refcount.h:264
Inline: True
```
```
In net/core/skmsg.c (ffffffff81a3bef3)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff81a3dffa)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffff81a414f9)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_cleanup_ops
```
```
In net/core/sock_map.c (ffffffff81a4e6a0)
Location: include/linux/refcount.h:264
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
In net/core/devlink.c (ffffffff81a5db68)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_netns_get
```
```
In net/core/bpf_sk_storage.c (ffffffff81a611d6)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81a64d46)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffff81a6e425)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_put
```
```
In net/sched/act_api.c (ffffffff81a72df1)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_delete_index
  - net/sched/act_api.c:tcf_del_walker
```
```
In net/netlink/af_netlink.c (ffffffff81a78887)
Location: include/linux/refcount.h:264
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
In net/netfilter/nf_queue.c (ffffffff81a8f663)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81a91834)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffff81a97413)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/ip_fragment.c (ffffffff81a994c5)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa07a8)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3055)
Location: include/linux/refcount.h:264
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4cd5)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa64b8)
Location: include/linux/refcount.h:264
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
In net/ipv4/tcp.c (ffffffff81aae168)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ab464d)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81ac13ae)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac222f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8cbd)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9aad)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acd23e)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81ad75f7)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8e21)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff81ada2af)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81adf8d4)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81ae8f31)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aed832)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5a81)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (ffffffff81af8385)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff81afce37)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:nexthop_add
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
```
In net/ipv4/fib_rules.c (ffffffff81aff7e6)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffff81b03ed7)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/ipv4/syncookies.c (ffffffff81b07956)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b09463)
Location: include/linux/refcount.h:264
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
In net/ipv4/cipso_ipv4.c (ffffffff81b0b2ab)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b0c4b0)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b16286)
Location: include/linux/refcount.h:264
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
In net/xfrm/xfrm_state.c (ffffffff81b184dd)
Location: include/linux/refcount.h:264
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
In net/unix/af_unix.c (ffffffff81b24b3a)
Location: include/linux/refcount.h:264
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
In net/ipv6/af_inet6.c (ffffffff81b2ab1c)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/anycast.c (ffffffff81b2b89b)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81b3c7fd)
Location: include/linux/refcount.h:264
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
In net/ipv6/route.c (ffffffff81b44055)
Location: include/linux/refcount.h:264
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
In net/ipv6/ip6_fib.c (ffffffff81b4eeea)
Location: include/linux/refcount.h:264
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
In net/ipv6/ipv6_sockglue.c (ffffffff81b508b4)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81b54568)
Location: include/linux/refcount.h:264
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
In net/ipv6/udp.c (ffffffff81b58896)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81b5cdd0)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff81b62ee7)
Location: include/linux/refcount.h:264
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
In net/ipv6/reassembly.c (ffffffff81b663c3)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a87b)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81b755b7)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b784e6)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78821)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffff81b7bf6c)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b7cd22)
Location: include/linux/refcount.h:264
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
In net/packet/af_packet.c (ffffffff81b8b5a7)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba7719)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff81ba8c1f)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/mptcp/protocol.c (ffffffff81babfaa)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff81baea59)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/subflow.c:subflow_req_destructor
```
```
In net/mptcp/pm.c (ffffffff81bb296c)
Location: include/linux/refcount.h:264
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_close
  - net/mptcp/pm.c:pm_worker
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
In kernel/kprobes.c (ffffffff81193ad0)
Location: include/linux/refcount.h:308
Inline: True
```
```
In mm/memcontrol.c (ffffffff813033f1)
Location: include/linux/refcount.h:308
Inline: True
```
```
In fs/io_uring.c (ffffffff81399a26)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
```
```
In net/core/sock.c (ffffffff819e7a33)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7329)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5354)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81b025b8)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In kernel/kprobes.c (ffffffff81194ab0)
Location: include/linux/refcount.h:308
Inline: True
```
```
In mm/memcontrol.c (ffffffff81309911)
Location: include/linux/refcount.h:308
Inline: True
```
```
In fs/io_uring.c (ffffffff8139510a)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_work
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_complete_post
```
```
In net/core/sock.c (ffffffff819cda03)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2349)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ad066d)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedec8)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In kernel/kprobes.c (ffffffff811bd9c0)
Location: include/linux/refcount.h:308
Inline: True
```
```
In kernel/padata.c (ffffffff812948b3)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/memcontrol.c (ffffffff81353151)
Location: include/linux/refcount.h:308
Inline: True
```
```
In fs/io_uring.c (ffffffff813e87b9)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_uring_drop_tctx_refs
```
```
In net/core/sock.c (ffffffff81a7d213)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f1c9)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f08b)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae278)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In kernel/trace/rethook.c (ffffffff81268da1)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_free_rcu
```
```
In kernel/padata.c (ffffffff812e9af1)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/memcontrol.c (ffffffff813cdc51)
Location: include/linux/refcount.h:308
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81e8f860)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:__io_put_task
```
```
In net/core/sock.c (ffffffff81bf0803)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81cfe839)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff81d14d14)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81d1fd25)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81d413e6)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In kernel/trace/rethook.c (ffffffff812bb081)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_free_rcu
```
```
In kernel/padata.c (ffffffff81353931)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/memcontrol.c (ffffffff81452311)
Location: include/linux/refcount.h:308
Inline: True
```
```
In io_uring/io_uring.c (ffffffff8178a984)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:__io_put_task
```
```
In net/core/sock.c (ffffffff81d9cda3)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3759)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff81edae54)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6f15)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a1b1)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In kernel/trace/rethook.c (ffffffff812dec81)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_free_rcu
```
```
In kernel/padata.c (ffffffff81384b31)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/memcontrol.c (ffffffff81487e21)
Location: include/linux/refcount.h:308
Inline: True
```
```
In io_uring/io_uring.c (ffffffff817cb424)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
```
```
In net/core/sock.c (ffffffff81e0b5f3)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81f21999)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81f467bc)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69ce1)
Location: include/linux/refcount.h:308
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In kernel/padata.c (ffffffff813adf41)
Location: include/linux/refcount.h:297
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/memcontrol.c (ffffffff814b7ff1)
Location: include/linux/refcount.h:297
Inline: True
```
```
In io_uring/io_uring.c (ffffffff8180f914)
Location: include/linux/refcount.h:297
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
```
```
In net/core/sock.c (ffffffff81ec7fe3)
Location: include/linux/refcount.h:297
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5929)
Location: include/linux/refcount.h:297
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/refcount.h:297
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8200c8fc)
Location: include/linux/refcount.h:297
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff82030361)
Location: include/linux/refcount.h:297
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In lib/objpool.c (ffffffff82191e88)
Location: include/linux/refcount.h:297
Inline: True
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
In mm/memcontrol.c (c000000000451d18)
Location: include/linux/refcount.h:94
Inline: True
```
```
In net/core/sock.c (c000000000c83594)
Location: include/linux/refcount.h:94
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (c000000000d8d2f0)
Location: include/linux/refcount.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (c000000000da6774)
Location: include/linux/refcount.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (c000000000db36c8)
Location: include/linux/refcount.h:94
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (c000000000dd9094)
Location: include/linux/refcount.h:94
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In mm/memcontrol.c (ffffffe0002438de)
Location: include/linux/refcount.h:94
Inline: True
```
```
In net/core/sock.c (ffffffe00073fd24)
Location: include/linux/refcount.h:94
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3ed2)
Location: include/linux/refcount.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f48c2)
Location: include/linux/refcount.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd340)
Location: include/linux/refcount.h:94
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffe0008148cc)
Location: include/linux/refcount.h:94
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In mm/memcontrol.c (ffffffff812bb095)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
```
```
In net/core/sock.c (ffffffff818b4e59)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff8196f3a7)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff819814e4)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8198afa1)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff819a58a1)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In mm/memcontrol.c (ffffffff812ac215)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
```
```
In net/core/sock.c (ffffffff8186eda9)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81928e97)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff8193afa4)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81944a61)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f361)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In mm/memcontrol.c (ffffffff812b8ea5)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
```
```
In net/core/sock.c (ffffffff81905e59)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff819d9b77)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff819ebcb4)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819f5771)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10141)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In mm/memcontrol.c (ffffffff812c94c5)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
```
```
In net/core/sock.c (ffffffff81926e89)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff819e37d7)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5b64)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819ff971)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1a991)
Location: arch/x86/include/asm/refcount.h:68
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
</details>
</li>
</ul>

## Differences
