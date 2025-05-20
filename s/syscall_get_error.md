# Function: <code>syscall_get_error</code>

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
In arch/x86/kernel/signal.c (ffffffff8102e530)
Location: arch/x86/include/asm/syscall.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102d4e0)
Location: arch/x86/include/asm/syscall.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102d384)
Location: arch/x86/include/asm/syscall.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102b5f4)
Location: arch/x86/include/asm/syscall.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102c320)
Location: arch/x86/include/asm/syscall.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102d5e0)
Location: arch/x86/include/asm/syscall.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102e82d)
Location: arch/x86/include/asm/syscall.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81030a91)
Location: arch/x86/include/asm/syscall.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In kernel/ptrace.c (ffffffff810a6c8a)
Location: arch/x86/include/asm/syscall.h:55
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff81030f11)
Location: arch/x86/include/asm/syscall.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In kernel/ptrace.c (ffffffff810ad56d)
Location: arch/x86/include/asm/syscall.h:59
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff81033c5c)
Location: arch/x86/include/asm/syscall.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In kernel/ptrace.c (ffffffff810b4d77)
Location: arch/x86/include/asm/syscall.h:50
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff810346c4)
Location: arch/x86/include/asm/syscall.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
```
In kernel/ptrace.c (ffffffff810aff57)
Location: arch/x86/include/asm/syscall.h:50
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff81036251)
Location: arch/x86/include/asm/syscall.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/ptrace.c (ffffffff810b14e8)
Location: arch/x86/include/asm/syscall.h:50
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff8103b4f2)
Location: arch/x86/include/asm/syscall.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/ptrace.c (ffffffff810c37c8)
Location: arch/x86/include/asm/syscall.h:49
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff810422a3)
Location: arch/x86/include/asm/syscall.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/ptrace.c (ffffffff810daf41)
Location: arch/x86/include/asm/syscall.h:49
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff8104b603)
Location: arch/x86/include/asm/syscall.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/ptrace.c (ffffffff810fb076)
Location: arch/x86/include/asm/syscall.h:49
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff8104be93)
Location: arch/x86/include/asm/syscall.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/ptrace.c (ffffffff81106faf)
Location: arch/x86/include/asm/syscall.h:49
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff81053113)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/signal.c:handle_signal
```
```
In kernel/ptrace.c (ffffffff811108ff)
Location: arch/x86/include/asm/syscall.h:47
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (ffff8000101079c0)
Location: arch/arm64/include/asm/syscall.h:33
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (c0361a6c)
Location: arch/arm/include/asm/syscall.h:34
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (c00000000014e228)
Location: arch/powerpc/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (ffffffe0000cb930)
Location: arch/riscv/include/asm/syscall.h:44
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff81031071)
Location: arch/x86/include/asm/syscall.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In kernel/ptrace.c (ffffffff810a78dd)
Location: arch/x86/include/asm/syscall.h:59
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff81020a91)
Location: arch/x86/include/asm/syscall.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In kernel/ptrace.c (ffffffff810962bd)
Location: arch/x86/include/asm/syscall.h:59
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff81030ed1)
Location: arch/x86/include/asm/syscall.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In kernel/ptrace.c (ffffffff810a6e3d)
Location: arch/x86/include/asm/syscall.h:59
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In arch/x86/kernel/signal.c (ffffffff81031d61)
Location: arch/x86/include/asm/syscall.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In kernel/ptrace.c (ffffffff810af10d)
Location: arch/x86/include/asm/syscall.h:59
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
</details>
</li>
</ul>

## Differences
