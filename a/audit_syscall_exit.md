# Function: <code>audit_syscall_exit</code>

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
In arch/x86/entry/common.c (ffffffff81003616)
Location: include/linux/audit.h:163
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
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
In arch/x86/entry/common.c (ffffffff81003886)
Location: include/linux/audit.h:266
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
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
In arch/x86/entry/common.c (ffffffff81003846)
Location: include/linux/audit.h:266
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
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
In arch/x86/entry/common.c (ffffffff810036d6)
Location: include/linux/audit.h:265
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
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
In arch/x86/entry/common.c (ffffffff81003716)
Location: include/linux/audit.h:257
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
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
In arch/x86/entry/common.c (ffffffff81003e35)
Location: include/linux/audit.h:267
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
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
In arch/x86/entry/common.c (ffffffff81003935)
Location: include/linux/audit.h:266
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
In arch/x86/entry/common.c (ffffffff810041c5)
Location: include/linux/audit.h:309
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
In arch/x86/entry/common.c (ffffffff810041c5)
Location: include/linux/audit.h:309
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
In arch/x86/entry/common.c (ffffffff8100525a)
Location: include/linux/audit.h:326
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
In kernel/entry/common.c (ffffffff8113b82d)
Location: include/linux/audit.h:343
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
In kernel/entry/common.c (ffffffff8113cb0d)
Location: include/linux/audit.h:343
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
In kernel/entry/common.c (ffffffff8115fc2d)
Location: include/linux/audit.h:343
Inline: True
Inline callers:
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
In kernel/entry/common.c (ffffffff8118a13d)
Location: include/linux/audit.h:369
Inline: True
Inline callers:
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
In kernel/entry/common.c (ffffffff811c667d)
Location: include/linux/audit.h:366
Inline: True
Inline callers:
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
In kernel/entry/common.c (ffffffff811d929d)
Location: include/linux/audit.h:365
Inline: True
Inline callers:
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
In kernel/entry/common.c (ffffffff811eebdd)
Location: include/linux/audit.h:364
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
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
In arch/arm64/kernel/ptrace.c (ffff80001008ee88)
Location: include/linux/audit.h:309
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
In arch/arm/kernel/ptrace.c (c030d060)
Location: include/linux/audit.h:309
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
In arch/powerpc/kernel/ptrace.c (c000000000019500)
Location: include/linux/audit.h:309
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b645e)
Location: include/linux/audit.h:309
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
In arch/x86/entry/common.c (ffffffff810041c5)
Location: include/linux/audit.h:309
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
In arch/x86/entry/common.c (ffffffff81002695)
Location: include/linux/audit.h:309
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
In arch/x86/entry/common.c (ffffffff81004185)
Location: include/linux/audit.h:309
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
In arch/x86/entry/common.c (ffffffff810042a5)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
</details>
</li>
</ul>

## Differences
