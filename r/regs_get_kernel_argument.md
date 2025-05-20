# Function: <code>regs_get_kernel_argument</code>

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
In kernel/trace/trace_kprobe.c (ffffffff811b5e40)
Location: arch/x86/include/asm/ptrace.h:300
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811c4e2f)
Location: arch/x86/include/asm/ptrace.h:306
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811d0933)
Location: arch/x86/include/asm/ptrace.h:306
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811ec403)
Location: arch/x86/include/asm/ptrace.h:319
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811ea553)
Location: arch/x86/include/asm/ptrace.h:339
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811eb9ba)
Location: arch/x86/include/asm/ptrace.h:342
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff8121c8e2)
Location: arch/x86/include/asm/ptrace.h:342
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff8125b6cf)
Location: arch/x86/include/asm/ptrace.h:346
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff812acfc1)
Location: arch/x86/include/asm/ptrace.h:346
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff812cf180)
Location: arch/x86/include/asm/ptrace.h:346
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e1193)
Location: arch/x86/include/asm/ptrace.h:346
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
In kernel/trace/trace_kprobe.c (ffffffff812ecb80)
Location: arch/x86/include/asm/ptrace.h:346
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812ff1e3)
Location: arch/x86/include/asm/ptrace.h:346
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff80001024f1f0)
Location: arch/arm64/include/asm/ptrace.h:323
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
</details>
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
In kernel/trace/trace_kprobe.c (ffffffff811c8f53)
Location: arch/x86/include/asm/ptrace.h:306
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811bbd33)
Location: arch/x86/include/asm/ptrace.h:306
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811c6d23)
Location: arch/x86/include/asm/ptrace.h:306
Inline: True
Inline callers:
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
In kernel/trace/trace_kprobe.c (ffffffff811d4f83)
Location: arch/x86/include/asm/ptrace.h:306
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
</details>
</li>
</ul>

## Differences
