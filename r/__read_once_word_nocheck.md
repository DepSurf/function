# Function: <code>__read_once_word_nocheck</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81037b69)
Location: include/linux/compiler.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81040fe9)
Location: include/linux/compiler.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81082a04)
Location: include/linux/compiler.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff811cc9e6)
Location: include/linux/compiler.h:307
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff81bd372b)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81040f49)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81bd83c3)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff811c9f26)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff81bc5b9d)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81042945)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81bca200)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff811cb2d9)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff81c988e7)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81048cb3)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81c9f57d)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff811f7603)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff81e47e55)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81e4ed28)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff8123116e)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff810517dd)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810bb446)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff8127d5de)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff81052546)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810be586)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff8129a073)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff81059766)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810c5706)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff812b56f3)
Location: include/asm-generic/rwonce.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
