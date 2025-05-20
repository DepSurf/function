# Function: <code>syscall_get_nr</code>

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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In kernel/seccomp.c (ffffffff8113be8f)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In lib/syscall.c (0)
Location: arch/x86/include/asm/syscall.h:43
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In kernel/seccomp.c (ffffffff811444f5)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In lib/syscall.c (0)
Location: arch/x86/include/asm/syscall.h:43
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In kernel/seccomp.c (ffffffff8114e391)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff811770f8)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In lib/syscall.c (0)
Location: arch/x86/include/asm/syscall.h:43
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In kernel/seccomp.c (ffffffff81150a31)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In lib/syscall.c (0)
Location: arch/x86/include/asm/syscall.h:43
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In kernel/seccomp.c (ffffffff8115d22e)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
```
```
In lib/syscall.c (0)
Location: arch/x86/include/asm/syscall.h:43
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
In arch/x86/entry/common.c (ffffffff81003752)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:trace_event_raw_event_sys_exit
```
```
In arch/x86/kernel/signal.c (ffffffff8102d5cf)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103d834)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/seccomp.c (ffffffff8116c0c9)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff811967cb)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff814f0374)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/entry/common.c (ffffffff810037e2)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:trace_event_raw_event_sys_exit
```
```
In arch/x86/kernel/signal.c (ffffffff8102e81c)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103edc4)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/seccomp.c (ffffffff81179ae9)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a490b)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81504294)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/entry/common.c (ffffffff8100392e)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:trace_event_raw_event_sys_exit
```
```
In arch/x86/kernel/signal.c (ffffffff81030a80)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041a1c)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/ptrace.c (ffffffff810a6aaf)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff811868c9)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b284b)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81532407)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/entry/common.c (ffffffff8100392e)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:trace_event_raw_event_sys_exit
```
```
In arch/x86/kernel/signal.c (ffffffff81030f00)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104219c)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/ptrace.c (ffffffff810ad08f)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff81192849)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811bde3b)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81553247)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/entry/common.c (ffffffff81004bf7)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:trace_event_raw_event_sys_exit
```
```
In arch/x86/kernel/signal.c (ffffffff81033c47)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ptrace.c (ffffffff81045744)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/ptrace.c (ffffffff810b4b82)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff811a7689)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d7bd3)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff815dc62a)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/signal.c (ffffffff810346af)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104518f)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/ptrace.c (ffffffff810afd62)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff8113b237)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:trace_event_raw_event_sys_exit
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113bcf9)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff811a4e3a)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d4ca3)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff815fa2aa)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/signal.c (ffffffff8103623a)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104689a)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/ptrace.c (ffffffff810b12f2)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff8113c527)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:trace_event_raw_event_sys_exit
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113cfe9)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff811a5a9a)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d64f3)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff815dce82)
Location: arch/x86/include/asm/syscall.h:39
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/signal.c (ffffffff8103b4da)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
```
```
In kernel/ptrace.c (ffffffff810c35a7)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff8115f647)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:trace_event_raw_event_sys_exit
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff81160109)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff811cf205)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff81203383)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff816487e2)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/signal.c (ffffffff8104228d)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
```
```
In kernel/ptrace.c (ffffffff810dad0a)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff81189a87)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:trace_event_raw_event_sys_exit
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8118a5f1)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff81203375)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff8123e1c1)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff8175ec1a)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/signal.c (ffffffff8104b5ed)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
```
```
In kernel/ptrace.c (ffffffff810fae3a)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff811c5f24)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:trace_event_raw_event_sys_exit
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811c6b91)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff8124b235)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff8128bb91)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff8188c53a)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/signal.c (ffffffff8104be7d)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
```
```
In kernel/ptrace.c (ffffffff81106a5c)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff811d8b24)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:trace_event_raw_event_sys_exit
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811d98b1)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff81262553)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff812a8aa1)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff818ce9a2)
Location: arch/x86/include/asm/syscall.h:38
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/signal.c (ffffffff810530fd)
Location: arch/x86/include/asm/syscall.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/syscall.h:36
Inline: True
```
```
In kernel/ptrace.c (ffffffff811103ac)
Location: arch/x86/include/asm/syscall.h:36
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff811eedca)
Location: arch/x86/include/asm/syscall.h:36
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_trace_enter
  - kernel/entry/common.c:perf_trace_sys_exit
  - kernel/entry/common.c:trace_event_raw_event_sys_exit
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811ef561)
Location: arch/x86/include/asm/syscall.h:36
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff8127c793)
Location: arch/x86/include/asm/syscall.h:36
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff812c47b1)
Location: arch/x86/include/asm/syscall.h:36
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81920782)
Location: arch/x86/include/asm/syscall.h:36
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/arm64/kernel/ptrace.c (0)
Location: arch/arm64/include/asm/syscall.h:20
Inline: True
```
```
In kernel/ptrace.c (0)
Location: arch/arm64/include/asm/syscall.h:20
Inline: True
```
```
In kernel/seccomp.c (0)
Location: arch/arm64/include/asm/syscall.h:20
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: arch/arm64/include/asm/syscall.h:20
Inline: True
```
```
In lib/syscall.c (0)
Location: arch/arm64/include/asm/syscall.h:20
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
In arch/arm/kernel/ptrace.c (c030b7e4)
Location: arch/arm/include/asm/syscall.h:22
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:perf_trace_sys_exit
  - arch/arm/kernel/ptrace.c:trace_event_raw_event_sys_exit
