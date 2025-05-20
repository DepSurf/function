# Function: <code>task_pid_vnr</code>

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
In kernel/fork.c (ffffffff810800c6)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - kernel/fork.c:SyS_set_tid_address
```
```
In kernel/exit.c (ffffffff81082b7b)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/capability.c (ffffffff8108a433)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - kernel/capability.c:SyS_capget
  - kernel/capability.c:SyS_capset
```
```
In kernel/signal.c (ffffffff8108ed57)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:get_signal
```
```
In kernel/sys.c (ffffffff81093ad0)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/sched/core.c (ffffffff810aceec)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/futex.c (ffffffff810ff871)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
```
In kernel/cgroup.c (ffffffff81118c08)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - kernel/cgroup.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff8113bb05)
Location: include/linux/sched.h:1926
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff8126711c)
Location: include/linux/sched.h:1926
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81269833)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
```
```
In fs/coredump.c (ffffffff8126f92e)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/msg.c (ffffffff81326514)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In block/ioprio.c (ffffffff813cde7c)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_get
```
```
In lib/dynamic_debug.c (ffffffff81413eed)
Location: include/linux/sched.h:1926
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff81081e66)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - kernel/fork.c:SyS_set_tid_address
```
```
In kernel/exit.c (ffffffff81085bdd)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/capability.c (ffffffff8108d696)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capget
```
```
In kernel/signal.c (ffffffff81092559)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
```
In kernel/sys.c (ffffffff81097e64)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/sched/core.c (ffffffff810af97c)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/futex.c (ffffffff8110a2ea)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup.c (ffffffff811208b2)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/seccomp.c (ffffffff811442bf)
Location: include/linux/sched.h:2065
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81294875)
Location: include/linux/sched.h:2065
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81295b33)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
```
```
In fs/coredump.c (ffffffff8129aff0)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/msg.c (ffffffff8135b158)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In block/ioprio.c (ffffffff814124c5)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff8145bb3d)
Location: include/linux/sched.h:2065
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff810868c6)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - kernel/fork.c:SyS_set_tid_address
```
```
In kernel/exit.c (ffffffff8108ab4d)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/capability.c (ffffffff810925d6)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capget
```
```
In kernel/signal.c (ffffffff810974e9)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
```
In kernel/sys.c (ffffffff8109ce14)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/sched/core.c (ffffffff810b5aac)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/futex.c (ffffffff81111ada)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup.c (ffffffff81128d9f)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/seccomp.c (ffffffff8114e16e)
Location: include/linux/sched.h:2152
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff812a9525)
Location: include/linux/sched.h:2152
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812aa783)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
```
```
In fs/coredump.c (ffffffff812afbd3)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/msg.c (ffffffff8137177a)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In block/ioprio.c (ffffffff8142d925)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff8147a61d)
Location: include/linux/sched.h:2152
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff81083616)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/fork.c:SyS_set_tid_address
```
```
In kernel/exit.c (ffffffff81087a2f)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/capability.c (ffffffff8108f76d)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capget
```
```
In kernel/signal.c (ffffffff810947f9)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
```
In kernel/sys.c (ffffffff81099cf4)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/sched/core.c (ffffffff810b1d3c)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110a3c5)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffff81112ef8)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a2e1)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/seccomp.c (ffffffff81150805)
Location: include/linux/sched.h:1156
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff812b5e82)
Location: include/linux/sched.h:1156
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812b8f0f)
Location: include/linux/sched.h:1156
Inline: True
```
```
In fs/coredump.c (ffffffff812bcede)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/msg.c (ffffffff81384b2b)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In block/ioprio.c (ffffffff8143ac66)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff814837dc)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff81089ef6)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/fork.c:SyS_set_tid_address
```
```
In kernel/exit.c (ffffffff8108e7bf)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/capability.c (ffffffff8109662d)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/capability.c:SyS_capset
  - kernel/capability.c:SyS_capget
