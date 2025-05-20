# Function: <code>is_trace_idt_enabled</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff81040356)
Location: arch/x86/include/asm/desc.h:465
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/tracepoint.c (ffffffff810663f1)
Location: arch/x86/include/asm/desc.h:465
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
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
In arch/x86/kernel/cpu/common.c (ffffffff81041284)
Location: arch/x86/include/asm/desc.h:465
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff81066181)
Location: arch/x86/include/asm/desc.h:465
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
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
In arch/x86/kernel/cpu/common.c (ffffffff81040cd1)
Location: arch/x86/include/asm/desc.h:465
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff810696a1)
Location: arch/x86/include/asm/desc.h:465
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
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
In arch/x86/kernel/cpu/common.c (ffffffff8103ea55)
Location: arch/x86/include/asm/desc.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff810688f6)
Location: arch/x86/include/asm/desc.h:572
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
