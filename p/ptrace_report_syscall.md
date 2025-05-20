# Function: <code>ptrace_report_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003568)
Location: include/linux/tracehook.h:59
Inline: True
Inline callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100342d)
Location: include/linux/tracehook.h:59
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003409)
Location: include/linux/tracehook.h:59
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810031d1)
Location: include/linux/tracehook.h:59
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100311e)
Location: include/linux/tracehook.h:59
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810038fe)
Location: include/linux/tracehook.h:59
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
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
Location: include/linux/tracehook.h:60
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
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
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
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
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
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
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__syscall_return_slowpath
  - arch/x86/entry/common.c:__syscall_return_slowpath
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
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
In kernel/entry/common.c (ffffffff8113b870)
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
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
In kernel/entry/common.c (ffffffff8113cb45)
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
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
In kernel/entry/common.c (ffffffff8115fc65)
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8118a181)
Location: include/linux/ptrace.h:412
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811c66c1)
Location: include/linux/ptrace.h:403
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811d92e1)
Location: include/linux/ptrace.h:403
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_exit_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811eec21)
Location: include/linux/ptrace.h:407
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_trace_enter
  - kernel/entry/common.c:syscall_trace_enter
```
</details>
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
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
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
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
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
In arch/powerpc/kernel/ptrace.c (c00000000001957c)
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
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
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_exit
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_exit
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_enter
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_enter
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
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
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
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
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
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
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
Location: include/linux/tracehook.h:57
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
</details>
</li>
</ul>

## Differences