```
```
In kernel/signal.c (ffffffff8109b699)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
```
In kernel/sys.c (ffffffff810a09d4)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/sched/core.c (ffffffff810b911c)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81115585)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffff8111e495)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff8112da66)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81136fc9)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff8115ca39)
Location: include/linux/sched.h:1156
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812c80a0)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff812d972f)
Location: include/linux/sched.h:1156
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812dc810)
Location: include/linux/sched.h:1156
Inline: True
```
```
In fs/coredump.c (ffffffff812e07b8)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/msg.c (ffffffff813a8e51)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In block/ioprio.c (ffffffff81466c86)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff814bf81c)
Location: include/linux/sched.h:1156
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff8108a9dd)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff81092359)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/capability.c (ffffffff8109966c)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
```
In kernel/signal.c (ffffffff8109f75a)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
```
In kernel/sys.c (ffffffff810a6142)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810c0c0c)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81121d25)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffff8112afba)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff8113bd75)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811457b6)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff8116bdbd)
Location: include/linux/sched.h:1248
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812f1702)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff81303ff4)
Location: include/linux/sched.h:1248
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813078fd)
Location: include/linux/sched.h:1248
Inline: True
```
```
In fs/coredump.c (ffffffff8130cac8)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In block/ioprio.c (ffffffff8149a364)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff814f0660)
Location: include/linux/sched.h:1248
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff8109297d)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff8109a660)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/capability.c (ffffffff810a19f0)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
```
In kernel/signal.c (ffffffff810a79e5)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810ac7af)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810c9f7c)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d445)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffff81136e32)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff811475f5)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151376)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff81177fb3)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In fs/userfaultfd.c (ffffffff813060c2)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff81319744)
Location: include/linux/sched.h:1250
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8131d10d)
Location: include/linux/sched.h:1250
Inline: True
```
```
In fs/coredump.c (ffffffff813224de)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In block/ioprio.c (ffffffff814b4674)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff81504580)
Location: include/linux/sched.h:1250
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff81096841)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff8109f1ab)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810a6438)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
```
In kernel/signal.c (ffffffff810ae199)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b46bb)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810d1c1c)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81137e45)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffff8113fc11)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff81152865)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c644)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff81184d7f)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (ffffffff81327662)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff8134240e)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81345d52)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/coredump.c (ffffffff81349683)
Location: include/linux/sched.h:1322
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff813cef06)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff814e2b98)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff8153271a)
Location: include/linux/sched.h:1322
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff8109cf11)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff810a573b)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810aca18)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
```
In kernel/signal.c (ffffffff810b47a9)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b843b)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810dbbfc)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81143eb5)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffff8114b7f1)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff8115e4b5)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81167e0c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff81192233)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In fs/userfaultfd.c (ffffffff8133a442)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff8135a844)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8135e055)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/coredump.c (ffffffff81361923)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff813e85d6)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff814fbf58)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff8155355a)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff810a3b11)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff810ac458)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810b4708)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/signal.c (ffffffff810bcf30)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810bfdfd)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e4ac0)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811538c5)
Location: include/linux/sched.h:1357
Inline: True
```
```
In kernel/futex.c (ffffffff8115c50e)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:wake_futex_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff8116e835)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81179c09)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff811a5774)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (ffffffff813745db)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff8139e93e)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
```
```
In fs/compat_binfmt_elf.c (ffffffff813a2abc)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
```
```
In fs/coredump.c (ffffffff813a7837)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/ext4/sysfs.c (ffffffff814351a2)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff8155bc00)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff815dc94a)
Location: include/linux/sched.h:1357
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff8109f261)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff810a7b11)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810af8f6)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/signal.c (ffffffff810b8190)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810bafc2)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e260b)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114fd05)
Location: include/linux/sched.h:1416
Inline: True
```
```
In kernel/futex.c (ffffffff811588ef)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:wake_futex_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff8116b243)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81176979)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff811a272d)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (ffffffff81382543)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff813aff1e)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_prstatus
  - fs/binfmt_elf.c:fill_prstatus
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3b2c)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
```
```
In fs/coredump.c (ffffffff813b86bf)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/ext4/sysfs.c (ffffffff8144db83)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff81577d66)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff815fa8ca)
Location: include/linux/sched.h:1416
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff810a0131)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff810a9954)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810b0ea5)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff810b1ec6)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b971f)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810bc8fa)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e43bb)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81151145)
Location: include/linux/sched.h:1438
Inline: True
```
```
In kernel/futex.c (ffffffff81159c64)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff8116bdc3)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177389)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff811a334d)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (ffffffff813895c9)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff813b7402)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813bab01)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/coredump.c (ffffffff813bf6ff)
Location: include/linux/sched.h:1438
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff8145363f)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff8157faa6)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff815dd4a7)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
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
In kernel/fork.c (ffffffff810b1541)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff810bb460)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810c2eca)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff810c4380)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810cbd2f)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810cf2da)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810fb0cb)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81175515)
Location: include/linux/sched.h:1536
Inline: True
```
```
In kernel/futex.c (ffffffff8117ea84)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff811919a3)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119eaf9)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff811cca2d)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (ffffffff813d68b4)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff814070e2)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a801)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/coredump.c (ffffffff8140f52f)
Location: include/linux/sched.h:1536
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff814a7654)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff815e4d67)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff81648e57)
Location: include/linux/sched.h:1536
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
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
In kernel/fork.c (ffffffff810c7840)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff810d1e37)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810da2e4)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff810dab2f)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810e2ca1)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810e7e61)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff81117564)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a9e39)
Location: include/linux/sched.h:1548
Inline: True
```
```
In kernel/futex/core.c (ffffffff811b2da8)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/futex/core.c:handle_futex_death
```
```
In kernel/futex/pi.c (ffffffff811b5780)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff811c1332)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf2b0)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff81200d2b)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (ffffffff814601ab)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff8147bc47)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f566)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/coredump.c (ffffffff8148518d)
Location: include/linux/sched.h:1548
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff8152eea3)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff81693da5)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff8175f301)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
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
In kernel/fork.c (ffffffff810e43a0)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff810f0897)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810fa2c4)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff810fac3f)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff81103151)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff81108b71)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff8113ea9b)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e9da9)
Location: include/linux/sched.h:1570
Inline: True
```
```
In kernel/futex/core.c (ffffffff811f3c93)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/futex/core.c:handle_futex_death
```
```
In kernel/futex/pi.c (ffffffff811f68a0)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff81203982)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81212c40)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff81248a6b)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (ffffffff814f0012)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff8150e687)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff815126b6)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/coredump.c (ffffffff8151863c)
Location: include/linux/sched.h:1570
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff815cd33a)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In security/apparmor/notify.c (ffffffff816ea22f)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_unotif
```
```
In block/ioprio.c (ffffffff81752dbb)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff8188c9f6)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108c04b)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
```
```
In kernel/fork.c (ffffffff810efa30)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff810fc854)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff81106452)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff81106dbf)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8110f391)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff81114e81)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff8114b29b)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fe4b9)
Location: include/linux/sched.h:1579
Inline: True
```
```
In kernel/futex/core.c (ffffffff81208423)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/futex/core.c:handle_futex_death
```
```
In kernel/futex/pi.c (ffffffff8120b092)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff81218ee2)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228550)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff8125fe5b)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (ffffffff81526e10)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff81545e47)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8154a0f2)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/coredump.c (ffffffff81550196)
Location: include/linux/sched.h:1579
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff81604bda)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In security/apparmor/notify.c (ffffffff8172373a)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_v3_unotif
```
```
In block/ioprio.c (ffffffff8178ee7b)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff818cee56)
Location: include/linux/sched.h:1579
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81093dbb)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show
```
```
In kernel/fork.c (ffffffff810f8e40)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff81105f54)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff8110fda2)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
  - kernel/capability.c:__do_sys_capget
