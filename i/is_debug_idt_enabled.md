# Function: <code>is_debug_idt_enabled</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff81040338)
Location: arch/x86/include/asm/desc.h:440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/tracepoint.c (ffffffff810663cb)
Location: arch/x86/include/asm/desc.h:440
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
In arch/x86/kernel/cpu/common.c (ffffffff81041076)
Location: arch/x86/include/asm/desc.h:440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff8106615b)
Location: arch/x86/include/asm/desc.h:440
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
In arch/x86/kernel/cpu/common.c (ffffffff81040ac3)
Location: arch/x86/include/asm/desc.h:440
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff8106967b)
Location: arch/x86/include/asm/desc.h:440
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
In arch/x86/kernel/cpu/common.c (ffffffff8103ea46)
Location: arch/x86/include/asm/desc.h:547
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff810688eb)
Location: arch/x86/include/asm/desc.h:547
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
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
In arch/x86/kernel/cpu/common.c (ffffffff81041733)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057747)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/cpu/common.c (ffffffff81043003)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105a627)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/cpu/common.c (ffffffff8104466b)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810602a7)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/cpu/common.c (ffffffff81046c19)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063bae)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/cpu/common.c (ffffffff81047399)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106425e)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047519)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063d4e)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/cpu/common.c (ffffffff8103669f)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105405e)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/cpu/common.c (ffffffff81047359)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810641fe)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
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
In arch/x86/kernel/cpu/common.c (ffffffff81048759)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810657be)
Location: arch/x86/include/asm/desc.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
</ul>

## Differences
