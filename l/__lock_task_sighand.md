# Function: <code>__lock_task_sighand</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f1a0)
Location: kernel/signal.c:1209
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:do_send_sig_info
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:send_sigqueue
  - kernel/sys.c:k_getrusage
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/taskstats.c:taskstats_user_cmd
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:oom_adj_write
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/tty/tty_audit.c:tty_audit_push_current
```
**Symbols:**

```
ffffffff8108f1a0-ffffffff8108f226: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092210)
Location: kernel/signal.c:1209
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:k_getrusage
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/taskstats.c:taskstats_user_cmd
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81092210-ffffffff81092295: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810971a0)
Location: kernel/signal.c:1215
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:k_getrusage
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810971a0-ffffffff81097225: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810944a0)
Location: kernel/signal.c:1233
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810944a0-ffffffff81094524: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b340)
Location: kernel/signal.c:1234
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff8109b340-ffffffff8109b3c4: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f2b0)
Location: kernel/signal.c:1242
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff8109f2b0-ffffffff8109f320: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7570)
Location: kernel/signal.c:1325
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810a7570-ffffffff810a75e0: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab9a0)
Location: kernel/signal.c:1363
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810ab9a0-ffffffff810aba03: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1fb0)
Location: kernel/signal.c:1368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810b1fb0-ffffffff810b2013: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810baac8)
Location: kernel/signal.c:1368
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:fill_stats_for_tgid
  - fs/coredump.c:zap_threads
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810ba970-ffffffff810ba9d6: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5d87)
Location: kernel/signal.c:1369
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:handle_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:fill_stats_for_tgid
  - fs/coredump.c:zap_threads
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810b5c30-ffffffff810b5c97: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7987)
Location: kernel/signal.c:1371
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:fill_stats_for_tgid
  - fs/coredump.c:zap_threads
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810b7830-ffffffff810b7897: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c9e07)
Location: kernel/signal.c:1382
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:fill_stats_for_tgid
  - fs/coredump.c:zap_threads
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810c9c80-ffffffff810c9ce7: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e18f0)
Location: kernel/signal.c:1383
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_unfreeze_traced
  - kernel/sys.c:getrusage
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:fill_stats_for_tgid
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810e1740-ffffffff810e17b4: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81101c10)
Location: kernel/signal.c:1384
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_unfreeze_traced
  - kernel/sys.c:getrusage
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:fill_stats_for_tgid
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81101a30-ffffffff81101aa4: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110de29)
Location: kernel/signal.c:1390
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_unfreeze_traced
  - kernel/sys.c:getrusage
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:fill_stats_for_tgid
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff8110dc40-ffffffff8110dcb4: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81117789)
Location: kernel/signal.c:1391
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_unfreeze_traced
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:fill_stats_for_tgid
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff811175a0-ffffffff81117614: __lock_task_sighand (STB_GLOBAL)
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
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010dba0)
Location: kernel/signal.c:1368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:taskstats_user_cmd
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffff80001010dba0-ffff80001010dc94: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0365fa8)
Location: kernel/signal.c:1368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:taskstats_user_cmd
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
c0365fa8-c0366014: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000154fb0)
Location: kernel/signal.c:1368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:taskstats_user_cmd
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
c000000000154fb0-c000000000155070: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ced04)
Location: kernel/signal.c:1368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/taskstats.c:taskstats_user_cmd
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffe0000ced04-ffffffe0000ced70: __lock_task_sighand (STB_GLOBAL)
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
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac320)
Location: kernel/signal.c:1368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810ac320-ffffffff810ac383: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109acb0)
Location: kernel/signal.c:1368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff8109acb0-ffffffff8109ad13: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab880)
Location: kernel/signal.c:1368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810ab880-ffffffff810ab8e3: __lock_task_sighand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sighand_struct *__lock_task_sighand(struct task_struct *tsk, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b39a0)
Location: kernel/signal.c:1368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
  - kernel/sys.c:getrusage
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/freezer.c:freeze_task
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810b39a0-ffffffff810b3a12: __lock_task_sighand (STB_GLOBAL)
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
