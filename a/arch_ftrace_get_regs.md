# Function: <code>arch_ftrace_get_regs</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b111)
Location: arch/x86/include/asm/ftrace.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff811abbf4)
Location: arch/x86/include/asm/ftrace.h:50
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:call_direct_funcs
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107c321)
Location: arch/x86/include/asm/ftrace.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff811ac4f4)
Location: arch/x86/include/asm/ftrace.h:50
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:call_direct_funcs
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8108a471)
Location: arch/x86/include/asm/ftrace.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff811d6103)
Location: arch/x86/include/asm/ftrace.h:50
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:call_direct_funcs
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109a9c1)
Location: arch/x86/include/asm/ftrace.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff8120b483)
Location: arch/x86/include/asm/ftrace.h:57
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:call_direct_funcs
```
```
In kernel/trace/fprobe.c (ffffffff812685fa)
Location: arch/x86/include/asm/ftrace.h:57
Inline: True
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b1401)
Location: arch/x86/include/asm/ftrace.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff81253ea3)
Location: arch/x86/include/asm/ftrace.h:43
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/fprobe.c (ffffffff812ba83a)
Location: arch/x86/include/asm/ftrace.h:43
Inline: True
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b43b1)
Location: arch/x86/include/asm/ftrace.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff8126b483)
Location: arch/x86/include/asm/ftrace.h:43
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/fprobe.c (ffffffff812ddfce)
Location: arch/x86/include/asm/ftrace.h:43
Inline: True
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb811)
Location: arch/x86/include/asm/ftrace.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff81285933)
Location: arch/x86/include/asm/ftrace.h:43
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/fprobe.c (ffffffff812fc0be)
Location: arch/x86/include/asm/ftrace.h:43
Inline: True
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
