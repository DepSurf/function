# Function: <code>put_task_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810803cd)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810822e5)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/exit.c:delayed_put_task_struct
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff8108c291)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/ptrace.c:SyS_ptrace
  - kernel/ptrace.c:compat_SyS_ptrace
```
```
In kernel/sys.c (ffffffff810958a2)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prlimit64
```
```
In kernel/kthread.c (ffffffff810a0847)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810a3ae1)
Location: include/linux/sched.h:2028
Inline: True
```
```
In kernel/sched/core.c (ffffffff810a95c2)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810b571f)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810c0ade)
Location: include/linux/sched.h:2028
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c26c2)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/locking/rtmutex.c (ffffffff810cb05b)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810cbb3c)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__rwsem_do_wake
```
```
In kernel/irq/manage.c (ffffffff810db7d3)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/kcmp.c (ffffffff810e985e)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f272a)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/futex.c (ffffffff81101689)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup.c (ffffffff81117064)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:css_task_iter_next
  - kernel/cgroup.c:css_task_iter_end
  - kernel/cgroup.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8113a55e)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff8113e9ba)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8115728a)
Location: include/linux/sched.h:2028
Inline: True
```
```
In kernel/events/core.c (ffffffff8117b2ff)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In mm/oom_kill.c (ffffffff811906a0)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff811d0ad7)
Location: include/linux/sched.h:2028
Inline: True
```
```
In mm/mempolicy.c (ffffffff811e17ea)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/mempolicy.c:SyS_migrate_pages
```
```
In mm/migrate.c (ffffffff811f2b71)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:SyS_move_pages
```
```
In mm/memcontrol.c (ffffffff811fea25)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/memory-failure.c (ffffffff81202be2)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc_namespace.c (ffffffff8124f10a)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81277131)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8127acd1)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:oom_adj_write
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_pid_readdir
```
```
In fs/proc/fd.c (ffffffff8128149e)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
```
```
In fs/proc/namespaces.c (ffffffff81283715)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_follow_link
  - fs/proc/namespaces.c:proc_ns_dir_lookup
