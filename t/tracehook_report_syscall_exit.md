# Function: <code>tracehook_report_syscall_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tracehook_report_syscall_exit(struct pt_regs *regs, int step);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003540)
Location: include/linux/tracehook.h:123
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81003540-ffffffff81003605: tracehook_report_syscall_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tracehook_report_syscall_exit(struct pt_regs *regs, int step);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810037b0)
Location: include/linux/tracehook.h:123
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff810037b0-ffffffff81003875: tracehook_report_syscall_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tracehook_report_syscall_exit(struct pt_regs *regs, int step);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003780)
Location: include/linux/tracehook.h:123
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81003780-ffffffff81003840: tracehook_report_syscall_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tracehook_report_syscall_exit(struct pt_regs *regs, int step);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003610)
Location: include/linux/tracehook.h:123
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81003610-ffffffff810036cf: tracehook_report_syscall_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tracehook_report_syscall_exit(struct pt_regs *regs, int step);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003640)
Location: include/linux/tracehook.h:123
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81003640-ffffffff8100370c: tracehook_report_syscall_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tracehook_report_syscall_exit(struct pt_regs *regs, int step);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003d50)
Location: include/linux/tracehook.h:123
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81003d50-ffffffff81003e30: tracehook_report_syscall_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003973)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004203)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004203)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100527f)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__syscall_return_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113b859)
Location: include/linux/tracehook.h:125
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113cb33)
Location: include/linux/tracehook.h:125
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8115fc53)
Location: include/linux/tracehook.h:125
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff80001008ef00)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (c030d0a8)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c000000000019544)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/ptrace.c (ffffffe0000b6484)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_exit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004203)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810026d3)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810041c3)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810042e3)
Location: include/linux/tracehook.h:124
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
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
</ul>
