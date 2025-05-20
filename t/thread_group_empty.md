# Function: <code>thread_group_empty</code>

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
In kernel/fork.c (ffffffff81080672)
Location: include/linux/sched.h:2720
Inline: True
Inline callers:
  - kernel/fork.c:SyS_unshare
```
```
In kernel/exit.c (ffffffff810820d8)
Location: include/linux/sched.h:2720
Inline: True
Inline callers:
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/ptrace.c (ffffffff8108ad17)
Location: include/linux/sched.h:2720
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff8108de25)
Location: include/linux/sched.h:2720
Inline: True
Inline callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:exit_signals
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f3061)
Location: include/linux/sched.h:2720
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
```
```
In kernel/user_namespace.c (ffffffff8111ed22)
Location: include/linux/sched.h:2720
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff8113ee96)
Location: include/linux/sched.h:2720
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In fs/exec.c (ffffffff812132ef)
Location: include/linux/sched.h:2720
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813334a8)
Location: include/linux/sched.h:2720
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff810824b2)
Location: include/linux/sched.h:2989
Inline: True
Inline callers:
  - kernel/fork.c:SyS_unshare
```
```
In kernel/exit.c (ffffffff81085b95)
Location: include/linux/sched.h:2989
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8108e5ce)
Location: include/linux/sched.h:2989
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81091119)
Location: include/linux/sched.h:2989
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810fa171)
Location: include/linux/sched.h:2989
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
```
```
In kernel/user_namespace.c (ffffffff81126c72)
Location: include/linux/sched.h:2989
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff811474cb)
Location: include/linux/sched.h:2989
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff811a52d8)
Location: include/linux/sched.h:2989
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff81239e3a)
Location: include/linux/sched.h:2989
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81368349)
Location: include/linux/sched.h:2989
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff81086f12)
Location: include/linux/sched.h:3103
Inline: True
Inline callers:
  - kernel/fork.c:SyS_unshare
```
```
In kernel/exit.c (ffffffff8108ab05)
Location: include/linux/sched.h:3103
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81093164)
Location: include/linux/sched.h:3103
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81096084)
Location: include/linux/sched.h:3103
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81107af1)
Location: include/linux/sched.h:3103
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule
```
```
In kernel/user_namespace.c (ffffffff81130762)
Location: include/linux/sched.h:3103
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff8115136b)
Location: include/linux/sched.h:3103
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff811b4fc8)
Location: include/linux/sched.h:3103
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff8124cb6a)
Location: include/linux/sched.h:3103
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8137eb59)
Location: include/linux/sched.h:3103
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff81083d67)
Location: include/linux/sched/signal.h:563
Inline: True
Inline callers:
  - kernel/fork.c:SyS_unshare