```
```
In kernel/ptrace.c (ffffffff8111070f)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff81118d11)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff8111e871)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_gettid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff81156ecb)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81214849)
Location: include/linux/pid.h:238
Inline: True
```
```
In kernel/futex/core.c (ffffffff8121f2b3)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/futex/core.c:handle_futex_death
```
```
In kernel/futex/pi.c (ffffffff81222647)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
```
In kernel/cgroup/cgroup.c (ffffffff81230a72)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81240352)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff81279fa6)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (ffffffff8155bb91)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff8157b328)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8157f0ff)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
```
In fs/coredump.c (ffffffff81586025)
Location: include/linux/pid.h:238
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff8163d89a)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In security/apparmor/notify.c (ffffffff81764a36)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_v3_unotif
```
```
In block/ioprio.c (ffffffff817d17ab)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff81920c3e)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_emit_prefix
```
```
In drivers/gpu/drm/drm_ioctl.c (ffffffff81c9e04c)
Location: include/linux/pid.h:238
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioctl.c:drm_getclient
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
In kernel/fork.c (ffff8000100f11c4)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/fork.c:__arm64_sys_set_tid_address
```
```
In kernel/exit.c (ffff8000100fb668)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffff800010106670)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/capability.c:__arm64_sys_capset
  - kernel/capability.c:__arm64_sys_capget