```
```
In kernel/ptrace.c (c03619d4)
Location: arch/arm/include/asm/syscall.h:22
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/seccomp.c (c044901c)
Location: arch/arm/include/asm/syscall.h:22
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (c0478984)
Location: arch/arm/include/asm/syscall.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (c080867c)
Location: arch/arm/include/asm/syscall.h:22
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
In arch/powerpc/kernel/ptrace.c (c0000000000116f8)
Location: arch/powerpc/include/asm/syscall.h:21
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_exit
  - arch/powerpc/kernel/ptrace.c:trace_event_raw_event_sys_exit
```
```
In kernel/ptrace.c (c00000000014dd40)
Location: arch/powerpc/include/asm/syscall.h:21
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (c00000000028763c)
Location: arch/powerpc/include/asm/syscall.h:21
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (c0000000002cc6a0)
Location: arch/powerpc/include/asm/syscall.h:21
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (c000000000812124)
Location: arch/powerpc/include/asm/syscall.h:21
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b5c00)
Location: arch/riscv/include/asm/syscall.h:25
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:perf_trace_sys_exit
  - arch/riscv/kernel/ptrace.c:trace_event_raw_event_sys_exit
```
```
In kernel/ptrace.c (ffffffe0000cb7bc)
Location: arch/riscv/include/asm/syscall.h:25
Inline: True
```
```
In kernel/seccomp.c (ffffffe00016c022)
Location: arch/riscv/include/asm/syscall.h:25
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffe0001931e2)
Location: arch/riscv/include/asm/syscall.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffe00048c59c)
Location: arch/riscv/include/asm/syscall.h:25
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
In arch/x86/entry/common.c (ffffffff8100392e)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:trace_event_raw_event_sys_exit
```
```
In arch/x86/kernel/signal.c (ffffffff81031060)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104231c)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/ptrace.c (ffffffff810a73ff)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff8118ae69)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b645b)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff8154b827)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/entry/common.c (ffffffff81001e0e)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:trace_event_raw_event_sys_exit
```
```
In arch/x86/kernel/signal.c (ffffffff81020a80)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ptrace.c (ffffffff810319dc)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/ptrace.c (ffffffff81095ddf)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff8117df89)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a925b)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff8153bb07)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/entry/common.c (ffffffff8100392e)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:trace_event_raw_event_sys_exit
```
```
In arch/x86/kernel/signal.c (ffffffff81030ec0)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104215c)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/ptrace.c (ffffffff810a695f)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff81188c39)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b422b)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81547567)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/entry/common.c (ffffffff810039fe)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_exit
  - arch/x86/entry/common.c:trace_event_raw_event_sys_exit
```
```
In arch/x86/kernel/signal.c (ffffffff81031d50)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104353c)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg32
```
```
In kernel/ptrace.c (ffffffff810aeaaf)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff811965a9)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c22cb)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff815613b7)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
</details>
</li>
</ul>

## Differences