```
```
In security/yama/yama_lsm.c (ffffffff81395432)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:yama_task_prctl
```
```
In drivers/tty/tty_ldsem.c (ffffffff814ebcaf)
Location: include/linux/sched.h:2028
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff811906a0-ffffffff811906b2: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81082202)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81085c5a)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff8108f6cb)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
```
In kernel/sys.c (ffffffff81098c42)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prlimit64
```
```
In kernel/kthread.c (ffffffff810a3f37)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810a7201)
Location: include/linux/sched.h:2167
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b0845)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
```
```
In kernel/sched/fair.c (ffffffff810b87a6)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810c456e)
Location: include/linux/sched.h:2167
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c623a)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/locking/rtmutex.c (ffffffff810cfb75)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff810e10e0)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff810e95bf)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff810f05c1)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f982e)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/futex.c (ffffffff81108c2b)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup.c (ffffffff81120c85)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:css_task_iter_end
  - kernel/cgroup.c:css_task_iter_next
```
```
In kernel/hung_task.c (ffffffff81142a87)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff81146fea)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161b0a)
Location: include/linux/sched.h:2167
Inline: True
```
```
In kernel/events/core.c (ffffffff811966b9)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/oom_kill.c (ffffffff811a5108)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/process_vm_access.c (ffffffff811edc58)
Location: include/linux/sched.h:2167
Inline: True
```
```
In mm/mempolicy.c (ffffffff812001ca)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/mempolicy.c:SyS_migrate_pages
```
```
In mm/migrate.c (ffffffff812127fd)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:SyS_move_pages
```
```
In mm/memcontrol.c (ffffffff81222841)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/memory-failure.c (ffffffff81227239)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc_namespace.c (ffffffff8127788a)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff812a36a8)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff812a88a2)
Location: include/linux/sched.h:2167
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff812ae6f0)
Location: include/linux/sched.h:2167
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
In fs/proc/namespaces.c (ffffffff812b093b)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff813d0e71)
Location: include/linux/sched.h:2167
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
In drivers/tty/tty_ldsem.c (ffffffff8189e956)
Location: include/linux/sched.h:2167
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
**Symbols:**

```
ffffffff811a4820-ffffffff811a4832: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810441a5)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff81086c62)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108abca)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff8109464b)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
```
In kernel/sys.c (ffffffff8109dbf2)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prlimit64
```
```
In kernel/kthread.c (ffffffff810a9585)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810acd16)
Location: include/linux/sched.h:2254
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b69d1)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
```
```
In kernel/sched/fair.c (ffffffff810bf380)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810ca5ca)
Location: include/linux/sched.h:2254
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cc1ff)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/locking/rtmutex.c (ffffffff810d6557)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff810e7a5a)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff810f0486)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff810f7721)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811071be)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/futex.c (ffffffff8111041b)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup.c (ffffffff811291b0)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:css_task_iter_end
  - kernel/cgroup.c:css_task_iter_next
```
```
In kernel/hung_task.c (ffffffff8114c868)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff81150e91)
Location: include/linux/sched.h:2254
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c66a)
Location: include/linux/sched.h:2254
Inline: True
```
```
In kernel/events/core.c (ffffffff811a6448)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/oom_kill.c (ffffffff811b5700)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff811fe566)
Location: include/linux/sched.h:2254
Inline: True
```
```
In mm/mempolicy.c (ffffffff81211e37)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
```
```
In mm/migrate.c (ffffffff812249f2)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/memory-failure.c (ffffffff81239806)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc_namespace.c (ffffffff8128b56a)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff812b9087)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff812be182)
Location: include/linux/sched.h:2254
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff812c40d0)
Location: include/linux/sched.h:2254
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
In fs/proc/namespaces.c (ffffffff812c632b)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff813e8571)
Location: include/linux/sched.h:2254
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
In drivers/tty/tty_ldsem.c (ffffffff818d37f9)
Location: include/linux/sched.h:2254
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
**Symbols:**

```
ffffffff811b4d70-ffffffff811b4d82: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043095)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810839ba)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81087a66)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff81091717)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
```
In kernel/sys.c (ffffffff8109ad91)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prlimit64
```
```
In kernel/kthread.c (ffffffff810a6270)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810a9901)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b2c21)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
```
```
In kernel/sched/fair.c (ffffffff810b9b51)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810c40d3)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c6962)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/locking/rtmutex.c (ffffffff810d569f)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff810e6e8c)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff810f045b)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff810f951d)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81109585)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/futex.c (ffffffff811109eb)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff811280ae)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81129ef3)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8114e7ee)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff81153610)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fa0a)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In kernel/events/core.c (ffffffff811adb75)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/oom_kill.c (ffffffff811bd419)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff81209156)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In mm/page_io.c (ffffffff8120b0c0)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff8121be48)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
```
```
In mm/migrate.c (ffffffff812300d6)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/memory-failure.c (ffffffff81244ce6)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In fs/proc_namespace.c (ffffffff8129836d)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff812c7403)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff812cb956)
Location: include/linux/sched/task.h:93
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff812d14db)
Location: include/linux/sched/task.h:93
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
In fs/proc/namespaces.c (ffffffff812d36a0)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff813f4c9e)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:__report_access
  - security/yama/yama_lsm.c:__report_access
Direct callers:
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffff8190a95c)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff811bc060-ffffffff811bc073: put_task_struct (STB_LOCAL)
ffffffff813f4480-ffffffff813f4493: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046679)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff8108a2a0)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108e7f6)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810985a7)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
```
In kernel/sys.c (ffffffff810a1a71)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prlimit64
```
```
In kernel/kthread.c (ffffffff810ac800)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810b0195)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ba021)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
```
```
In kernel/sched/fair.c (ffffffff810c1c21)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810cbad8)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810ce1aa)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/locking/rtmutex.c (ffffffff810dd58a)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff810ef1a2)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff810fa11f)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff81103f9d)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81114755)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/futex.c (ffffffff8111c83b)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff811345e9)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81136d62)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8115b07e)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff8115fe10)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cafe)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In kernel/events/core.c (ffffffff811c16e5)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
```
In mm/oom_kill.c (ffffffff811d203e)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff81222286)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In mm/page_io.c (ffffffff812245f0)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff81237111)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
```
```
In mm/migrate.c (ffffffff8124dd66)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/memory-failure.c (ffffffff81264bd6)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In fs/proc_namespace.c (ffffffff812bb66d)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff812eb225)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff812f0136)
Location: include/linux/sched/task.h:93
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff812f5cd4)
Location: include/linux/sched/task.h:93
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
In fs/proc/namespaces.c (ffffffff812f7ed0)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff8141cb5e)
Location: include/linux/sched/task.h:93
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
In drivers/tty/tty_ldsem.c (ffffffff81994cc5)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff811d0c90-ffffffff811d0ca3: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048c25)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff8108dabb)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81092390)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff8109ad3a)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810a79e2)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/kthread.c (ffffffff810b3800)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810b6fa5)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c15c5)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
```
```
In kernel/sched/fair.c (ffffffff810c8d76)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810d4257)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810d8016)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (ffffffff810e5c4e)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff810f7339)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8110277a)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff8110ebe8)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81120efb)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/futex.c (ffffffff81128e1f)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff81142d09)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8114555d)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81169cac)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff8116ed9d)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bb6a)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b38b3)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/events/core.c (ffffffff811e1a5f)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In mm/oom_kill.c (ffffffff811f2cb4)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff81244164)
Location: include/linux/sched/task.h:93
Inline: True
```
```
In mm/page_io.c (ffffffff81246af6)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff8125a03c)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff8127186a)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812882f2)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff812e4211)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff813173c3)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8131d0e6)
Location: include/linux/sched/task.h:93
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff81323557)
Location: include/linux/sched/task.h:93
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
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff8144eddb)
Location: include/linux/sched/task.h:93
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
In drivers/tty/tty_ldsem.c (ffffffff819f1279)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In net/xdp/xdp_umem.c (ffffffff819ccc44)
Location: include/linux/sched/task.h:93
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff811d2e40-ffffffff811d2e53: put_task_struct (STB_LOCAL)
ffffffff811f1f30-ffffffff811f1f43: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058bc1)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff81095d4b)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109a697)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810a306a)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810b06f2)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/kthread.c (ffffffff810bcb00)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810c0335)
Location: include/linux/sched/task.h:95
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ca8f5)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
```
```
In kernel/sched/fair.c (ffffffff810d6bda)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810dd767)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810df7b6)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (ffffffff810f11e8)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810f1c0d)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/irq/manage.c (ffffffff81102d00)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8110e182)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff8111a1b3)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112c61b)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/futex.c (ffffffff81133a0b)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff8114e839)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811510d4)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81176b75)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff8117c89d)
Location: include/linux/sched/task.h:95
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119958a)
Location: include/linux/sched/task.h:95
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811c453e)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffffffff811f1ecf)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81204cc9)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff81258864)
Location: include/linux/sched/task.h:95
Inline: True
```
```
In mm/page_io.c (ffffffff8125af24)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff8126decc)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff81285e8a)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff8129d242)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff812f8e91)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff8132e838)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff813343c6)
Location: include/linux/sched/task.h:95
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff8133a477)
Location: include/linux/sched/task.h:95
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
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff8146bdab)
Location: include/linux/sched/task.h:95
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
In drivers/tty/tty_ldsem.c (ffffffff81a2c601)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In net/xdp/xdp_umem.c (ffffffff81a05cf2)
Location: include/linux/sched/task.h:95
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81203d90-ffffffff81203da3: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c16b)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff81099feb)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109f1ec)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810a7c3e)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810b612f)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/kthread.c (ffffffff810c2afb)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810c6442)
Location: include/linux/sched/task.h:112
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d25b0)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff810d9db9)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810e4745)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810e63a0)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (ffffffff810f9a4d)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8110b9f4)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8111781c)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff81124ac8)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81136fdf)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/futex.c (ffffffff8113f02b)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff8115a397)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115cef6)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81183980)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff81189744)
Location: include/linux/sched/task.h:112
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a71aa)
Location: include/linux/sched/task.h:112
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d607a)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffffffff81209aca)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8121c37d)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff8126bf56)
Location: include/linux/sched/task.h:112
Inline: True
```
```
In mm/page_io.c (ffffffff81275f2e)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff812894d5)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812a0afc)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812b8350)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff813194b4)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81357296)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8135c875)
Location: include/linux/sched/task.h:112
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff81362617)
Location: include/linux/sched/task.h:112
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
In fs/proc/namespaces.c (ffffffff813642d7)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff81498da9)
Location: include/linux/sched/task.h:112
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
In drivers/tty/tty_ldsem.c (ffffffff81a9c770)
Location: include/linux/sched/task.h:112
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff8121b1d0-ffffffff8121b1e8: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ca7b)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810a05cb)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a577c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810ae25e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810bc70f)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/kthread.c (ffffffff810c8e6b)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810cf522)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dca20)
Location: include/linux/sched/task.h:116
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
In kernel/sched/fair.c (ffffffff810e4539)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810ef905)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810f1a20)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (ffffffff8110583d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81117df4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff81123bf0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff81130a88)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811430b2)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (ffffffff8114aec4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff81166047)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81168aea)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8118f7f0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff81195684)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b299a)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e2021)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffffffff81216e3a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81229d4d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff8127ad66)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/page_io.c (ffffffff812859fe)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff81299065)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812b1f0c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812ca230)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff8132c2e4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff8136edc9)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff81374e15)
Location: include/linux/sched/task.h:116
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff8137a877)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (ffffffff8137c567)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff814b2c39)
Location: include/linux/sched/task.h:116
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
In drivers/tty/tty_ldsem.c (ffffffff81ad3fc0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3e7d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff81228c90-ffffffff81228ca8: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061bd8)
Location: include/linux/sched/task.h:123
Inline: True
```
```
In kernel/fork.c (ffffffff810a520f)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/fork.c:wait_for_vfork_done
```
```
In kernel/exit.c (ffffffff810ac4b0)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810b5fce)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810c406a)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810cd927)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff810d0a99)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810d917a)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (ffffffff810e55b8)
Location: include/linux/sched/task.h:123
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
In kernel/sched/fair.c (ffffffff810eb9d1)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f9327)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810fb02d)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f53e)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff811104ae)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811256a4)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff81131185)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/kcmp.c (ffffffff8113fed4)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex.c (ffffffff8115ccc2)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff811771b7)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117a84c)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811a4327)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/taskstats.c (ffffffff811aa5df)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_pid
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cae7a)
Location: include/linux/sched/task.h:123
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fc71b)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff81216741)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
```
```
In kernel/events/core.c (ffffffff81242a66)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In mm/oom_kill.c (ffffffff81256bd0)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff812acfb6)
Location: include/linux/sched/task.h:123
Inline: True
```
```
In mm/page_io.c (ffffffff812b7da7)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff812cd1cc)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812e7414)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff81300227)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff8136607e)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff81380b04)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - fs/io_uring.c:__io_req_aux_free
```
```
In fs/proc/task_mmu.c (ffffffff813b70e9)
Location: include/linux/sched/task.h:123
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
Location: include/linux/sched/task.h:123
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
In fs/proc/fd.c (ffffffff813c3843)
Location: include/linux/sched/task.h:123
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
In fs/proc/namespaces.c (ffffffff813c6207)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff81512044)
Location: include/linux/sched/task.h:123
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
In drivers/tty/tty_ldsem.c (ffffffff81bcc01e)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189ed5d)
Location: include/linux/sched/task.h:123
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff812319c0-ffffffff812319f3: put_task_struct (STB_LOCAL)
ffffffff81255640-ffffffff81255673: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ffef)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/fork.c (ffffffff810a092f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:wait_for_vfork_done
```
```
In kernel/exit.c (ffffffff810a7b69)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810b11be)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810bf442)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810c8448)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff810cb319)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810d431a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (ffffffff810e08b0)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff810e97f4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f7519)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f9778)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c6fe)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff8110d65e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81121504)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8112c5f3)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_del_holdout
```
```
In kernel/kcmp.c (ffffffff8113c21e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex.c (ffffffff81158cb0)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff81173e97)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177646)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811a147c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/taskstats.c (ffffffff811a7b8f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_pid
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c855a)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fb70a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff8121867e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In kernel/events/core.c (ffffffff8124d1b7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In mm/oom_kill.c (ffffffff812617e0)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff812b8bcd)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In mm/madvise.c (ffffffff812c19e0)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/page_io.c (ffffffff812c3457)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff812d9cb1)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812ed159)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-failure.c (ffffffff8130c4d7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff81372f70)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff8138fa53)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:__io_free_req
```
```
In fs/proc/task_mmu.c (ffffffff813c8a78)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813ce4ba)
Location: include/linux/sched/task.h:108
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
In fs/proc/fd.c (ffffffff813d59ea)
Location: include/linux/sched/task.h:108
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
In fs/proc/namespaces.c (ffffffff813d81a7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff8152ede9)
Location: include/linux/sched/task.h:108
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
In drivers/tty/tty_ldsem.c (ffffffff81c44e3e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ade2c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff8123b630-ffffffff8123b663: put_task_struct (STB_LOCAL)
ffffffff81260300-ffffffff81260333: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061171)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810a3d0c)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810a99aa)
Location: include/linux/sched/task.h:110
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
In kernel/ptrace.c (ffffffff810b24f4)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810c0e17)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810c9ef4)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff810ccd45)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810d5f5a)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (ffffffff810e26d0)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff810ea0c5)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f9a29)
Location: include/linux/sched/task.h:110
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810fb8cf)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e52a)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff81c36443)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811217e4)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8112ce07)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
```
In kernel/kcmp.c (ffffffff8113d3c7)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex.c (ffffffff8115a010)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff81174a67)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811781c3)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811a20d4)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/taskstats.c (ffffffff811a8833)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c97fa)
Location: include/linux/sched/task.h:110
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fc42a)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff8121bcda)
Location: include/linux/sched/task.h:110
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
In kernel/events/core.c (ffffffff81251a77)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In mm/oom_kill.c (ffffffff81265ffd)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff812be099)
Location: include/linux/sched/task.h:110
Inline: True
```
```
In mm/madvise.c (ffffffff812c88de)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/page_io.c (ffffffff812ca29b)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff812e1529)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812f34f5)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff813005c4)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff81312c37)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff813798f9)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io-wq.c (ffffffff813a25e6)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_exit_workers
```
```
In fs/proc/task_mmu.c (ffffffff813cfab7)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813d5141)
Location: include/linux/sched/task.h:110
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
In fs/proc/fd.c (ffffffff813dc7a7)
Location: include/linux/sched/task.h:110
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
In fs/proc/namespaces.c (ffffffff813df057)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff81535585)
Location: include/linux/sched/task.h:110
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
In drivers/tty/tty_ldsem.c (ffffffff81c380a3)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890e20)
Location: include/linux/sched/task.h:110
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff8123fd60-ffffffff8123fd93: put_task_struct (STB_LOCAL)
ffffffff81264e40-ffffffff81264e73: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106ae31)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810b5529)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810bb4b6)
Location: include/linux/sched/task.h:111
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
In kernel/ptrace.c (ffffffff810c47c4)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/ptrace.c:__x64_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810d3907)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810dcce4)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff810dfe85)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810e916e)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (ffffffff810f8ce1)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff8110184c)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff8111293c)
Location: include/linux/sched/task.h:111
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff81118738)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/core_sched.c (ffffffff8112c50b)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112dc8a)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d54f6c)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81141d84)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8114dacf)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
```
In kernel/kcmp.c (ffffffff81160547)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex.c (ffffffff8117f265)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff8119bb37)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119fb2a)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811cb889)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/taskstats.c (ffffffff811d2393)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5287)
Location: include/linux/sched/task.h:111
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff8122dd5a)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff81252bd7)
Location: include/linux/sched/task.h:111
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
In kernel/events/core.c (ffffffff8128d299)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In mm/oom_kill.c (ffffffff812a325e)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff8130083c)
Location: include/linux/sched/task.h:111
Inline: True
```
```
In mm/madvise.c (ffffffff8130d93f)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/page_io.c (ffffffff8130f2bb)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff813287f9)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff8133d965)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff8134a264)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff8135e6c1)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff813c6459)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io-wq.c (ffffffff813f30dd)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_put_and_exit
```
```
In fs/proc/task_mmu.c (ffffffff81420e97)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81426a81)
Location: include/linux/sched/task.h:111
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
In fs/proc/fd.c (ffffffff8142dd97)
Location: include/linux/sched/task.h:111
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
In fs/proc/namespaces.c (ffffffff81430a07)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff81593b55)
Location: include/linux/sched/task.h:111
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
In drivers/tty/tty_ldsem.c (ffffffff81d56965)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81924922)
Location: include/linux/sched/task.h:111
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff811154a0-ffffffff811154d3: put_task_struct (STB_LOCAL)
ffffffff8127a600-ffffffff8127a633: put_task_struct (STB_LOCAL)
ffffffff812a1660-ffffffff812a1693: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81078120)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810cb89d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810d1e8b)
Location: include/linux/sched/task.h:116
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
In kernel/ptrace.c (ffffffff810db969)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810e9a87)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810f655c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff810fa97d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff81103ef0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (ffffffff811150b5)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff8111bd6c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff81134a0d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
Direct callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
```
```
In kernel/sched/build_utility.c (ffffffff8114b76e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8114ea5e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f26b0d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81165898)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8117484e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff81e5f55e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811932a8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex/core.c (ffffffff811b31c4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex/core.c:wait_for_owner_exiting
```
```
In kernel/futex/pi.c (ffffffff811b4f40)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff811cbd7e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0138)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811ff650)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/taskstats.c (ffffffff81206a58)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122eaa7)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff81270767)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff8129b128)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In kernel/events/core.c (ffffffff812e1fa1)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In mm/oom_kill.c (ffffffff812fb156)
Location: include/linux/sched/task.h:116
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
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff81367c24)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/madvise.c (ffffffff81378e1a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/page_io.c (ffffffff813794d5)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff81397a49)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff813b0c20)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff813c0e0c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff813d8ea1)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff8144ccdd)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81498d14)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff814a0411)
Location: include/linux/sched/task.h:116
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
In fs/proc/fd.c (ffffffff814a7598)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (ffffffff814aa737)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff816355f1)
Location: include/linux/sched/task.h:116
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
In io_uring/io-wq.c (ffffffff816dbc45)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
```
```
In drivers/tty/tty_ldsem.c (ffffffff81f28afd)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7a292)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff8112ec60-ffffffff8112ecb7: put_task_struct (STB_LOCAL)
ffffffff812cdc90-ffffffff812cdce7: put_task_struct (STB_LOCAL)
ffffffff812f9580-ffffffff812f95d7: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088d30)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810e8eb4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810f08eb)
Location: include/linux/sched/task.h:116
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
In kernel/ptrace.c (ffffffff810fba39)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff8110b727)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff81118bec)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff8111d7d2)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff8112965b)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (ffffffff8113c455)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff8114527e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8115ef2d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
Direct callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
```
```
In kernel/sched/build_utility.c (ffffffff8117a1fe)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8117dbfe)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d25dc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811997e8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff811ab4a1)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff811b1478)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811d0ae8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex/core.c (ffffffff811f40d4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex/core.c:wait_for_owner_exiting
```
```
In kernel/futex/pi.c (ffffffff811f6030)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff8120f24e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81213b9e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81247065)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/taskstats.c (ffffffff8124ed88)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127aaa7)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6b70)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
```
In kernel/bpf/syscall.c (ffffffff812c6271)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/helpers.c (ffffffff812f424a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_release
```
```
In kernel/bpf/task_iter.c (ffffffff812f7457)
Location: include/linux/sched/task.h:116
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
In kernel/events/core.c (ffffffff8134a4d1)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In mm/oom_kill.c (ffffffff81364473)
Location: include/linux/sched/task.h:116
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
In mm/process_vm_access.c (ffffffff813e3bf4)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/madvise.c (ffffffff813f66cc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/page_io.c (ffffffff813f6ef5)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff81417629)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff81431770)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff81442cdc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff8145e9b5)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff814db24d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff8152d01e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81535331)
Location: include/linux/sched/task.h:116
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
In fs/proc/fd.c (ffffffff8153cc78)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (ffffffff81540387)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/apparmor/file.c (ffffffff816dbc9e)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff816ec2d1)
Location: include/linux/sched/task.h:116
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
In io_uring/io_uring.c (ffffffff8178ba21)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
```
In io_uring/io-wq.c (ffffffff817a7d49)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
```
```
In drivers/tty/tty_ldsem.c (ffffffff820d475d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
**Symbols:**

```
ffffffff81158a20-ffffffff81158a77: put_task_struct (STB_LOCAL)
ffffffff81337960-ffffffff813379b7: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108bc30)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810f4acf)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810fc8a8)
Location: include/linux/sched/task.h:122
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
In kernel/ptrace.c (ffffffff81107ad9)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff81117ab7)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff811260ac)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff8112a9c2)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff81136afb)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (ffffffff81150097)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff8115578e)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8116f61d)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
Direct callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
```
```
In kernel/sched/build_utility.c (ffffffff8118ae50)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118e89e)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff821569a6)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811ab4ca)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff811bd3c1)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff811c313e)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811e4d5e)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd35f)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running
```
```
In kernel/futex/core.c (ffffffff81208864)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/futex/core.c:wait_for_owner_exiting
```
```
In kernel/futex/pi.c (ffffffff8120a830)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff81224c5e)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812294da)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8125e0f5)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/taskstats.c (ffffffff81266138)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292607)
Location: include/linux/sched/task.h:122
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff81296ea1)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_release
  - kernel/trace/trace_osnoise.c:stop_kthread
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8c30)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
```
In kernel/bpf/syscall.c (ffffffff812ed331)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff81325328)
Location: include/linux/sched/task.h:122
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
In kernel/events/core.c (ffffffff8137b511)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In mm/oom_kill.c (ffffffff81396944)
Location: include/linux/sched/task.h:122
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
In mm/process_vm_access.c (ffffffff81418944)
Location: include/linux/sched/task.h:122
Inline: True
```
```
In mm/madvise.c (ffffffff814296b0)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/page_io.c (ffffffff8142a2c7)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_bdev_sync
```
```
In mm/mempolicy.c (ffffffff8144abb9)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff814671b0)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff8147859c)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff81494805)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff8150f72a)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81564d29)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8156d501)
Location: include/linux/sched/task.h:122
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
In fs/proc/fd.c (ffffffff81574f38)
Location: include/linux/sched/task.h:122
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
In fs/proc/namespaces.c (ffffffff81578327)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/apparmor/file.c (ffffffff817152e4)
Location: include/linux/sched/task.h:122
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff81726701)
Location: include/linux/sched/task.h:122
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
In io_uring/io_uring.c (ffffffff817ccb6b)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_put_task_remote
```
```
In io_uring/io-wq.c (ffffffff817e8bc6)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
```
```
In rust/helpers.c (ffffffff81805ae5)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_put_task_struct
```
```
In drivers/tty/tty_ldsem.c (ffffffff8215896d)
Location: include/linux/sched/task.h:122
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
**Symbols:**

```
ffffffff81168bf0-ffffffff81168c47: put_task_struct (STB_LOCAL)
ffffffff813687d0-ffffffff81368827: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81093918)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810fde6f)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff81105fa8)
Location: include/linux/sched/task.h:125
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
In kernel/ptrace.c (ffffffff81111479)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff811214a7)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff811306ac)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
```
```
In kernel/kthread.c (ffffffff8113519c)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop_put
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff8115bf67)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffffffff811633de)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8117c401)
Location: include/linux/sched/task.h:125
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
Direct callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
```
```
In kernel/sched/build_utility.c (ffffffff81199787)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119d24e)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff822397e6)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/rcu/update.c (ffffffff811cda06)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_holdout_task
```
```
In kernel/rcu/tree.c (ffffffff811d337e)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811faaae)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121355f)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running
```
```
In kernel/futex/core.c (ffffffff8121f6f4)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/futex/core.c:wait_for_owner_exiting
```
```
In kernel/futex/pi.c (ffffffff81221d90)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/futex/waitwake.c (ffffffff812238e1)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_mark
```
```
In kernel/cgroup/cgroup.c (ffffffff8123c954)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8124132a)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81278035)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/taskstats.c (ffffffff81280028)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/taskstats.c:cmd_attr_pid
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812adc47)
Location: include/linux/sched/task.h:125
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b24f1)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_release
  - kernel/trace/trace_osnoise.c:stop_kthread
