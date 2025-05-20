# Function: <code>regs_get_kernel_stack_nth_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811b5ed0)
Location: arch/x86/include/asm/ptrace.h:250
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811c4c16)
Location: arch/x86/include/asm/ptrace.h:256
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811d08b6)
Location: arch/x86/include/asm/ptrace.h:256
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811ec386)
Location: arch/x86/include/asm/ptrace.h:269
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811ea4d6)
Location: arch/x86/include/asm/ptrace.h:289
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811eb93d)
Location: arch/x86/include/asm/ptrace.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff8121c865)
Location: arch/x86/include/asm/ptrace.h:292
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff8125b655)
Location: arch/x86/include/asm/ptrace.h:296
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff812acf3e)
Location: arch/x86/include/asm/ptrace.h:296
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff812cf2c3)
Location: arch/x86/include/asm/ptrace.h:296
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e1628)
Location: arch/x86/include/asm/ptrace.h:296
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff812eccc3)
Location: arch/x86/include/asm/ptrace.h:296
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812ff678)
Location: arch/x86/include/asm/ptrace.h:296
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/trace/trace_kprobe.c (ffffffff811c8ed6)
Location: arch/x86/include/asm/ptrace.h:256
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811bbcb6)
Location: arch/x86/include/asm/ptrace.h:256
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811c6ca6)
Location: arch/x86/include/asm/ptrace.h:256
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811d4f06)
Location: arch/x86/include/asm/ptrace.h:256
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
</details>
</li>
</ul>

## Differences
