# Function: <code>int3_emulate_jmp</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff828aa0da)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106d220)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:ftrace_int3_handler
  - arch/x86/kernel/ftrace.c:ftrace_int3_handler
  - arch/x86/kernel/ftrace.c:ftrace_int3_handler
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
In arch/x86/kernel/alternative.c (ffffffff828ad13d)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106ea10)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
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
In arch/x86/kernel/alternative.c (ffffffff81bbe112)
Location: arch/x86/include/asm/text-patching.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
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
In arch/x86/kernel/alternative.c (ffffffff81c369c2)
Location: arch/x86/include/asm/text-patching.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
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
In arch/x86/kernel/alternative.c (ffffffff81c28e65)
Location: arch/x86/include/asm/text-patching.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107acd1)
Location: arch/x86/include/asm/text-patching.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_loop
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jcc
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
In arch/x86/kernel/alternative.c (ffffffff81d46ff5)
Location: arch/x86/include/asm/text-patching.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81088e7e)
Location: arch/x86/include/asm/text-patching.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_loop
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jcc
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
In arch/x86/kernel/alternative.c (ffffffff81f155de)
Location: arch/x86/include/asm/text-patching.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8109910e)
Location: arch/x86/include/asm/text-patching.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_loop
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jcc
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
In arch/x86/kernel/alternative.c (ffffffff820bcacc)
Location: arch/x86/include/asm/text-patching.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810af8de)
Location: arch/x86/include/asm/text-patching.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_loop
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jcc
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
In arch/x86/kernel/alternative.c (ffffffff8213e340)
Location: arch/x86/include/asm/text-patching.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810b28fe)
Location: arch/x86/include/asm/text-patching.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_loop
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jcc
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
In arch/x86/kernel/alternative.c (ffffffff82220330)
Location: arch/x86/include/asm/text-patching.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810b9d5e)
Location: arch/x86/include/asm/text-patching.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_loop
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jcc
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_jmp
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_ret
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8289b14f)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106d9b0)
Location: arch/x86/include/asm/text-patching.h:61
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
In arch/x86/kernel/alternative.c (ffffffff8289340d)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105ddd0)
Location: arch/x86/include/asm/text-patching.h:61
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
In arch/x86/kernel/alternative.c (ffffffff828ae12f)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106de60)
Location: arch/x86/include/asm/text-patching.h:61
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
In arch/x86/kernel/alternative.c (ffffffff828ae14d)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff810700e0)
Location: arch/x86/include/asm/text-patching.h:61
Inline: True
```
</details>
</li>
</ul>

## Differences