```
```
In kernel/exit.c (ffffffff81087afe)
Location: include/linux/sched/signal.h:563
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8109026a)
Location: include/linux/sched/signal.h:563
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81093064)
Location: include/linux/sched/signal.h:563
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81109c90)
Location: include/linux/sched/signal.h:563
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffff81131dd2)
Location: include/linux/sched/signal.h:563
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff81153964)
Location: include/linux/sched/signal.h:563
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff811bc49c)
Location: include/linux/sched/signal.h:563
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff81258bc9)
Location: include/linux/sched/signal.h:563
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813929e9)
Location: include/linux/sched/signal.h:563
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff8108a657)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/fork.c:SyS_unshare
```
```
In kernel/exit.c (ffffffff8108e88e)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810970da)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff81099f44)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81114e5d)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffff8113ebf2)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff81160164)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff811d109c)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff8127ad62)
Location: include/linux/sched/signal.h:564
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813b8049)
Location: include/linux/sched/signal.h:564
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff8108dead)
Location: include/linux/sched/signal.h:592
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/exit.c (ffffffff810923e8)
Location: include/linux/sched/signal.h:592
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/ptrace.c (ffffffff8109a602)
Location: include/linux/sched/signal.h:592
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff8109df1c)
Location: include/linux/sched/signal.h:592
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811215f6)
Location: include/linux/sched/signal.h:592
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffff8114ce42)
Location: include/linux/sched/signal.h:592
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff8116f09c)
Location: include/linux/sched/signal.h:592
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff811f22cc)
Location: include/linux/sched/signal.h:592
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812a214e)
Location: include/linux/sched/signal.h:592
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813e8c2f)
Location: include/linux/sched/signal.h:592
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff8109613d)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/exit.c (ffffffff8109a6d3)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
```
```
In kernel/ptrace.c (ffffffff810a2842)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810a622c)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112cd16)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffff81159a62)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff8117cb9c)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff8120413c)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812b70ce)
Location: include/linux/sched/signal.h:634
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81403434)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff8109a66a)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (ffffffff8109f239)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a74c5)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810aaf3f)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811376df)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffff811661b2)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff81189a51)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff8121b50a)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812d4961)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff8143003d)
Location: include/linux/sched/signal.h:665
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff810a0c2a)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (ffffffff810a57c9)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810adab6)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810b153f)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81143637)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffff81172072)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff81195994)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff81228e9a)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812e64e1)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff81449d9d)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff810a7a9d)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (ffffffff810ad3af)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:exit_notify
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810b54d6)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810b853f)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/user_namespace.c (ffffffff811845f2)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff811a9ce4)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_tgid_alloc
```
```
In mm/oom_kill.c (ffffffff81255a2d)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff8131de25)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff8149b79d)
Location: include/linux/sched/signal.h:669
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff810a380d)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/exit.c (ffffffff810a734a)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:exit_notify
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810b06d8)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810b37ef)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/user_namespace.c (ffffffff81181612)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff811a7304)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_tgid_alloc
```
```
In mm/oom_kill.c (ffffffff812606af)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff81329335)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff814b922d)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff810a443d)
Location: include/linux/sched/signal.h:688
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/exit.c (ffffffff810a83da)
Location: include/linux/sched/signal.h:688
Inline: True
Inline callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:exit_notify
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810b1c58)
Location: include/linux/sched/signal.h:688
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810b4d0f)
Location: include/linux/sched/signal.h:688
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/user_namespace.c (ffffffff81182732)
Location: include/linux/sched/signal.h:688
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff811a7e33)
Location: include/linux/sched/signal.h:688
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_tgid_alloc
```
```
In mm/oom_kill.c (ffffffff8126529f)
Location: include/linux/sched/signal.h:688
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff8132f16f)
Location: include/linux/sched/signal.h:688
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff814bf07d)
Location: include/linux/sched/signal.h:688
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff810b5c5d)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/exit.c (ffffffff810b9e3a)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:exit_notify
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810c3e28)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810c6faf)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/user_namespace.c (ffffffff811aa702)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff811d1963)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_tgid_alloc
```
```
In mm/oom_kill.c (ffffffff812a1acf)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff8137c94f)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff81517a9d)
Location: include/linux/sched/signal.h:686
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff810cc149)
Location: include/linux/sched/signal.h:726
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/exit.c (ffffffff810d0a32)
Location: include/linux/sched/signal.h:726
Inline: True
Inline callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810dbe7f)
Location: include/linux/sched/signal.h:726
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
```
```
In kernel/signal.c (ffffffff810debfb)
Location: include/linux/sched/signal.h:726
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/user_namespace.c (ffffffff811dbd42)
Location: include/linux/sched/signal.h:726
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff81207113)
Location: include/linux/sched/signal.h:726
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff812f99cd)
Location: include/linux/sched/signal.h:726
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff813fbc8f)
Location: include/linux/sched/signal.h:726
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff815aa4d3)
Location: include/linux/sched/signal.h:726
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff810e97f9)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/exit.c (ffffffff810ef3e2)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810fbf9f)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
```
```
In kernel/signal.c (ffffffff810ff2ab)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/user_namespace.c (ffffffff81221592)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff8124f483)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff81363b3d)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff81484d3f)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff816547d3)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff810f5409)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/exit.c (ffffffff810fb402)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8110803f)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
```
```
In kernel/signal.c (ffffffff8110b2fb)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/user_namespace.c (ffffffff81237a42)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff81266833)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff8139600d)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff814b9cbf)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff8168d013)
Location: include/linux/sched/signal.h:727
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/exit.c (ffffffff811047e2)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:exit_notify
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff811119cf)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_detach
```
```
In kernel/signal.c (ffffffff81114959)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/user_namespace.c (ffffffff8125127e)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff81280723)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff813bfdd1)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff814ec228)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff816c9503)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffff8000100f55fc)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (ffff8000100fb708)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffff8000101070ac)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffff80001010d190)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101adc30)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffff8000101e6724)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffff80001020da28)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffff8000102b6210)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffff80001038e680)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffff800010533b18)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (c0353d30)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (c035977c)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c0361790)
Location: include/linux/sched/signal.h:657
Inline: True
```
```
In kernel/signal.c (c0365418)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (c03f8a5c)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (c0426790)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (c044c600)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (c04e392c)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (c0574cd4)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (c06eb348)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (c00000000013b6f8)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (c000000000142c0c)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c00000000014ed08)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (c000000000154280)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (c000000000211c70)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (c0000000002565e0)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (c00000000028bd40)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (c00000000036e5dc)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (c000000000485578)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (c0000000006819c0)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffe0000c19d2)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (ffffffe0000c5352)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffe0000cbbf2)
Location: include/linux/sched/signal.h:657
Inline: True
```
```
In kernel/signal.c (ffffffe0000ce690)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffe00013779c)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffe00015ba64)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffe00016eb12)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffe0001db034)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffe00025e1d4)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffe000393f36)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff8109a54a)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (ffffffff8109f0e9)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a7e26)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810ab8af)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113bde7)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffff8116a692)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff8118dfb4)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff812214ea)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812deac1)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff8144237d)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff81088f8a)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (ffffffff8108db1d)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810967f2)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff8109a24f)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e9c7)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffff8115d892)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff811810c4)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff8121469a)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812cec01)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff81432de1)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff8109a4fa)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (ffffffff8109f099)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a7386)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810aae0f)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81139b07)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffff81168462)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff8118bd84)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff8121f28a)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812dc8d1)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff8143e51d)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/fork.c (ffffffff810a217a)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:pidfd_poll
```
```
In kernel/exit.c (ffffffff810a6fe2)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:will_become_orphaned_pgrp
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810af312)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffffffff810b2eef)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:complete_signal
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811465f7)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
```
```
In kernel/user_namespace.c (ffffffff81175b52)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
```
```
In kernel/taskstats.c (ffffffff81199701)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In mm/oom_kill.c (ffffffff8122e302)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:task_will_free_mem
```
```
In fs/exec.c (ffffffff812ed691)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/keys/keyctl.c (ffffffff81455696)
Location: include/linux/sched/signal.h:657
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
</details>
</li>
</ul>

## Differences