```
```
In kernel/signal.c (ffff800010110864)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
```
In kernel/sys.c (ffff8000101148b8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_setpgid
  - kernel/sys.c:__arm64_sys_gettid
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
```
```
In kernel/sched/core.c (ffff80001013b9dc)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae3ec)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffff8000101b80e4)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffff8000101cecf4)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101da918)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffff800010209ce4)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In fs/userfaultfd.c (ffff8000103f9534)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffff80001041fe3c)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffff800010421aec)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
```
```
In fs/coredump.c (ffff80001042806c)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/ext4/sysfs.c (ffff8000104c13b8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffff8000105fdfd4)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - block/ioprio.c:__arm64_sys_ioprio_get
  - block/ioprio.c:__arm64_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffff80001065f924)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (c035326c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_set_tid_address
```
```
In kernel/exit.c (c0359598)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (c03613c8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capget
```
```
In kernel/signal.c (c0369b30)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
```
In kernel/sys.c (c036d020)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/sched/core.c (c038b25c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (c03f92e8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (c0402054)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (c04121a8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (c041d230)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/seccomp.c (c0447bfc)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (c05cd4cc)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (c05e63b8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf.c:fill_psinfo
```
```
In fs/binfmt_elf_fdpic.c (c05e9640)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:fill_prstatus
  - fs/binfmt_elf_fdpic.c:fill_prstatus
```
```
In fs/coredump.c (c05f0d18)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/ext4/sysfs.c (c0684fe8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (c07a91d8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
```
```
In lib/dynamic_debug.c (c0808960)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e4340)
Location: include/linux/sched.h:1316
Inline: True
```
```
In kernel/fork.c (c000000000136d30)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_set_tid_address
```
```
In kernel/exit.c (c000000000142c78)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (c00000000014d9ac)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capget
```
```
In kernel/signal.c (c000000000158094)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
```
In kernel/sys.c (c00000000015c8c0)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/sched/core.c (c000000000189870)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (c000000000212924)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (c00000000021d770)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (c000000000238cf0)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (c0000000002489b4)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (c000000000286ff0)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In fs/userfaultfd.c (c0000000005019bc)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (c00000000052ed04)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/compat_binfmt_elf.c (c000000000532924)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/coredump.c (c000000000538280)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/ext4/sysfs.c (c0000000005f7e9c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (c000000000797b1c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
```
```
In lib/dynamic_debug.c (c0000000008125b0)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffe0000c1260)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_set_tid_address
```
```
In kernel/exit.c (ffffffe0000c52e2)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffe0000cb422)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capget
```
```
In kernel/signal.c (ffffffe0000d1a08)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
```
In kernel/sys.c (ffffffe0000d3da0)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/sched/core.c (ffffffe0000eaf3c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000137f44)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffe00013cdf6)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffe00014952c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000152ea0)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffe00016a7b2)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In fs/userfaultfd.c (ffffffe0002a891a)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffe0002c0e14)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/coredump.c (ffffffe0002c640a)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffe00033c958)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffe000439bc8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffe00048c818)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff81096831)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff8109f05b)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810a6d88)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
```
In kernel/signal.c (ffffffff810aeb19)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b27ab)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810d606c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c665)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffff81143e11)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff81156ad5)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116042c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff8118a853)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In fs/userfaultfd.c (ffffffff81332a22)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff81352e24)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81356635)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/coredump.c (ffffffff81359f03)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff813e0bb6)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff814f4538)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff8154bb3a)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff810852b1)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff8108da8f)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff81095768)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
```
In kernel/signal.c (ffffffff8109d469)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810a10cc)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810c46fc)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f105)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffff81137901)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff81149df5)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115369c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff8117d97d)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In fs/userfaultfd.c (ffffffff81323529)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff81343b04)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813472f5)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/coredump.c (ffffffff8134abb3)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff813d1636)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff814e4a48)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff8153be1a)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff810967e1)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff8109f00b)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810a62e8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
```
In kernel/signal.c (ffffffff810ae079)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b1d0b)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810d2e9c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a385)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffff81141cc1)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff811548a5)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e1fc)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff81188623)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In fs/userfaultfd.c (ffffffff813304f2)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff813508f4)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81354105)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/coredump.c (ffffffff813579d3)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff813ddf36)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff814f05c8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff8154787a)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
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
In kernel/fork.c (ffffffff8109e671)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
```
In kernel/exit.c (ffffffff810a6f52)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/capability.c (ffffffff810ae3c8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
```
In kernel/signal.c (ffffffff810b62e9)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810bc8d3)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__x64_sys_gettid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810dd985)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146d75)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
```
In kernel/futex.c (ffffffff8114f27d)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/cgroup/cgroup.c (ffffffff811617a5)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b62c)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/seccomp.c (ffffffff81195f78)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In fs/userfaultfd.c (ffffffff81342e40)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff81363e79)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813652a8)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
```
```
In fs/coredump.c (ffffffff8136b0b3)
Location: include/linux/sched.h:1316
Inline: True
```
```
In fs/ext4/sysfs.c (ffffffff813f3356)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In block/ioprio.c (ffffffff8150967e)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
```
In lib/dynamic_debug.c (ffffffff815616ca)
Location: include/linux/sched.h:1316
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
</details>
</li>
</ul>

## Differences
