# Function: <code>ftrace_get_regs</code>

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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b0f5)
Location: include/linux/ftrace.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff811abbdb)
Location: include/linux/ftrace.h:109
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107c305)
Location: include/linux/ftrace.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff811ac4db)
Location: include/linux/ftrace.h:109
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8108a455)
Location: include/linux/ftrace.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff811d60fa)
Location: include/linux/ftrace.h:109
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109a9a5)
Location: include/linux/ftrace.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff8120b47a)
Location: include/linux/ftrace.h:121
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:call_direct_funcs
```
```
In kernel/trace/fprobe.c (ffffffff812685f1)
Location: include/linux/ftrace.h:121
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b13e5)
Location: include/linux/ftrace.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff81253e9a)
Location: include/linux/ftrace.h:121
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/fprobe.c (ffffffff812ba831)
Location: include/linux/ftrace.h:121
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b4395)
Location: include/linux/ftrace.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff8126b47a)
Location: include/linux/ftrace.h:134
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/fprobe.c (ffffffff812ddfc5)
Location: include/linux/ftrace.h:134
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb7f5)
Location: include/linux/ftrace.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff8128592a)
Location: include/linux/ftrace.h:134
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/fprobe.c (ffffffff812fc0b5)
Location: include/linux/ftrace.h:134
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
