# Function: <code>unlock_task_sighand</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108aa91)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8108f282)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - kernel/signal.c:do_send_sig_info
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:send_sigqueue
```
```
In kernel/sys.c (ffffffff810927a5)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
```
```
In kernel/sched/auto_group.c (ffffffff810c4a1c)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
```
```
In kernel/freezer.c (ffffffff810e9d69)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f26ae)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/taskstats.c (ffffffff8113eb27)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (ffffffff8126f284)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8127a97f)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:oom_adj_write
```
```
In fs/proc/array.c (ffffffff8127ff7e)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In drivers/tty/tty_audit.c (ffffffff814ed222)
Location: include/linux/sched.h:2761
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_push_current
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108eed7)
Location: include/linux/sched.h:3030
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff81092eb6)
Location: include/linux/sched.h:3030
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff81095926)
Location: include/linux/sched.h:3030
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
```
```
In kernel/sched/auto_group.c (ffffffff810c8ce1)
Location: include/linux/sched.h:3030
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff810f0abb)
Location: include/linux/sched.h:3030
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810fac8c)
Location: include/linux/sched.h:3030
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff81147158)
Location: include/linux/sched.h:3030
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (ffffffff8129aabf)
Location: include/linux/sched.h:3030
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812a7ec2)
Location: include/linux/sched.h:3030
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff812acfca)
Location: include/linux/sched.h:3030
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81093e67)
Location: include/linux/sched.h:3144
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff81097e46)
Location: include/linux/sched.h:3144
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff8109a916)
Location: include/linux/sched.h:3144
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
```
```
In kernel/sched/auto_group.c (ffffffff810cecf1)
Location: include/linux/sched.h:3144
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff810f7c1b)
Location: include/linux/sched.h:3144
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110860c)
Location: include/linux/sched.h:3144
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff81150ff5)
Location: include/linux/sched.h:3144
Inline: True
```
```
In fs/coredump.c (ffffffff812af64f)
Location: include/linux/sched.h:3144
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812bd7a2)
Location: include/linux/sched.h:3144
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff812c289e)
Location: include/linux/sched.h:3144
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81090f57)
Location: include/linux/sched/signal.h:584
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff81095158)
Location: include/linux/sched/signal.h:584
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff8109b0b0)
Location: include/linux/sched/signal.h:584
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810cdf8f)
Location: include/linux/sched/signal.h:584
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff810f9aeb)
Location: include/linux/sched/signal.h:584
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110a8d6)
Location: include/linux/sched/signal.h:584
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff81153679)
Location: include/linux/sched/signal.h:584
Inline: True
```
```
In fs/coredump.c (ffffffff812bca8f)
Location: include/linux/sched/signal.h:584
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812ca72e)
Location: include/linux/sched/signal.h:584
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff812cfb9c)
Location: include/linux/sched/signal.h:584
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff81097dc7)
Location: include/linux/sched/signal.h:585
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff8109bff8)
Location: include/linux/sched/signal.h:585
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810a1d90)
Location: include/linux/sched/signal.h:585
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810d5865)
Location: include/linux/sched/signal.h:585
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff811045ae)
Location: include/linux/sched/signal.h:585
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81115a43)
Location: include/linux/sched/signal.h:585
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff8115fe79)
Location: include/linux/sched/signal.h:585
Inline: True
```
```
In fs/coredump.c (ffffffff812e0378)
Location: include/linux/sched/signal.h:585
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812eefbe)
Location: include/linux/sched/signal.h:585
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff812f431b)
Location: include/linux/sched/signal.h:585
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff8109b838)
Location: include/linux/sched/signal.h:613
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810a03c8)
Location: include/linux/sched/signal.h:613
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810a80b2)
Location: include/linux/sched/signal.h:613
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810dd815)
Location: include/linux/sched/signal.h:613
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff8110f3ae)
Location: include/linux/sched/signal.h:613
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81122236)
Location: include/linux/sched/signal.h:613
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff8116ec2b)
Location: include/linux/sched/signal.h:613
Inline: True
```
```
In fs/coredump.c (ffffffff8130c59c)
Location: include/linux/sched/signal.h:613
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8131c08e)
Location: include/linux/sched/signal.h:613
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81321728)
Location: include/linux/sched/signal.h:613
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810a3a52)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810a8703)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810b0dc2)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810e7f85)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff8111a9fa)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d947)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff8117c72b)
Location: include/linux/sched/signal.h:655
Inline: True
```
```
In fs/coredump.c (ffffffff81321dfc)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8133323e)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81338838)
Location: include/linux/sched/signal.h:655
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810a8686)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810abcd9)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810b6911)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810eef06)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81125100)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811385ec)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff8115dcf4)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff811895cf)
Location: include/linux/sched/signal.h:686
Inline: True
```
```
In fs/coredump.c (ffffffff81349c75)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8135b16e)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81360ef7)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810aeca6)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b22e9)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810bced1)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810fab96)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff811310c0)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811442cf)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff811698e4)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff8119550f)
Location: include/linux/sched/signal.h:678
Inline: True
```
```
In fs/coredump.c (ffffffff81361f15)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8137337e)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81379157)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810b6840)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810bab91)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810c4611)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/task_work.c (ffffffff810ce56e)
Location: include/linux/sched/signal.h:690
Inline: True
```
```
In kernel/sched/autogroup.c (ffffffff8110507d)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81140490)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81153ddf)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff8117b454)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff811aa44a)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/coredump.c (ffffffff813a7cde)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/proc/base.c (ffffffff813bb61e)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff813c2203)
Location: include/linux/sched/signal.h:690
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810b1a2d)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b5e5a)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810bfa11)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff811036fd)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff8113c800)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114f9b8)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:handle_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff811782f4)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff811a79ea)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/coredump.c (ffffffff813b8b63)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/proc/base.c (ffffffff813cd1ae)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff813d4352)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810b30a0)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b7a5a)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810c1441)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff811059f9)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff8113da50)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81150d96)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff81178e64)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff811a83ca)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/coredump.c (ffffffff813bfc60)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/proc/base.c (ffffffff813d407e)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff813db192)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810c5240)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810c9ee4)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810d3f31)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff81123689)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81160bd0)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81175166)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff811a0794)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff811d1ca6)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/coredump.c (ffffffff8140fa90)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/proc/base.c (ffffffff8142578e)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff8142c828)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810dce4c)
Location: include/linux/sched/signal.h:749
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_unfreeze_traced
```
```
In kernel/signal.c (ffffffff810e19c2)
Location: include/linux/sched/signal.h:749
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810ecbfa)
Location: include/linux/sched/signal.h:749
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_utility.c (ffffffff8114d261)
Location: include/linux/sched/signal.h:749
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81193959)
Location: include/linux/sched/signal.h:749
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa43b)
Location: include/linux/sched/signal.h:749
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
```
In kernel/cgroup/freezer.c (ffffffff811d0eec)
Location: include/linux/sched/signal.h:749
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff812064b7)
Location: include/linux/sched/signal.h:749
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/proc/base.c (ffffffff8149eb29)
Location: include/linux/sched/signal.h:749
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff814a60eb)
Location: include/linux/sched/signal.h:749
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810fd094)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_unfreeze_traced
```
```
In kernel/signal.c (ffffffff81101ce2)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff8110df9a)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_utility.c (ffffffff8117c301)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff811d13dd)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ea488)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
```
In kernel/cgroup/freezer.c (ffffffff81214a5c)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff8124e7b7)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/proc/base.c (ffffffff81533849)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff8153b72b)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff811090ae)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_unfreeze_traced
```
```
In kernel/signal.c (ffffffff8110df28)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff8111a235)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_utility.c (ffffffff8118cfac)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff811e564d)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811feba8)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
```
In kernel/cgroup/freezer.c (ffffffff8122a37c)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff81265b67)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/proc/base.c (ffffffff8156ba39)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81573a56)
Location: include/linux/sched/signal.h:750
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff81112a3e)
Location: include/linux/sched/signal.h:753
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_unfreeze_traced
```
```
In kernel/signal.c (ffffffff81117888)
Location: include/linux/sched/signal.h:753
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sched/build_utility.c (ffffffff8119b95c)
Location: include/linux/sched/signal.h:753
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff811fb347)
Location: include/linux/sched/signal.h:753
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81214fa9)
Location: include/linux/sched/signal.h:753
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
```
In kernel/cgroup/freezer.c (ffffffff8124233c)
Location: include/linux/sched/signal.h:753
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff8127fa28)
Location: include/linux/sched/signal.h:753
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/proc/base.c (ffffffff815a5d95)
Location: include/linux/sched/signal.h:753
Inline: True
Inline callers:
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff815ac35d)
Location: include/linux/sched/signal.h:753
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010109390)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffff80001010e010)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffff800010119a30)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffff80001015f610)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffff800010198430)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae824)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffff8000101dcde0)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffff80001020d77c)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (ffff8000104285d0)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffff80001043d8a4)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffff800010445610)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (c0362c94)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (c036634c)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (c036df84)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (c03abe3c)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
```
```
In kernel/freezer.c (c03e33d0)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (c03f9908)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (c041ee60)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (c044c22c)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (c05f123c)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (c0603a90)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (c060a664)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c000000000150848)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (c000000000155458)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (c000000000161260)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (c0000000001b4bb0)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (c0000000001f834c)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (c000000000212de8)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (c00000000024ab50)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (c00000000028b7c4)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (c0000000005387e8)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (c000000000551d98)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (c00000000055b020)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffe0000cca7e)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffe0000cefce)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffe0000d4724)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffe000103854)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffe0001290de)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000138298)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffe000154a76)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffe00016e7ba)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (ffffffe0002c67d0)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffe0002d6a7c)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffe0002db56e)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810a9016)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810ac659)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810b7241)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810f3ee6)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81129870)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113ca7f)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff81161f04)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff8118db2f)
Location: include/linux/sched/signal.h:678
Inline: True
```
```
In fs/coredump.c (ffffffff8135a4f5)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8136b95e)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81371737)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810979e6)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff8109afe9)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810a5b81)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810e40a6)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff8111c100)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f50a)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff81155164)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff81180c4d)
Location: include/linux/sched/signal.h:678
Inline: True
```
```
In fs/coredump.c (ffffffff8134b19f)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8135c3ee)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81362202)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810a8576)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810abbb9)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810b67a1)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810f10c6)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81127590)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a79f)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff8115fcd4)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff8118b8ff)
Location: include/linux/sched/signal.h:678
Inline: True
```
```
In fs/coredump.c (ffffffff81357fc5)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8136942e)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff8136f207)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/ptrace.c (ffffffff810b06a6)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b3d22)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810beb21)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810fc0c6)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81133bd0)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114725f)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff8116d004)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff81199274)
Location: include/linux/sched/signal.h:678
Inline: True
```
```
In fs/coredump.c (ffffffff8136b6dc)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8137cc9e)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81382b97)
Location: include/linux/sched/signal.h:678
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
</ul>

## Differences
