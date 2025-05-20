# Function: <code>lock_task_sighand</code>

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
In kernel/ptrace.c (ffffffff8108a9d1)
Location: include/linux/sched.h:2751
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_getsiginfo
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8108f243)
Location: include/linux/sched.h:2751
Inline: True
Inline callers:
  - kernel/signal.c:do_send_sig_info
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:send_sigqueue
```
```
In kernel/sys.c (ffffffff81092640)
Location: include/linux/sched.h:2751
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
```
```
In kernel/sched/auto_group.c (ffffffff810c4973)
Location: include/linux/sched.h:2751
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
```
```
In kernel/freezer.c (ffffffff810e9d4e)
Location: include/linux/sched.h:2751
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f268f)
Location: include/linux/sched.h:2751
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/taskstats.c (ffffffff8113ea3d)
Location: include/linux/sched.h:2751
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (ffffffff8126f23f)
Location: include/linux/sched.h:2751
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8127a43d)
Location: include/linux/sched.h:2751
Inline: True
Inline callers:
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:oom_adj_write
```
```
In fs/proc/array.c (ffffffff8127fdba)
Location: include/linux/sched.h:2751
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
```
In drivers/tty/tty_audit.c (ffffffff814ed1cc)
Location: include/linux/sched.h:2751
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
In kernel/ptrace.c (ffffffff8108ee69)
Location: include/linux/sched.h:3020
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff81092dfb)
Location: include/linux/sched.h:3020
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810957c0)
Location: include/linux/sched.h:3020
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
```
```
In kernel/sched/auto_group.c (ffffffff810c8c93)
Location: include/linux/sched.h:3020
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff810f0aa0)
Location: include/linux/sched.h:3020
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810faa3f)
Location: include/linux/sched.h:3020
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff8114706d)
Location: include/linux/sched.h:3020
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (ffffffff8129aa83)
Location: include/linux/sched.h:3020
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812a7e00)
Location: include/linux/sched.h:3020
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff812ace06)
Location: include/linux/sched.h:3020
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
In kernel/ptrace.c (ffffffff81093df9)
Location: include/linux/sched.h:3134
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff81097d8b)
Location: include/linux/sched.h:3134
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff8109a7b0)
Location: include/linux/sched.h:3134
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
```
```
In kernel/sched/auto_group.c (ffffffff810ceca3)
Location: include/linux/sched.h:3134
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff810f7c00)
Location: include/linux/sched.h:3134
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811083bf)
Location: include/linux/sched.h:3134
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff81150f14)
Location: include/linux/sched.h:3134
Inline: True
```
```
In fs/coredump.c (ffffffff812af613)
Location: include/linux/sched.h:3134
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812bd6e0)
Location: include/linux/sched.h:3134
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff812c26d7)
Location: include/linux/sched.h:3134
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
In kernel/ptrace.c (ffffffff81090ee9)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff8109509a)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff8109af43)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810cdf53)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff810f9ad0)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110a647)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff811533a3)
Location: include/linux/sched/signal.h:574
Inline: True
```
```
In fs/coredump.c (ffffffff812bca43)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812ca66c)
Location: include/linux/sched/signal.h:574
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff812cf967)
Location: include/linux/sched/signal.h:574
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
In kernel/ptrace.c (ffffffff81097d59)
Location: include/linux/sched/signal.h:575
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff8109bf3a)
Location: include/linux/sched/signal.h:575
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810a1c23)
Location: include/linux/sched/signal.h:575
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810d5823)
Location: include/linux/sched/signal.h:575
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81104593)
Location: include/linux/sched/signal.h:575
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811157f7)
Location: include/linux/sched/signal.h:575
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff8115fba3)
Location: include/linux/sched/signal.h:575
Inline: True
```
```
In fs/coredump.c (ffffffff812e032d)
Location: include/linux/sched/signal.h:575
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812eeefc)
Location: include/linux/sched/signal.h:575
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff812f40e9)
Location: include/linux/sched/signal.h:575
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
In kernel/ptrace.c (ffffffff8109b6f1)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810a030d)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810a7f44)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810dd7ed)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff8110f393)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81121fb1)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff8116eaf2)
Location: include/linux/sched/signal.h:603
Inline: True
```
```
In fs/coredump.c (ffffffff8130c568)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8131bfcc)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81321508)
Location: include/linux/sched/signal.h:603
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
In kernel/ptrace.c (ffffffff810a391f)
Location: include/linux/sched/signal.h:645
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810a8653)
Location: include/linux/sched/signal.h:645
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810b0c54)
Location: include/linux/sched/signal.h:645
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810e7f5d)
Location: include/linux/sched/signal.h:645
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff8111a9df)
Location: include/linux/sched/signal.h:645
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d6d1)
Location: include/linux/sched/signal.h:645
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/taskstats.c (ffffffff8117c5f2)
Location: include/linux/sched/signal.h:645
Inline: True
```
```
In fs/coredump.c (ffffffff81321dc8)
Location: include/linux/sched/signal.h:645
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8133317c)
Location: include/linux/sched/signal.h:645
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81338618)
Location: include/linux/sched/signal.h:645
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
In kernel/ptrace.c (ffffffff810a8649)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810abc36)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810b67b4)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810eeedd)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff811250e5)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811380d0)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff8115dcc9)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff81189496)
Location: include/linux/sched/signal.h:676
Inline: True
```
```
In fs/coredump.c (ffffffff81349c25)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8135b0ae)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81360cd9)
Location: include/linux/sched/signal.h:676
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
In kernel/ptrace.c (ffffffff810aec69)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b2246)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810bcd74)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810fab6d)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff811310a5)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811441b4)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff811698b9)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff811953d6)
Location: include/linux/sched/signal.h:668
Inline: True
```
```
In fs/coredump.c (ffffffff81361ec5)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff813732be)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81378f39)
Location: include/linux/sched/signal.h:668
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
In kernel/ptrace.c (ffffffff810b6803)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810baac8)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810c44b4)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/task_work.c (ffffffff810ce546)
Location: include/linux/sched/signal.h:680
Inline: True
```
```
In kernel/sched/autogroup.c (ffffffff8110503d)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81140475)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81153db8)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff8117b429)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff811aa316)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/coredump.c (ffffffff813a7ca3)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/proc/base.c (ffffffff813bb55e)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff813c1fe9)
Location: include/linux/sched/signal.h:680
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
In kernel/ptrace.c (ffffffff810b19f0)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b5d87)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810bf8b4)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff811036bd)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff8113c7e5)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114f978)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:handle_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff811782c9)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff811a78b6)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/coredump.c (ffffffff813b8b34)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/proc/base.c (ffffffff813cd0ee)
Location: include/linux/sched/signal.h:695
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff813d4139)
Location: include/linux/sched/signal.h:695
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
In kernel/ptrace.c (ffffffff810b3036)
Location: include/linux/sched/signal.h:701
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b7987)
Location: include/linux/sched/signal.h:701
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810c12e4)
Location: include/linux/sched/signal.h:701
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff811059bd)
Location: include/linux/sched/signal.h:701
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff8113da35)
Location: include/linux/sched/signal.h:701
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81150ca1)
Location: include/linux/sched/signal.h:701
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff81178e39)
Location: include/linux/sched/signal.h:701
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff811a8296)
Location: include/linux/sched/signal.h:701
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/coredump.c (ffffffff813bfc34)
Location: include/linux/sched/signal.h:701
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/proc/base.c (ffffffff813d3fbe)
Location: include/linux/sched/signal.h:701
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff813daf79)
Location: include/linux/sched/signal.h:701
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
In kernel/ptrace.c (ffffffff810c51d6)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810c9e07)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810d3dd4)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff8112364d)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81160bb5)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81175071)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff811a0769)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff811d1b86)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/coredump.c (ffffffff8140fa64)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/proc/base.c (ffffffff814256ce)
Location: include/linux/sched/signal.h:699
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff8142c676)
Location: include/linux/sched/signal.h:699
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
In kernel/ptrace.c (ffffffff810dcdf5)
Location: include/linux/sched/signal.h:739
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
In kernel/signal.c (ffffffff810e18f0)
Location: include/linux/sched/signal.h:739
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810eca9e)
Location: include/linux/sched/signal.h:739
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_utility.c (ffffffff8114d225)
Location: include/linux/sched/signal.h:739
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81193945)
Location: include/linux/sched/signal.h:739
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa329)
Location: include/linux/sched/signal.h:739
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
In kernel/cgroup/freezer.c (ffffffff811d0ec1)
Location: include/linux/sched/signal.h:739
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff81206397)
Location: include/linux/sched/signal.h:739
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/proc/base.c (ffffffff8149ea67)
Location: include/linux/sched/signal.h:739
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff814a5f26)
Location: include/linux/sched/signal.h:739
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
In kernel/ptrace.c (ffffffff810fd040)
Location: include/linux/sched/signal.h:740
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
In kernel/signal.c (ffffffff81101c10)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff8110de3e)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_utility.c (ffffffff8117c2c5)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff811d13ad)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ea349)
Location: include/linux/sched/signal.h:740
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
In kernel/cgroup/freezer.c (ffffffff81214a31)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff8124e697)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/proc/base.c (ffffffff81533787)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff8153b566)
Location: include/linux/sched/signal.h:740
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
In kernel/ptrace.c (ffffffff81109084)
Location: include/linux/sched/signal.h:740
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
In kernel/signal.c (ffffffff8110de29)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff8111a0ce)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_utility.c (ffffffff8118cf73)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff811e561d)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fea69)
Location: include/linux/sched/signal.h:740
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
In kernel/cgroup/freezer.c (ffffffff8122a351)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff81265a47)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/proc/base.c (ffffffff8156b977)
Location: include/linux/sched/signal.h:740
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81573896)
Location: include/linux/sched/signal.h:740
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
In kernel/ptrace.c (ffffffff81112a14)
Location: include/linux/sched/signal.h:743
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
In kernel/signal.c (ffffffff81117789)
Location: include/linux/sched/signal.h:743
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sched/build_utility.c (ffffffff8119b923)
Location: include/linux/sched/signal.h:743
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff811fb333)
Location: include/linux/sched/signal.h:743
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81214f69)
Location: include/linux/sched/signal.h:743
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
In kernel/cgroup/freezer.c (ffffffff81242311)
Location: include/linux/sched/signal.h:743
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff8127f8d9)
Location: include/linux/sched/signal.h:743
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/proc/base.c (ffffffff815a2f29)
Location: include/linux/sched/signal.h:743
Inline: True
Inline callers:
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff815ac232)
Location: include/linux/sched/signal.h:743
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
In kernel/ptrace.c (ffff800010109350)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffff80001010df68)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffff8000101198f8)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffff80001015f5e4)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffff80001019840c)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae740)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffff8000101dcdb0)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffff80001020d694)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (ffff800010428594)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffff80001043d828)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffff800010445f24)
Location: include/linux/sched/signal.h:668
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
In kernel/ptrace.c (c0362c44)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (c036628c)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (c036de10)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (c03abe18)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
```
```
In kernel/freezer.c (c03e33b0)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (c03f97e0)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (c041ee34)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (c044c08c)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (c05f1208)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (c06038b0)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (c060a33c)
Location: include/linux/sched/signal.h:668
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
In kernel/ptrace.c (c0000000001507fc)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (c0000000001553a4)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (c000000000161110)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (c0000000001b4b84)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (c0000000001f8324)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (c000000000212cd0)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (c00000000024ab1c)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (c00000000028b698)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (c0000000005387b4)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (c000000000551ce0)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (c00000000055ae2c)
Location: include/linux/sched/signal.h:668
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
In kernel/ptrace.c (ffffffe0000cca4a)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffe0000cef58)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffe0000d4626)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffe000103834)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffe0001290c2)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001381d0)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffe000154a48)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffe00016e6f2)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In fs/coredump.c (ffffffe0002c67a4)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffe0002d6a08)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffe0002db3dc)
Location: include/linux/sched/signal.h:668
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
In kernel/ptrace.c (ffffffff810a8fd9)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810ac5b6)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810b70e4)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810f3ebd)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81129855)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c964)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff81161ed9)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff8118d9f6)
Location: include/linux/sched/signal.h:668
Inline: True
```
```
In fs/coredump.c (ffffffff8135a4a5)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8136b89e)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81371519)
Location: include/linux/sched/signal.h:668
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
In kernel/ptrace.c (ffffffff810979a9)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff8109af46)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810a5a24)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810e407d)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff8111c0e5)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f3d4)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff81155139)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff81180b17)
Location: include/linux/sched/signal.h:668
Inline: True
```
```
In fs/coredump.c (ffffffff8134b14f)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8135c32e)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81361fa9)
Location: include/linux/sched/signal.h:668
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
In kernel/ptrace.c (ffffffff810a8539)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810abb16)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810b6644)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810f109d)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81127575)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a684)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff8115fca9)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff8118b7c6)
Location: include/linux/sched/signal.h:668
Inline: True
```
```
In fs/coredump.c (ffffffff81357f75)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8136936e)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff8136efe9)
Location: include/linux/sched/signal.h:668
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
In kernel/ptrace.c (ffffffff810b0669)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_setsiginfo
  - kernel/ptrace.c:ptrace_getsiginfo
```
```
In kernel/signal.c (ffffffff810b3c7f)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:do_send_sig_info
```
```
In kernel/sys.c (ffffffff810be9c4)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/autogroup.c (ffffffff810fc09d)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/freezer.c (ffffffff81133bb5)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81147144)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
```
```
In kernel/cgroup/freezer.c (ffffffff8116cfd9)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze_task
```
```
In kernel/taskstats.c (ffffffff8119913b)
Location: include/linux/sched/signal.h:668
Inline: True
```
```
In fs/coredump.c (ffffffff8136b6b9)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8137cbde)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timers_start
  - fs/proc/base.c:proc_pid_limits
```
```
In fs/proc/array.c (ffffffff81382979)
Location: include/linux/sched/signal.h:668
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
</ul>

## Differences
