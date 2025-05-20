# Function: <code>find_task_by_vpid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109e760)
Location: kernel/pid.c:459
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capget
  - kernel/ptrace.c:ptrace_get_task_struct
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_prlimit64
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:SyS_get_robust_list
  - kernel/futex_compat.c:compat_SyS_get_robust_list
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/migrate.c:SyS_move_pages
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_control
  - security/yama/yama_lsm.c:yama_task_prctl
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff8109e760-ffffffff8109e7ad: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1e00)
Location: kernel/pid.c:459
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capget
  - kernel/ptrace.c:ptrace_get_task_struct
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
  - kernel/futex.c:SyS_get_robust_list
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex_compat.c:compat_SyS_get_robust_list
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/migrate.c:SyS_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/yama/yama_lsm.c:yama_task_prctl
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810a1e00-ffffffff810a1e4d: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6ec0)
Location: kernel/pid.c:459
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:SyS_capget
  - kernel/ptrace.c:ptrace_get_task_struct
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
  - kernel/futex.c:SyS_get_robust_list
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex_compat.c:compat_SyS_get_robust_list
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/yama/yama_lsm.c:yama_task_prctl
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810a6ec0-ffffffff810a6f0d: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3e00)
Location: kernel/pid.c:460
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:SyS_capget
  - kernel/ptrace.c:ptrace_get_task_struct
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
  - kernel/futex.c:SyS_get_robust_list
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex_compat.c:compat_SyS_get_robust_list
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/yama/yama_lsm.c:yama_task_prctl
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810a3e00-ffffffff810a3e53: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aa400)
Location: kernel/pid.c:329
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:SyS_capget
  - kernel/ptrace.c:ptrace_get_task_struct
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
  - kernel/futex.c:SyS_get_robust_list
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex_compat.c:compat_SyS_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/yama/yama_lsm.c:yama_task_prctl
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810aa400-ffffffff810aa45e: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b1010)
Location: kernel/pid.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/futex_compat.c:__x32_compat_sys_get_robust_list
  - kernel/futex_compat.c:__ia32_compat_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810b1010-ffffffff810b1070: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ba150)
Location: kernel/pid.c:350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810ba150-ffffffff810ba1a8: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c0060)
Location: kernel/pid.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:check_clock
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810c0060-ffffffff810c00b4: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c6430)
Location: kernel/pid.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810c6430-ffffffff810c6484: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ce360)
Location: kernel/pid.c:419
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/capability.c:__do_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810ce300-ffffffff810ce34f: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8e1b)
Location: kernel/pid.c:420
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/capability.c:__do_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810c8dc0-ffffffff810c8e0f: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca8bb)
Location: kernel/pid.c:420
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__do_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810ca860-ffffffff810ca8af: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd80b)
Location: kernel/pid.c:420
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__do_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core_sched.c:sched_core_share_pid
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x64_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810dd7b0-ffffffff810dd7ff: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f7171)
Location: kernel/pid.c:420
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__do_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
  - kernel/futex/syscalls.c:__ia32_sys_get_robust_list
  - kernel/futex/syscalls.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810f7100-ffffffff810f7158: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811198e1)
Location: kernel/pid.c:420
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__do_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
  - kernel/futex/syscalls.c:__ia32_sys_get_robust_list
  - kernel/futex/syscalls.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff81119860-ffffffff811198b8: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126dc1)
Location: kernel/pid.c:423
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__do_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
  - kernel/futex/syscalls.c:__ia32_sys_get_robust_list
  - kernel/futex/syscalls.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff81126d40-ffffffff81126d98: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811313a1)
Location: kernel/pid.c:423
Inline: True
Inline callers:
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__do_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
  - kernel/futex/syscalls.c:__ia32_sys_get_robust_list
  - kernel/futex/syscalls.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_select_domain
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff81131320-ffffffff81131378: find_task_by_vpid (STB_GLOBAL)
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
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124c88)
Location: kernel/pid.c:353
Inline: False
Direct callers:
  - kernel/capability.c:__arm64_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_sys_getsid
  - kernel/sys.c:__arm64_sys_getpgid
  - kernel/sys.c:__arm64_sys_setpgid
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__arm64_sys_sched_getattr
  - kernel/sched/core.c:__arm64_sys_sched_getparam
  - kernel/sched/core.c:__arm64_sys_sched_getscheduler
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:__arm64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__arm64_sys_ioprio_get
  - block/ioprio.c:__arm64_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffff800010124c88-ffff800010124ce4: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377c20)
Location: kernel/pid.c:353
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_getscheduler
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
c0377c20-c0377c80: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016ea70)
Location: kernel/pid.c:353
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:__se_sys_getpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_getscheduler
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:__se_compat_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
c00000000016ea70-c00000000016eb04: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dcc1a)
Location: kernel/pid.c:353
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:__se_sys_getpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_getscheduler
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffe0000dcc1a-ffffffe0000dcc70: find_task_by_vpid (STB_GLOBAL)
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
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c07b0)
Location: kernel/pid.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810c07b0-ffffffff810c0804: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aefb0)
Location: kernel/pid.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810aefb0-ffffffff810af004: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfd00)
Location: kernel/pid.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810bfd00-ffffffff810bfd54: find_task_by_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *find_task_by_vpid(pid_t vnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8110)
Location: kernel/pid.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/signal.c:do_send_specific
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/sched/core.c:__ia32_sys_sched_getscheduler
  - kernel/sched/core.c:__x64_sys_sched_getscheduler
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_pid
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - net/core/net_namespace.c:get_net_ns_by_pid
```
**Symbols:**

```
ffffffff810c8110-ffffffff810c8164: find_task_by_vpid (STB_GLOBAL)
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