```
```
In kernel/trace/bpf_trace.c (ffffffff812ea602)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_dealloc
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
```
In kernel/bpf/syscall.c (ffffffff8130be21)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff81349a13)
Location: include/linux/sched/task.h:125
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
In kernel/events/core.c (ffffffff813a4711)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In mm/oom_kill.c (ffffffff813c0254)
Location: include/linux/sched/task.h:125
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
In mm/process_vm_access.c (ffffffff81445496)
Location: include/linux/sched/task.h:125
Inline: True
```
```
In mm/madvise.c (ffffffff81462ee0)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/page_io.c (ffffffff8146368d)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_bdev_sync
```
```
In mm/mempolicy.c (ffffffff814845f8)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff814963f0)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff814a7ccc)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff814c4115)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff81543c2a)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff8159b7e8)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff815a5e79)
Location: include/linux/sched/task.h:125
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
In fs/proc/fd.c (ffffffff815ad908)
Location: include/linux/sched/task.h:125
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
In fs/proc/namespaces.c (ffffffff815b0a57)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/apparmor/file.c (ffffffff81754001)
Location: include/linux/sched/task.h:125
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff81767921)
Location: include/linux/sched/task.h:125
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
In io_uring/io_uring.c (ffffffff818112d5)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_put_task_remote
```
```
In io_uring/io-wq.c (ffffffff8182e976)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
```
```
In rust/helpers.c (ffffffff81842855)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_put_task_struct
```
```
In drivers/tty/tty_ldsem.c (ffffffff8223c1ed)
Location: include/linux/sched/task.h:125
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
**Symbols:**

```
ffffffff81175ea0-ffffffff81175ef7: put_task_struct (STB_LOCAL)
ffffffff8138f6b0-ffffffff8138f707: put_task_struct (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100b5f24)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_yield_to
```
```
In kernel/fork.c (ffff8000100f4e98)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffff8000100fb6bc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffff800010108410)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__arm64_compat_sys_ptrace
  - kernel/ptrace.c:__arm64_sys_ptrace
