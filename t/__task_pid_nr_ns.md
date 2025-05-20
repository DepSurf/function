# Function: <code>__task_pid_nr_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109dd70)
Location: kernel/pid.c:520
Inline: False
Direct callers:
  - kernel/fork.c:SyS_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/capability.c:SyS_capget
  - kernel/capability.c:SyS_capset
  - kernel/signal.c:send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:get_signal
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:SyS_setpgid
  - kernel/sched/core.c:schedule_tail
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/cgroup.c:pidlist_array_load
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_mmap_output
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/thread_self.c:proc_thread_self_readlink
  - fs/proc/thread_self.c:proc_thread_self_follow_link
  - ipc/msg.c:do_msgsnd
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_get
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
**Symbols:**

```
ffffffff8109dd70-ffffffff8109ddf3: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a13d0)
Location: kernel/pid.c:520
Inline: False
Direct callers:
  - kernel/fork.c:SyS_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_readlink
  - ipc/msg.c:do_msgsnd
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
**Symbols:**

```
ffffffff810a13d0-ffffffff810a1453: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6490)
Location: kernel/pid.c:520
Inline: False
Direct callers:
  - kernel/fork.c:SyS_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - ipc/msg.c:do_msgsnd
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
**Symbols:**

```
ffffffff810a6490-ffffffff810a6513: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3410)
Location: kernel/pid.c:521
Inline: False
Direct callers:
  - kernel/fork.c:SyS_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:sys_getpid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810a3410-ffffffff810a34a6: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9ca0)
Location: kernel/pid.c:390
Inline: False
Direct callers:
  - kernel/fork.c:SyS_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:sys_getpid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810a9ca0-ffffffff810a9d89: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0810)
Location: kernel/pid.c:415
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_kill
  - kernel/signal.c:__do_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__x64_sys_getpid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810b0810-ffffffff810b08f8: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9950)
Location: kernel/pid.c:422
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__x64_sys_getpid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810b9950-ffffffff810b99db: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf750)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__x64_sys_getpid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810bf750-ffffffff810bf7e4: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5b20)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__x64_sys_getpid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c5b20-ffffffff810c5bb4: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd3b0)
Location: kernel/pid.c:491
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:wake_futex_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/exec.c:exec_binprm
  - fs/userfaultfd.c:handle_userfault
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810cd3b0-ffffffff810cd42d: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7f50)
Location: kernel/pid.c:492
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:wake_futex_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/exec.c:exec_binprm
  - fs/userfaultfd.c:handle_userfault
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - drivers/scsi/sg.c:sg_read
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c7f50-ffffffff810c7fe1: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c99f0)
Location: kernel/pid.c:492
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/exec.c:exec_binprm
  - fs/userfaultfd.c:handle_userfault
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - drivers/scsi/sg.c:sg_read
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c99f0-ffffffff810c9a81: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dc950)
Location: kernel/pid.c:492
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:__x64_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/exec.c:exec_binprm
  - fs/userfaultfd.c:handle_userfault
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810dc950-ffffffff810dca00: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f6120)
Location: kernel/pid.c:492
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal_locked
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/audit.c:audit_log_task_info
  - kernel/auditsc.c:audit_log_uring
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/exec.c:exec_binprm
  - fs/userfaultfd.c:handle_userfault
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810f6120-ffffffff810f61df: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811186d0)
Location: kernel/pid.c:492
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal_locked
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/audit.c:audit_log_task_info
  - kernel/auditsc.c:audit_log_uring
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:task_group_seq_get_next
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/exec.c:exec_binprm
  - fs/userfaultfd.c:handle_userfault
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/apparmor/notify.c:build_unotif
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff811186d0-ffffffff8111878f: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81125910)
Location: kernel/pid.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal_locked
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/audit.c:audit_log_task_info
  - kernel/auditsc.c:audit_log_uring
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:task_group_seq_get_next
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/exec.c:exec_binprm
  - fs/userfaultfd.c:handle_userfault
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/apparmor/notify.c:build_v3_unotif
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81125910-ffffffff811259cf: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8112ff10)
Location: kernel/pid.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal_locked
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getppid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/audit.c:audit_log_task_info
  - kernel/auditsc.c:audit_log_uring
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_fill_link_info
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:task_seq_get_next
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - fs/exec.c:exec_binprm
  - fs/userfaultfd.c:handle_userfault
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - security/apparmor/notify.c:build_v3_unotif
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/dynamic_debug.c:__dynamic_emit_prefix
  - drivers/gpu/drm/drm_ioctl.c:drm_getclient
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff8112ff10-ffffffff8112ffcf: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124020)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/fork.c:__arm64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__arm64_sys_capset
  - kernel/capability.c:__arm64_sys_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__arm64_sys_setpgid
  - kernel/sys.c:__arm64_sys_getppid
  - kernel/sys.c:__arm64_sys_gettid
  - kernel/sys.c:__arm64_sys_getpid
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__arm64_sys_ioprio_get
  - block/ioprio.c:__arm64_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffff800010124020-ffff8000101240e8: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377370)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capget
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:sys_getpid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/exec.c:__do_execve_file
  - fs/userfaultfd.c:handle_userfault
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:fill_prstatus
  - fs/binfmt_elf_fdpic.c:fill_prstatus
  - fs/binfmt_elf_fdpic.c:fill_prstatus
  - fs/binfmt_elf_fdpic.c:fill_prstatus
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:do_mq_timedsend
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - drivers/scsi/sg.c:sg_check_file_access
  - drivers/scsi/sg.c:sg_check_file_access
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_autobind
```
**Symbols:**

```
c0377370-c0377414: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016dd80)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:sys_getpid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_autobind
```
**Symbols:**

```
c00000000016dd80-c00000000016de48: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc36c)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capget
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:sys_getpid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/exec.c:__do_execve_file
  - fs/userfaultfd.c:handle_userfault
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_autobind
```
**Symbols:**

```
ffffffe0000dc36c-ffffffe0000dc40a: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfea0)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__x64_sys_getpid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810bfea0-ffffffff810bff34: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae6b0)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__x64_sys_getpid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810ae6b0-ffffffff810ae744: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf3f0)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__x64_sys_getpid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810bf3f0-ffffffff810bf484: __task_pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pid_t __task_pid_nr_ns(struct task_struct *task, enum pid_type type, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7850)
Location: kernel/pid.c:425
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_getppid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__x64_sys_getpid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:cgroup_procs_show
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/events/core.c:perf_event_pid_type
  - fs/userfaultfd.c:handle_userfault
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/self.c:proc_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/ext4/sysfs.c:ext4_attr_show
  - ipc/mqueue.c:__do_notify
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/realpath.c:tomoyo_get_local_path
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - lib/dynamic_debug.c:dynamic_emit_prefix
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c7850-ffffffff810c790e: __task_pid_nr_ns (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
