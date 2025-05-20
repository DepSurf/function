# Function: <code>int3_emulate_call</code>

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
In arch/x86/kernel/alternative.c (ffffffff828aa0ba)
Location: arch/x86/include/asm/text-patching.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106d1ff)
Location: arch/x86/include/asm/text-patching.h:81
Inline: True
Inline callers:
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
In arch/x86/kernel/alternative.c (ffffffff828ad11d)
Location: arch/x86/include/asm/text-patching.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106e9ef)
Location: arch/x86/include/asm/text-patching.h:81
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
In arch/x86/kernel/alternative.c (ffffffff81bbe13a)
Location: arch/x86/include/asm/text-patching.h:144
Inline: True
Inline callers:
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
In arch/x86/kernel/alternative.c (ffffffff81c36a0b)
Location: arch/x86/include/asm/text-patching.h:156
Inline: True
Inline callers:
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
In arch/x86/kernel/alternative.c (ffffffff81c28eae)
Location: arch/x86/include/asm/text-patching.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107ac81)
Location: arch/x86/include/asm/text-patching.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
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
In arch/x86/kernel/alternative.c (ffffffff81d4703e)
Location: arch/x86/include/asm/text-patching.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81088e0e)
Location: arch/x86/include/asm/text-patching.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
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
In arch/x86/kernel/alternative.c (ffffffff81f15618)
Location: arch/x86/include/asm/text-patching.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8109908e)
Location: arch/x86/include/asm/text-patching.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
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
In arch/x86/kernel/alternative.c (ffffffff820bcac1)
Location: arch/x86/include/asm/text-patching.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810af84e)
Location: arch/x86/include/asm/text-patching.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
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
In arch/x86/kernel/alternative.c (ffffffff8213e335)
Location: arch/x86/include/asm/text-patching.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810b286e)
Location: arch/x86/include/asm/text-patching.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call_indirect
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
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
In arch/x86/kernel/alternative.c (ffffffff82220325)
Location: arch/x86/include/asm/text-patching.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810b96f4)
Location: arch/x86/include/asm/text-patching.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_emulate_call
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
In arch/x86/kernel/alternative.c (ffffffff8289b12f)
Location: arch/x86/include/asm/text-patching.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106d98f)
Location: arch/x86/include/asm/text-patching.h:81
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
In arch/x86/kernel/alternative.c (ffffffff828933ed)
Location: arch/x86/include/asm/text-patching.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105ddaf)
Location: arch/x86/include/asm/text-patching.h:81
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
In arch/x86/kernel/alternative.c (ffffffff828ae10f)
Location: arch/x86/include/asm/text-patching.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106de3f)
Location: arch/x86/include/asm/text-patching.h:81
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
In arch/x86/kernel/alternative.c (ffffffff828ae12d)
Location: arch/x86/include/asm/text-patching.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:int3_exception_notify
```
```
In arch/x86/kernel/ftrace.c (ffffffff810700bf)
Location: arch/x86/include/asm/text-patching.h:81
Inline: True
```
</details>
</li>
</ul>

## Differences