```
```
In kernel/sys.c (ffff800010119588)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_prlimit64
```
```
In kernel/kthread.c (ffff800010128590)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffff80001012f378)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/sched/core.c (ffff80001013c680)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (ffff8000101444ac)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffff800010150bac)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffff800010153740)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (ffff80001016b4bc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffff80001017a518)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffff800010188ec8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffff800010197d7c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/kcmp.c:__arm64_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101adab8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (ffff8000101b9df4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffff8000101d7c60)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dbaa0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffff800010206eb0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffff80001020d8a0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102305cc)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/bpf/syscall.c (ffff800010265760)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffff8000102a1060)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In mm/oom_kill.c (ffff8000102b7c2c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
```
```
In mm/process_vm_access.c (ffff800010312318)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/page_io.c (ffff8000103200f8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffff800010337cd8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffff800010352650)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffff80001036ec80)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In fs/proc_namespace.c (ffff8000103e7a80)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffff800010439218)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffff80001043e648)
Location: include/linux/sched/task.h:116
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffff800010446b68)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (ffff800010448db0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffff8000105aac30)
Location: include/linux/sched/task.h:116
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
In drivers/tty/tty_ldsem.c (ffff800010da6c80)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffff800010290e70-ffff800010290eb0: put_task_struct (STB_LOCAL)
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
In kernel/fork.c (c0353608)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c03595f8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (c03624c8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/sys.c (c036dc10)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
```
```
In kernel/kthread.c (c037aac0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (c037f0e8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_destroy_threads
```
```
In kernel/sched/core.c (c038ca48)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/rt.c (c039bf80)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c03a188c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (c03b70f0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (c03cb848)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (c03d7738)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (c03e2ca4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (c03f80a4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (c040157c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (c041a928)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (c041de08)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (c0445c88)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (c044c348)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/trace_sched_wakeup.c (c046c7dc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/bpf/syscall.c (c0493968)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/events/core.c (c04d11c8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (c04e484c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
```
```
In mm/process_vm_access.c (c052d1b0)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/page_io.c (c0538958)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/proc_namespace.c (c05bf5e8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (c06001bc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (c06052f4)
Location: include/linux/sched/task.h:116
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (c060bd4c)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (c060df08)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (c075a440)
Location: include/linux/sched/task.h:116
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
In drivers/tty/tty_ldsem.c (c0e9ea88)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013af8c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c000000000142cd4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (c00000000014f960)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_compat_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/sys.c (c000000000160e98)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
```
```
In kernel/kthread.c (c000000000173204)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (c00000000017880c)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/sched/core.c (c00000000018ad10)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (c000000000194790)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (c0000000001a2484)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c0000000001a7ae4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (c0000000001c2f54)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (c0000000001d48a4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (c0000000001e3178)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (c0000000001f79d4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (c000000000211304)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (c00000000021dc10)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (c000000000244a80)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (c0000000002490b4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (c00000000028342c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (c00000000028b920)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bab68)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/bpf/syscall.c (c00000000030a284)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (c000000000353214)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (c00000000036fa58)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (c0000000003e3220)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/page_io.c (c0000000003f4fa0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (c000000000412aec)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (c000000000438fd8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (c00000000045e014)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (c0000000004ee264)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (c00000000054c030)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (c0000000005541a8)
Location: include/linux/sched/task.h:116
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (c00000000055cc30)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (c00000000055f618)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (c0000000007281d8)
Location: include/linux/sched/task.h:116
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
In drivers/tty/tty_ldsem.c (c000000000ee9564)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
c00000000036e070-c00000000036e0c4: put_task_struct (STB_LOCAL)
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
In kernel/fork.c (ffffffe0000c1534)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffe0000c5320)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffe0000cc320)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/sys.c (ffffffe0000d44fe)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
```
```
In kernel/kthread.c (ffffffe0000df3ae)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffe0000e3030)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/sched/core.c (ffffffe0000ebe8c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/rt.c (ffffffe0000f9278)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffe0000fb4ae)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (ffffffe00010ba90)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffe000113e90)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffe00011e178)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffe000128aca)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001371e8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (ffffffe00013e484)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffe000150d0e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000153c26)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffe0001696dc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffe00016e8b0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe0001887b0)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffe0001a103a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffffffe0001d03cc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffe0001dbe9a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
```
```
In mm/process_vm_access.c (ffffffe000219a0c)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/page_io.c (ffffffe0002217f2)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In fs/proc_namespace.c (ffffffe00029c8fc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffe0002d2fc0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffe0002d4e96)
Location: include/linux/sched/task.h:116
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffe0002dcaa8)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (ffffffe0002deb9e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffe0003f36a6)
Location: include/linux/sched/task.h:116
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
In drivers/tty/tty_ldsem.c (ffffffe0008c8efe)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c5fb)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff81099eeb)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109f09c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810a85ce)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810b6a7f)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/kthread.c (ffffffff810c31eb)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810c98a2)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d6c30)
Location: include/linux/sched/task.h:116
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
In kernel/sched/fair.c (ffffffff810de6e9)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810e91f5)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810eae20)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (ffffffff810feb4d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811103d4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8111c1d0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff81129238)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113b862)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (ffffffff811434e4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff8115e667)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116110a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81187e10)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff8118dca4)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811aafba)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811da641)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffffffff8120f48a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8122239d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff812733b6)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/page_io.c (ffffffff8127e04e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff81291645)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812aa4ec)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812c2810)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff813248c4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff813673a9)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8136d3f5)
Location: include/linux/sched/task.h:116
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff81372e57)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (ffffffff81374b47)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff814ab219)
Location: include/linux/sched/task.h:116
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
In drivers/tty/tty_ldsem.c (ffffffff81a72e30)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff812212e0-ffffffff812212f8: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104c7cb)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff8108892b)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108dad0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff81096f9e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810a53bf)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/kthread.c (ffffffff810b1a2b)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810b80c2)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c5520)
Location: include/linux/sched/task.h:116
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
In kernel/sched/fair.c (ffffffff810cd6f9)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810d8cc0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810dae40)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (ffffffff810eed35)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81101104)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8110d2ac)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff8111bac8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e222)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (ffffffff81136838)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff81151911)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81154374)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8117af50)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff81180dc5)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119deda)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811cd401)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffffffff8120222a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8121554d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff81265326)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/page_io.c (ffffffff8126fe7e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff812832c5)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff8129be4c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812b3860)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff81315464)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81358049)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8135de85)
Location: include/linux/sched/task.h:116
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff81363927)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (ffffffff81365617)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff8149bc39)
Location: include/linux/sched/task.h:116
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
In drivers/tty/tty_ldsem.c (ffffffff81a2f1ee)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177df2d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff81214490-ffffffff812144a8: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ca2b)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff81099e9b)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109f04c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810a7b2e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810b5fdf)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/kthread.c (ffffffff810c273b)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810c8dd2)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d3870)
Location: include/linux/sched/task.h:116
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
In kernel/sched/fair.c (ffffffff810daa69)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810e5e35)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810e7f50)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (ffffffff810fbd0d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8110e2c4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff8111a0c0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff81126f58)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81139582)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (ffffffff81141394)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff8115c437)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115eeda)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81185be0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff8118ba74)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8d8a)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d8411)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffffffff8120d22a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8122013d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff81271156)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/page_io.c (ffffffff8127bdee)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff8128f455)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812a82fc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812c0620)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff81322394)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81364e79)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8136aec5)
Location: include/linux/sched/task.h:116
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff81370927)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (ffffffff81372617)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff814a72b9)
Location: include/linux/sched/task.h:116
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
In drivers/tty/tty_ldsem.c (ffffffff81adf240)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8cfd)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff8121f080-ffffffff8121f098: put_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105df45)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810a1b03)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a6f95)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffff810afc5e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
```
In kernel/sys.c (ffffffff810be32d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/kthread.c (ffffffff810cacfb)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810d1342)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/sched/core.c (ffffffff810de7fe)
Location: include/linux/sched/task.h:116
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
In kernel/sched/fair.c (ffffffff810e64b7)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810f06a5)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810f31bc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/locking/rtmutex.c (ffffffff81106eaf)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811197f4)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffff81125821)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff8113359e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146022)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (ffffffff8114fc3e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff8116954e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116c151)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81193526)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/taskstats.c (ffffffff811993ee)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6bca)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e67be)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffffffff8121c0dd)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8122f249)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/process_vm_access.c (ffffffff81280bc6)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In mm/page_io.c (ffffffff8128b9ce)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/mempolicy.c (ffffffff8129fb1c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812b8611)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812d10c0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
```
In fs/proc_namespace.c (ffffffff813340e7)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81377ebc)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8137e8d5)
Location: include/linux/sched/task.h:116
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
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:lstats_write
  - fs/proc/base.c:lstats_show_proc
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/fd.c (ffffffff81384310)
Location: include/linux/sched/task.h:116
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
In fs/proc/namespaces.c (ffffffff81385ff7)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In security/yama/yama_lsm.c (ffffffff814bfc8c)
Location: include/linux/sched/task.h:116
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
In drivers/tty/tty_ldsem.c (ffffffff81aeb9ae)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2f9d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff8122e0d0-ffffffff8122e0e8: put_task_struct (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
