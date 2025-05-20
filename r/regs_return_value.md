# Function: <code>regs_return_value</code>

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
Location: arch/x86/include/asm/ptrace.h:92
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: arch/x86/include/asm/ptrace.h:92
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
Location: arch/x86/include/asm/ptrace.h:86
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: arch/x86/include/asm/ptrace.h:86
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
Location: arch/x86/include/asm/ptrace.h:86
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: arch/x86/include/asm/ptrace.h:86
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
Location: arch/x86/include/asm/ptrace.h:86
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: arch/x86/include/asm/ptrace.h:86
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
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/ptrace.h:109
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:109
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:109
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
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
In arch/x86/entry/common.c (ffffffff81005338)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__syscall_return_slowpath
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec15d)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f653b)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/entry/common.c (ffffffff8113b90b)
Location: arch/x86/include/asm/ptrace.h:109
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ea2ad)
Location: arch/x86/include/asm/ptrace.h:109
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4f1b)
Location: arch/x86/include/asm/ptrace.h:109
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/entry/common.c (ffffffff8113cbdd)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb71d)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5e0b)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/entry/common.c (ffffffff8115fcfa)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c620)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225fdb)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/entry/common.c (ffffffff8118a224)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125b400)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff81265c7b)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/entry/common.c (ffffffff811c6764)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_kprobe.c (ffffffff812acca6)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b75d1)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/entry/common.c (ffffffff811d9384)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cebbf)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db352)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e0eca)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
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
In kernel/entry/common.c (ffffffff811eecc4)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec5bf)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9419)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fef1a)
Location: arch/x86/include/asm/ptrace.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
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
Location: arch/arm64/include/asm/ptrace.h:300
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/arm64/include/asm/ptrace.h:300
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/arm64/include/asm/ptrace.h:300
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
In arch/arm/kernel/ptrace.c (c030d198)
Location: arch/arm/include/asm/ptrace.h:87
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
```
```
In kernel/trace/trace_kprobe.c (c04822b4)
Location: arch/arm/include/asm/ptrace.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (c048d650)
Location: arch/arm/include/asm/ptrace.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In arch/powerpc/kernel/ptrace.c (c0000000000195f0)
Location: arch/powerpc/include/asm/ptrace.h:147
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
```
```
In kernel/trace/trace_kprobe.c (c0000000002ebae0)
Location: arch/powerpc/include/asm/ptrace.h:147
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (c0000000002fdd50)
Location: arch/powerpc/include/asm/ptrace.h:147
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In arch/riscv/kernel/ptrace.c (0)
Location: arch/riscv/include/asm/ptrace.h:99
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
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
In arch/x86/entry/common.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: arch/x86/include/asm/ptrace.h:107
Inline: True
```
</details>
</li>
</ul>

## Differences
