# Function: <code>syscall_get_arguments</code>

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
In arch/x86/entry/common.c (ffffffff810032ba)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
  - arch/x86/entry/common.c:perf_trace_sys_enter
```
```
In kernel/seccomp.c (ffffffff8113b59d)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff81162000)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81413810)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
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
In arch/x86/entry/common.c (ffffffff810039df)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff81143afd)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c425)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff8145b520)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
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
In arch/x86/entry/common.c (ffffffff8100399d)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff8114d9cc)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff81177815)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81479fef)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003849)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff8114fdfc)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff8117a493)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81483302)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff81003c93-ffffffff81003c99: syscall_get_arguments.part.6 (STB_LOCAL)
ffffffff8117ab3d-ffffffff8117ab43: syscall_get_arguments.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100389f)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff8115c3cc)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff81187c74)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff814bf34b)
Location: arch/x86/include/asm/syscall.h:113
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff81003ee7-ffffffff81003eed: syscall_get_arguments.part.6 (STB_LOCAL)
ffffffff8118839d-ffffffff811883a3: syscall_get_arguments.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004097)
Location: arch/x86/include/asm/syscall.h:117
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff8116acec)
Location: arch/x86/include/asm/syscall.h:117
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff81197304)
Location: arch/x86/include/asm/syscall.h:117
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff814f03bf)
Location: arch/x86/include/asm/syscall.h:117
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff81003890-ffffffff81003896: syscall_get_arguments.part.6 (STB_LOCAL)
ffffffff81196980-ffffffff81196986: syscall_get_arguments.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810040c7)
Location: arch/x86/include/asm/syscall.h:117
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff81178e41)
Location: arch/x86/include/asm/syscall.h:117
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a5478)
Location: arch/x86/include/asm/syscall.h:117
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
Direct callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff815042df)
Location: arch/x86/include/asm/syscall.h:117
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff81003920-ffffffff81003926: syscall_get_arguments.part.7 (STB_LOCAL)
ffffffff811a4ac0-ffffffff811a4ac6: syscall_get_arguments.part.6 (STB_LOCAL)
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
In arch/x86/entry/common.c (ffffffff81003ef3)
Location: arch/x86/include/asm/syscall.h:112
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (ffffffff810a6ab7)
Location: arch/x86/include/asm/syscall.h:112
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff81185b3a)
Location: arch/x86/include/asm/syscall.h:112
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b3013)
Location: arch/x86/include/asm/syscall.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81532413)
Location: arch/x86/include/asm/syscall.h:112
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
In arch/x86/entry/common.c (ffffffff81003ef3)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (ffffffff810ad097)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff81191ab5)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811be443)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81553253)
Location: arch/x86/include/asm/syscall.h:116
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
In arch/x86/entry/common.c (ffffffff81004edb)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (ffffffff810b4b8a)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff811a53ef)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d7e07)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff815dc645)
Location: arch/x86/include/asm/syscall.h:107
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
In kernel/ptrace.c (ffffffff810afd6a)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff8113b5bb)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff811a234f)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d4ed7)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff815fa2ea)
Location: arch/x86/include/asm/syscall.h:107
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
In kernel/ptrace.c (ffffffff810b12fa)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff8113c89b)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff811a497a)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d6727)
Location: arch/x86/include/asm/syscall.h:107
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff815dcec2)
Location: arch/x86/include/asm/syscall.h:107
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
In kernel/ptrace.c (ffffffff810c35b0)
Location: arch/x86/include/asm/syscall.h:106
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff8115f9bb)
Location: arch/x86/include/asm/syscall.h:106
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff811cdadf)
Location: arch/x86/include/asm/syscall.h:106
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff812035b7)
Location: arch/x86/include/asm/syscall.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81648822)
Location: arch/x86/include/asm/syscall.h:106
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
In kernel/ptrace.c (ffffffff810dad13)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff8118a05a)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff81201acf)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff8123e943)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff8175ec6f)
Location: arch/x86/include/asm/syscall.h:97
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
In kernel/ptrace.c (ffffffff810fae43)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff811c6587)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff812498af)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff8128c350)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff8188c58f)
Location: arch/x86/include/asm/syscall.h:97
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
In kernel/ptrace.c (ffffffff81106a64)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff811d91a7)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff8125f7bf)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff812a8dc0)
Location: arch/x86/include/asm/syscall.h:97
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff818ce9f7)
Location: arch/x86/include/asm/syscall.h:97
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
In kernel/ptrace.c (ffffffff811103b4)
Location: arch/x86/include/asm/syscall.h:95
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/entry/common.c (ffffffff811eeea3)
Location: arch/x86/include/asm/syscall.h:95
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_trace_enter
  - kernel/entry/common.c:syscall_trace_enter
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:perf_trace_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
  - kernel/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/seccomp.c (ffffffff812797cf)
