# Function: <code>thread_group_leader</code>

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
In kernel/fork.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In kernel/exit.c (ffffffff810824aa)
Location: include/linux/sched.h:2692
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8108ad05)
Location: include/linux/sched.h:2692
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:2692
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/sched.h:2692
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
In kernel/fork.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In kernel/exit.c (ffffffff81086f44)
Location: include/linux/sched.h:2961
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8108dcf5)
Location: include/linux/sched.h:2961
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:2961
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/sched.h:2961
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
In kernel/fork.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In kernel/exit.c (ffffffff8108beb0)
Location: include/linux/sched.h:3075
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81092b85)
Location: include/linux/sched.h:3075
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:3075
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/sched.h:3075
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
In kernel/fork.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In kernel/exit.c (ffffffff810874aa)
Location: include/linux/sched/signal.h:535
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8108fca3)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched/signal.h:535
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/sched/signal.h:535
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
In kernel/fork.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In kernel/exit.c (ffffffff8108e23a)
Location: include/linux/sched/signal.h:536
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81096b73)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched/signal.h:536
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/linux/sched/signal.h:536
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
In kernel/fork.c (ffffffff8108d0f7)
Location: include/linux/sched/signal.h:564
Inline: True
```
```
In kernel/exit.c (ffffffff810923de)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/ptrace.c (ffffffff8109a4a5)
Location: include/linux/sched/signal.h:564
Inline: True
```
```
In kernel/sys.c (ffffffff810a606a)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81120dd4)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
```
In kernel/acct.c (ffffffff811363c5)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff8113e51b)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff8114e486)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff8116f328)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff811f2c21)
Location: include/linux/sched/signal.h:564
Inline: True
```
```
In fs/exec.c (ffffffff812a21aa)
Location: include/linux/sched/signal.h:564
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81304037)
Location: include/linux/sched/signal.h:564
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81307938)
Location: include/linux/sched/signal.h:564
Inline: True
```
```
In fs/proc/base.c (ffffffff8131f78b)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff8144ed77)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff81094e0f)
Location: include/linux/sched/signal.h:606
Inline: True
```
```
In kernel/exit.c (ffffffff8109a6c9)
Location: include/linux/sched/signal.h:606
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/ptrace.c (ffffffff810a2275)
Location: include/linux/sched/signal.h:606
Inline: True
```
```
In kernel/sys.c (ffffffff810ac75a)
Location: include/linux/sched/signal.h:606
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112c4f4)
Location: include/linux/sched/signal.h:606
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
```
In kernel/acct.c (ffffffff81141b55)
Location: include/linux/sched/signal.h:606
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff81149f4b)
Location: include/linux/sched/signal.h:606
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff8115b166)
Location: include/linux/sched/signal.h:606
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff8117ce28)
Location: include/linux/sched/signal.h:606
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In mm/oom_kill.c (ffffffff81204c41)
Location: include/linux/sched/signal.h:606
Inline: True
```
```
In fs/exec.c (ffffffff812b712e)
Location: include/linux/sched/signal.h:606
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81319787)
Location: include/linux/sched/signal.h:606
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8131d148)
Location: include/linux/sched/signal.h:606
Inline: True
```
```
In fs/proc/base.c (ffffffff813368b9)
Location: include/linux/sched/signal.h:606
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff8146bd47)
Location: include/linux/sched/signal.h:606
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff81099467)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109f22d)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a6f25)
Location: include/linux/sched/signal.h:637
Inline: True
```
```
In kernel/sys.c (ffffffff810b4666)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81136e97)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
```
```
In kernel/acct.c (ffffffff8114cf3e)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff81155c7d)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff81167804)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff81189cea)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812d49b4)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff8134244d)
Location: include/linux/sched/signal.h:637
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81345d91)
Location: include/linux/sched/signal.h:637
Inline: True
```
```
In fs/proc/base.c (ffffffff8135e904)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff81498d25)
Location: include/linux/sched/signal.h:637
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff8109fa61)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a57bd)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810ad355)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In kernel/sys.c (ffffffff810b83e6)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811431d4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/acct.c (ffffffff81158c0e)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff811618bd)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff811736c4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff81195bfa)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812e6534)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff8135a883)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8135e094)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/proc/base.c (ffffffff81376b64)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff814b2bb5)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff810a6b04)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810ad3a3)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810b5585)
Location: include/linux/sched/signal.h:652
Inline: True
```
```
In kernel/sys.c (ffffffff810bfda9)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/acct.c (ffffffff8116981e)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff81172d7d)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff811855e4)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff811aadd5)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff8131de9d)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff8139e97d)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_prstatus
```
```
In fs/compat_binfmt_elf.c (ffffffff813a2afb)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
```
```
In fs/proc/base.c (ffffffff813bf8d9)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff81511bac)
Location: include/linux/sched/signal.h:652
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:ptracer_exception_found
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff810a2616)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a8a73)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810b0785)
Location: include/linux/sched/signal.h:665
Inline: True
```
```
In kernel/sys.c (ffffffff810baf69)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/acct.c (ffffffff81165f70)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff8116fa3d)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff811826f4)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff811a8385)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/task_iter.c (ffffffff81218524)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In fs/exec.c (ffffffff813293ad)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff813aff62)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_prstatus
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3b70)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
```
```
In fs/proc/base.c (ffffffff813d1763)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff8152ea06)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:ptracer_exception_found
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff810a3309)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a99fa)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810b1d05)
Location: include/linux/sched/signal.h:671
Inline: True
```
```
In kernel/sys.c (ffffffff810bc89d)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/acct.c (ffffffff81166c9a)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff8117066d)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff81183854)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff811a8f05)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/task_iter.c (ffffffff8121b9f4)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In fs/exec.c (ffffffff8132f1bd)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff813b7446)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813bab45)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/proc/base.c (ffffffff813d8659)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff815354da)
Location: include/linux/sched/signal.h:671
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff810b4a94)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810bb506)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810c41c5)
Location: include/linux/sched/signal.h:669
Inline: True
```
```
In kernel/sys.c (ffffffff810cf27d)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/acct.c (ffffffff8118c45a)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff81196b9d)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff811ab934)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff811d2a6e)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/task_iter.c (ffffffff812528f4)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In fs/exec.c (ffffffff8137c99d)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff81407126)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a845)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/proc/base.c (ffffffff81429d89)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff81593aaa)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff810caf60)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810d1eef)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810dbe75)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
```
```
In kernel/sys.c (ffffffff810e7dfd)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/acct.c (ffffffff811bb840)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff811c6ad7)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff811dd0ab)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff812073f2)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/task_iter.c (ffffffff8129a9b5)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In fs/exec.c (ffffffff813fbcc6)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff8147bc8b)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f5aa)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/proc/base.c (ffffffff814a3206)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff81635ad7)
Location: include/linux/sched/signal.h:709
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff810e850d)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810f094f)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810fbf95)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
```
```
In kernel/sys.c (ffffffff81108b0d)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/acct.c (ffffffff811fd6a5)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff812095c7)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff81222a6b)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff8124f782)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/task_iter.c (ffffffff812f7208)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In fs/exec.c (ffffffff81484d76)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff8150e6cb)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff815126fa)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/proc/base.c (ffffffff81538486)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff816ec7e7)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff810f416c)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810fc90c)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff81108035)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
```
```
In kernel/sys.c (ffffffff81114e1d)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/acct.c (ffffffff81212825)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff8121ed17)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff812390cb)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff81266b32)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/task_iter.c (ffffffff813250d8)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In fs/exec.c (ffffffff814b9cf6)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff81545e8b)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8154a136)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/proc/base.c (ffffffff815706c9)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff81726c17)
Location: include/linux/sched/signal.h:710
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff810fe7a5)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff811047e2)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff811119c5)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
```
```
In kernel/signal.c (ffffffff81114959)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff8111e80d)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/acct.c (ffffffff81229eb5)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff812369a7)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/user_namespace.c (ffffffff8125127e)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/pid_namespace.c (ffffffff81252d9b)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/taskstats.c (ffffffff81280723)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tsacct.c (ffffffff81280a55)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/task_iter.c (ffffffff81348a58)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In mm/oom_kill.c (ffffffff813bfdd1)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff814ec228)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff8157b36c)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8157f147)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In security/keys/keyctl.c (ffffffff816c9503)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff81767e67)
Location: include/linux/sched/signal.h:702
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffff8000100f4014)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffff8000100fb700)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffff8000101071fc)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In kernel/sys.c (ffff800010114844)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad2ac)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/acct.c (ffff8000101c812c)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffff8000101d2b48)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffff8000101e79e0)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffff80001020dec8)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffff80001038e70c)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffff80001041fe88)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffff8000104239e8)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/proc/base.c (ffff80001044220c)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffff8000105aabac)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (c0352a88)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c0359770)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c0361820)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In kernel/sys.c (c036cfc8)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (c03f8258)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/acct.c (c040f118)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (c04159ec)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (c0427dbc)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (c044c994)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (c0574d34)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (c05e8384)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/binfmt_elf_fdpic.c (c05e9450)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:fill_prstatus
```
```
In fs/proc/base.c (c0607a74)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (c075a3f4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (c00000000013a3dc)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c000000000142c00)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c00000000014e408)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In kernel/sys.c (c00000000015c7b4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (c00000000021156c)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/acct.c (c000000000230780)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (c00000000023da30)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (c000000000258360)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (c00000000028c094)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (c000000000485620)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (c00000000052ed68)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/compat_binfmt_elf.c (c000000000532988)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/proc/base.c (c0000000005577a0)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (c00000000072811c)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffe0000c07e8)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffe0000c534a)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffe0000cbcba)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In kernel/sys.c (ffffffe0000d3d5c)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001372f6)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/acct.c (ffffffe000148094)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffe00014c3de)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffe00015ce2c)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffe00016ed66)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffe00025e26c)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffe0002c0e52)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/proc/base.c (ffffffe0002d8ee4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffe0003f3638)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff81099381)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109f0dd)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a76c5)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In kernel/sys.c (ffffffff810b2756)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113b984)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/acct.c (ffffffff8115122e)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff81159edd)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff8116bce4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff8118e21a)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812deb14)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff81352e63)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81356674)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/proc/base.c (ffffffff8136f144)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff814ab195)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff81087dd1)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108db11)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810960a5)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In kernel/sys.c (ffffffff810a107a)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e344)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/acct.c (ffffffff811444f1)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff8114d1cd)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff8115eee4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff8118133d)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812cec48)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff81343b43)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81347334)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/proc/base.c (ffffffff8135fbd4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff8149bbb5)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff81099331)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109f08d)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a6c25)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In kernel/sys.c (ffffffff810b1cb6)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811396a4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/acct.c (ffffffff8114f0de)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff81157cad)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff81169ab4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff8118bfea)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812dc924)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff81350933)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81354144)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/proc/base.c (ffffffff8136cc14)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff814a7235)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
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
In kernel/fork.c (ffffffff810a0f6a)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a6fd6)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810aeef5)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In kernel/sys.c (ffffffff810bc87b)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146165)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/acct.c (ffffffff8115beee)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/cgroup/cgroup.c (ffffffff81164cfd)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
```
```
In kernel/pid_namespace.c (ffffffff811771d4)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tsacct.c (ffffffff8119996a)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/exec.c (ffffffff812ed6d0)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/binfmt_elf.c (ffffffff81363ebd)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8136790f)
Location: include/linux/sched/signal.h:629
Inline: True
```
```
In fs/proc/base.c (ffffffff81380519)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
```
```
In security/yama/yama_lsm.c (ffffffff814bfc2f)
Location: include/linux/sched/signal.h:629
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
```
</details>
</li>
</ul>

## Differences
