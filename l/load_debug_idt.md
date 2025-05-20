# Function: <code>load_debug_idt</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff81040346)
Location: arch/x86/include/asm/desc.h:448
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/tracepoint.c (ffffffff810663d6)
Location: arch/x86/include/asm/desc.h:448
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
In arch/x86/kernel/cpu/common.c (ffffffff81041085)
Location: arch/x86/include/asm/desc.h:448
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff81066166)
Location: arch/x86/include/asm/desc.h:448
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
In arch/x86/kernel/cpu/common.c (ffffffff81040ad2)
Location: arch/x86/include/asm/desc.h:448
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff81069686)
Location: arch/x86/include/asm/desc.h:448
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
In arch/x86/kernel/cpu/common.c (ffffffff8103ecaf)
Location: arch/x86/include/asm/desc.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/tracepoint.c (ffffffff8106892b)
Location: arch/x86/include/asm/desc.h:555
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
In arch/x86/kernel/cpu/common.c (ffffffff8104197f)
Location: arch/x86/include/asm/desc.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810578cc)
Location: arch/x86/include/asm/desc.h:404
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
In arch/x86/kernel/cpu/common.c (ffffffff810431f1)
Location: arch/x86/include/asm/desc.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105a7d0)
Location: arch/x86/include/asm/desc.h:404
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
In arch/x86/kernel/cpu/common.c (ffffffff81044859)
Location: arch/x86/include/asm/desc.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81060450)
Location: arch/x86/include/asm/desc.h:404
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
In arch/x86/kernel/cpu/common.c (ffffffff81046e30)
Location: arch/x86/include/asm/desc.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063d2e)
Location: arch/x86/include/asm/desc.h:404
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
In arch/x86/kernel/cpu/common.c (ffffffff810475b9)
Location: arch/x86/include/asm/desc.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810643dd)
Location: arch/x86/include/asm/desc.h:404
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
In arch/x86/kernel/cpu/common.c (ffffffff81047730)
Location: arch/x86/include/asm/desc.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063ecd)
Location: arch/x86/include/asm/desc.h:404
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
In arch/x86/kernel/cpu/common.c (ffffffff81036931)
Location: arch/x86/include/asm/desc.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810541d0)
Location: arch/x86/include/asm/desc.h:404
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
In arch/x86/kernel/cpu/common.c (ffffffff81047570)
Location: arch/x86/include/asm/desc.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106437d)
Location: arch/x86/include/asm/desc.h:404
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
In arch/x86/kernel/cpu/common.c (ffffffff81048979)
Location: arch/x86/include/asm/desc.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81065944)
Location: arch/x86/include/asm/desc.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
</details>
</li>
</ul>

## Differences
