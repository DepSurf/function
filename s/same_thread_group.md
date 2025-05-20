# Function: <code>same_thread_group</code>

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
In kernel/exit.c (ffffffff81082c06)
Location: include/linux/sched.h:2709
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8108ad4a)
Location: include/linux/sched.h:2709
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff8108eb90)
Location: include/linux/sched.h:2709
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:get_signal
```
```
In kernel/sys.c (ffffffff81094c15)
Location: include/linux/sched.h:2709
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/sched.h:2709
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:2709
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:2709
Inline: True
```
```
In fs/exec.c (ffffffff81213479)
Location: include/linux/sched.h:2709
Inline: True
```
```
In fs/proc/base.c (ffffffff8127e6ff)
Location: include/linux/sched.h:2709
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/fd.c (0)
Location: include/linux/sched.h:2709
Inline: True
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
In kernel/exit.c (ffffffff81085c75)
Location: include/linux/sched.h:2978
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8108de22)
Location: include/linux/sched.h:2978
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff81093733)
Location: include/linux/sched.h:2978
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (ffffffff81097e25)
Location: include/linux/sched.h:2978
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/sched.h:2978
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:2978
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:2978
Inline: True
```
```
In fs/exec.c (ffffffff81239fce)
Location: include/linux/sched.h:2978
Inline: True
```
```
In fs/proc/base.c (ffffffff812ab71f)
Location: include/linux/sched.h:2978
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_tid_comm_permission
```
```
In fs/proc/fd.c (0)
Location: include/linux/sched.h:2978
Inline: True
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
In kernel/exit.c (ffffffff8108abe5)
Location: include/linux/sched.h:3092
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff81093574)
Location: include/linux/sched.h:3092
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff810986c3)
Location: include/linux/sched.h:3092
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (ffffffff8109cdd5)
Location: include/linux/sched.h:3092
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/sched.h:3092
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/sched.h:3092
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:3092
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:3092
Inline: True
```
```
In fs/exec.c (ffffffff8124cd19)
Location: include/linux/sched.h:3092
Inline: True
```
```
In fs/proc/base.c (ffffffff812c0dff)
Location: include/linux/sched.h:3092
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_tid_comm_permission
```
```
In fs/proc/fd.c (0)
Location: include/linux/sched.h:3092
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/sched.h:3092
Inline: True
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
In kernel/exit.c (ffffffff81087b8e)
Location: include/linux/sched/signal.h:552
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff81090684)
Location: include/linux/sched/signal.h:552
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff81095984)
Location: include/linux/sched/signal.h:552
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (ffffffff81099cb5)
Location: include/linux/sched/signal.h:552
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/sched/signal.h:552
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/sched/signal.h:552
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched/signal.h:552
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched/signal.h:552
Inline: True
```
```
In fs/exec.c (ffffffff81258d4e)
Location: include/linux/sched/signal.h:552
Inline: True
```
```
In fs/proc/base.c (ffffffff812cdfeb)
Location: include/linux/sched/signal.h:552
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_tid_comm_permission
```
```
In fs/proc/fd.c (0)
Location: include/linux/sched/signal.h:552
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/sched/signal.h:552
Inline: True
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
In kernel/exit.c (ffffffff8108e91e)
Location: include/linux/sched/signal.h:553
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810974f4)
Location: include/linux/sched/signal.h:553
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff8109c7df)
Location: include/linux/sched/signal.h:553
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (ffffffff810a0995)
Location: include/linux/sched/signal.h:553
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/sched/signal.h:553
Inline: True
```
```
In kernel/time/posix-timers.c (0)
Location: include/linux/sched/signal.h:553
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched/signal.h:553
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched/signal.h:553
Inline: True
```
```
In fs/exec.c (ffffffff8127aee4)
Location: include/linux/sched/signal.h:553
Inline: True
```
```
In fs/proc/base.c (ffffffff812f2841)
Location: include/linux/sched/signal.h:553
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_tid_comm_permission
```
```
In fs/proc/fd.c (0)
Location: include/linux/sched/signal.h:553
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/sched/signal.h:553
Inline: True
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
In kernel/exit.c (ffffffff8109247b)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8109a9bf)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff8109fc68)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (ffffffff810a607b)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810c3b06)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff8111f986)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81121025)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In mm/oom_kill.c (ffffffff811f3dc3)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In fs/exec.c (ffffffff812a25c6)
Location: include/linux/sched/signal.h:581
Inline: True
```
```
In fs/proc/base.c (ffffffff8131f810)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (ffffffff81322f5d)
Location: include/linux/sched/signal.h:581
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff8144f0c4)
Location: include/linux/sched/signal.h:581
Inline: True
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
In kernel/exit.c (ffffffff8109a789)
Location: include/linux/sched/signal.h:623
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a2bef)
Location: include/linux/sched/signal.h:623
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810a8f4f)
Location: include/linux/sched/signal.h:623
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810ac76b)
Location: include/linux/sched/signal.h:623
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810ccdc6)
Location: include/linux/sched/signal.h:623
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff8112b164)
Location: include/linux/sched/signal.h:623
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112c745)
Location: include/linux/sched/signal.h:623
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In mm/oom_kill.c (ffffffff81205c05)
Location: include/linux/sched/signal.h:623
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In fs/exec.c (ffffffff812b71a5)
Location: include/linux/sched/signal.h:623
Inline: True
```
```
In fs/proc/base.c (ffffffff8133693e)
Location: include/linux/sched/signal.h:623
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (ffffffff8133a0ad)
Location: include/linux/sched/signal.h:623
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff8146c132)
Location: include/linux/sched/signal.h:623
Inline: True
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
In kernel/exit.c (ffffffff8109f2d2)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a78ba)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810aee67)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b4677)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810d51a6)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff81136355)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811370ef)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In mm/oom_kill.c (ffffffff8121c20f)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812d4b9e)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff8135e9f7)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (ffffffff8136224c)
Location: include/linux/sched/signal.h:654
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff8149916c)
Location: include/linux/sched/signal.h:654
Inline: True
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
In kernel/exit.c (ffffffff810a5862)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810adeda)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810b547e)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b83f7)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810df766)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff811423f5)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811431f4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In mm/oom_kill.c (ffffffff81229bdb)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812e671e)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff81376c57)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (ffffffff8137a4ac)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff814b309c)
Location: include/linux/sched/signal.h:646
Inline: True
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
In kernel/exit.c (ffffffff810ad403)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
```
```
In kernel/ptrace.c (ffffffff810b59ba)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810be1c0)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810bfdba)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810e7ab6)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff81150c89)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811527d6)
Location: include/linux/sched/signal.h:658
Inline: True
```
```
In mm/oom_kill.c (ffffffff81256a38)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff8131dfd6)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff813bfa24)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
```
```
In fs/proc/fd.c (ffffffff813c358c)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff81511c23)
Location: include/linux/sched/signal.h:658
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:ptracer_exception_found
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
In kernel/exit.c (ffffffff810a8ad3)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
```
```
In kernel/ptrace.c (ffffffff810b0baa)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810b94b0)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810baf7a)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810e57a6)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff8114cf0e)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114ea1f)
Location: include/linux/sched/signal.h:671
Inline: True
```
```
In mm/oom_kill.c (ffffffff812615d5)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff813294e6)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff813d18ae)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
```
```
In fs/proc/fd.c (ffffffff813d560c)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff8152ea99)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:ptracer_exception_found
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
In kernel/exit.c (ffffffff810a9bd8)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
```
```
In kernel/ptrace.c (ffffffff810b214a)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810baab5)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810bc8ae)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810e7776)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff8114f406)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114feb8)
Location: include/linux/sched/signal.h:677
Inline: True
```
```
In mm/oom_kill.c (ffffffff81265e15)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff8132f2f6)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/io_uring.c (ffffffff81393211)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_queue_async_work
```
```
In fs/proc/base.c (ffffffff813d87a5)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:comm_write
```
```
In fs/proc/fd.c (ffffffff813dc463)
Location: include/linux/sched/signal.h:677
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff8153536e)
Location: include/linux/sched/signal.h:677
Inline: True
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
In kernel/exit.c (ffffffff810bb706)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
```
```
In kernel/ptrace.c (ffffffff810c3f56)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810cd46e)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810cf28e)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810fee16)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff811735cc)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811740e8)
Location: include/linux/sched/signal.h:675
Inline: True
```
```
In mm/oom_kill.c (ffffffff812a263f)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff8137cad6)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/io_uring.c (ffffffff813e1261)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_queue_async_work
```
```
In fs/proc/base.c (ffffffff81429ed5)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:comm_write
```
```
In fs/proc/fd.c (ffffffff8142dac3)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff81593899)
Location: include/linux/sched/signal.h:675
Inline: True
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
In kernel/exit.c (ffffffff810d2146)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
```
```
In kernel/ptrace.c (ffffffff810dbe96)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810e5367)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810e7e0e)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/sched/build_policy.c (ffffffff811396f4)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff811a695f)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a8dfc)
Location: include/linux/sched/signal.h:715
Inline: True
```
```
In mm/oom_kill.c (ffffffff812fa192)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff813fbe1c)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff814a3306)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:comm_write
```
```
In fs/proc/fd.c (ffffffff814a7473)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff81635b85)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
```
In io_uring/io_uring.c (ffffffff816cc2df)
Location: include/linux/sched/signal.h:715
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rw_should_reissue
  - io_uring/io_uring.c:io_queue_iowq
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
In kernel/exit.c (ffffffff810f0bba)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
```
```
In kernel/ptrace.c (ffffffff810fbfb6)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff811059e5)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff81108b1e)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/sched/build_policy.c (ffffffff81163eb4)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff811e64ff)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e8c4c)
Location: include/linux/sched/signal.h:716
Inline: True
```
```
In mm/oom_kill.c (ffffffff813648c2)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff81484ecc)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff81538586)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:comm_write
```
```
In fs/proc/fd.c (ffffffff8153cb33)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff816ec895)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
```
In io_uring/io_uring.c (ffffffff81790313)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/rw.c (ffffffff817a309f)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
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
In kernel/exit.c (ffffffff810fcb6a)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
```
```
In kernel/ptrace.c (ffffffff81108056)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff81111c77)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff81114e2e)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/sched/build_policy.c (ffffffff81174694)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff811fab48)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd25a)
Location: include/linux/sched/signal.h:716
Inline: True
```
```
In mm/oom_kill.c (ffffffff81396d92)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff814b9e4c)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff815707cf)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:comm_write
```
```
In fs/proc/fd.c (ffffffff81574df3)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff81726cc5)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
```
In io_uring/io_uring.c (ffffffff817ce3c3)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/rw.c (ffffffff817e4052)
Location: include/linux/sched/signal.h:716
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
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
In kernel/exit.c (ffffffff811070d2)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - kernel/exit.c:__do_wait
  - kernel/exit.c:__do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
```
```
In kernel/ptrace.c (ffffffff811119e7)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff8111b617)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff8111e81e)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/sched/build_policy.c (ffffffff81182a6b)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff81210d38)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121345a)
Location: include/linux/sched/signal.h:708
Inline: True
```
```
In mm/oom_kill.c (ffffffff813c0b02)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff814ec3c8)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff815a909b)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:comm_write
```
```
In fs/proc/fd.c (ffffffff815ad7c3)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff81767f15)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
```
In io_uring/io_uring.c (ffffffff81811673)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/rw.c (ffffffff81828102)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
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
In kernel/exit.c (ffff8000100fb850)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffff800010107fc4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffff800010110328)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (ffff800010114850)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_setpgid
```
```
In kernel/sched/cputime.c (ffff80001013f138)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffff8000101ac528)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad2d8)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In mm/oom_kill.c (ffff8000102b79bc)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffff80001038ea28)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffff8000104422d8)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (ffff8000104467b4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffff8000105aa928)
Location: include/linux/sched/signal.h:646
Inline: True
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
In kernel/exit.c (c0359814)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (c0362540)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (c03696ec)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (c036cfd8)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/sched/cputime.c (c038f120)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (c03f6878)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (c03f826c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In mm/oom_kill.c (c04e464c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (c0574f8c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (c0607b18)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (c060b8c4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (c075a8c4)
Location: include/linux/sched/signal.h:646
Inline: True
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
In kernel/exit.c (c000000000142de0)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (c00000000014f3a4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (c000000000157a7c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (c00000000015c7c4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/sched/cputime.c (c00000000018e2c4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (c000000000210220)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (c000000000211528)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In mm/oom_kill.c (c00000000036f804)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (c000000000485950)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (c0000000005578d0)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (c00000000055c61c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (c000000000728830)
Location: include/linux/sched/signal.h:646
Inline: True
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
In kernel/exit.c (ffffffe0000c53ae)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffe0000cc3e6)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffe0000d16b4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (ffffffe0000d3d66)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffe0000ed890)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffe00013639c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000137314)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In mm/oom_kill.c (ffffffe0001dbc8c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffe00025e4ee)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffe0002d8f4c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (ffffffe0002dc784)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffe0003f37f8)
Location: include/linux/sched/signal.h:646
Inline: True
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
In kernel/exit.c (ffffffff8109f182)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a824a)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810af7ee)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b2767)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810d9956)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff8113aba5)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113b9a4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In mm/oom_kill.c (ffffffff8122222b)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812decfe)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff8136f237)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (ffffffff81372a8c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff814ab67c)
Location: include/linux/sched/signal.h:646
Inline: True
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
In kernel/exit.c (ffffffff8108dbb6)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff81096c0a)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff8109e120)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810a108d)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810c8beb)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff8112d5f5)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e364)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In mm/oom_kill.c (ffffffff812153db)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812cee23)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff8135fcc7)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (ffffffff8136355c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff8149c09c)
Location: include/linux/sched/signal.h:646
Inline: True
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
In kernel/exit.c (ffffffff8109f132)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a77aa)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810aed4e)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b1cc7)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810d5c96)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff811388c5)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811396c4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In mm/oom_kill.c (ffffffff8121ffcb)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812dcb0e)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff8136cd07)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (ffffffff8137055c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff814a771c)
Location: include/linux/sched/signal.h:646
Inline: True
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
In kernel/exit.c (ffffffff810a7091)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810af8ca)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/signal.c (ffffffff810b703e)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810bc88c)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/sched/cputime.c (ffffffff810e15a6)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/posix-timers.c (ffffffff811454f4)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114618e)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In mm/oom_kill.c (ffffffff8122f0c6)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812ed8b7)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/proc/base.c (ffffffff81380608)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/proc/fd.c (ffffffff81383f21)
Location: include/linux/sched/signal.h:646
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In security/yama/yama_lsm.c (ffffffff814c0088)
Location: include/linux/sched/signal.h:646
Inline: True
```
</details>
</li>
</ul>

## Differences