Location: arch/x86/include/asm/syscall.h:95
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_syscalls.c (ffffffff812c4ad0)
Location: arch/x86/include/asm/syscall.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff819207d7)
Location: arch/x86/include/asm/syscall.h:95
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
In arch/arm64/kernel/ptrace.c (ffff80001008aa64)
Location: arch/arm64/include/asm/syscall.h:55
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:perf_trace_sys_enter
  - arch/arm64/kernel/ptrace.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (ffff800010106b00)
Location: arch/arm64/include/asm/syscall.h:55
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_seccomp
```
```
In kernel/seccomp.c (ffff8000102094c4)
Location: arch/arm64/include/asm/syscall.h:55
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffff80001023db70)
Location: arch/arm64/include/asm/syscall.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffff80001065f580)
Location: arch/arm64/include/asm/syscall.h:55
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
In arch/arm/kernel/ptrace.c (c030bdf4)
Location: arch/arm/include/asm/syscall.h:56
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:perf_trace_sys_enter
  - arch/arm/kernel/ptrace.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (c0361a1c)
Location: arch/arm/include/asm/syscall.h:56
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/seccomp.c (c0448228)
Location: arch/arm/include/asm/syscall.h:56
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (c047916c)
Location: arch/arm/include/asm/syscall.h:56
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (c0808694)
Location: arch/arm/include/asm/syscall.h:56
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
In arch/powerpc/kernel/ptrace.c (c00000000001155c)
Location: arch/powerpc/include/asm/syscall.h:73
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:perf_trace_sys_enter
  - arch/powerpc/kernel/ptrace.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (c00000000014dd54)
Location: arch/powerpc/include/asm/syscall.h:73
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (c000000000286540)
Location: arch/powerpc/include/asm/syscall.h:73
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (c0000000002cd220)
Location: arch/powerpc/include/asm/syscall.h:73
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (c000000000812140)
Location: arch/powerpc/include/asm/syscall.h:73
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b5c8a)
Location: arch/riscv/include/asm/syscall.h:65
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:perf_trace_sys_enter
  - arch/riscv/kernel/ptrace.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (ffffffe0000cb7c0)
Location: arch/riscv/include/asm/syscall.h:65
Inline: True
```
```
In kernel/seccomp.c (ffffffe00016b4ea)
Location: arch/riscv/include/asm/syscall.h:65
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffe00019316a)
Location: arch/riscv/include/asm/syscall.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffe00048c5bc)
Location: arch/riscv/include/asm/syscall.h:65
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
In arch/x86/entry/common.c (ffffffff81003ef3)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (ffffffff810a7407)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff8118a0d5)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b6a63)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff8154b833)
Location: arch/x86/include/asm/syscall.h:116
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
In arch/x86/entry/common.c (ffffffff81002523)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (ffffffff81095de7)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff8117d205)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a9853)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff8153bb13)
Location: arch/x86/include/asm/syscall.h:116
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
In arch/x86/entry/common.c (ffffffff81003ef3)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (ffffffff810a6967)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff81187ea5)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4833)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff81547573)
Location: arch/x86/include/asm/syscall.h:116
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
In arch/x86/entry/common.c (ffffffff81003fd3)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:perf_trace_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
  - arch/x86/entry/common.c:trace_event_raw_event_sys_enter
```
```
In kernel/ptrace.c (ffffffff810aeab7)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_entry
```
```
In kernel/seccomp.c (ffffffff811957f9)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c28d3)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In lib/syscall.c (ffffffff815613c3)
Location: arch/x86/include/asm/syscall.h:116
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
</details>
</li>
</ul>

## Differences
