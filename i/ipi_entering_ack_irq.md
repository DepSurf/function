# Function: <code>ipi_entering_ack_irq</code>

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
In arch/x86/kernel/irq_work.c (ffffffff81033bb6)
Location: arch/x86/include/asm/apic.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81050ad6)
Location: arch/x86/include/asm/apic.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81032dd6)
Location: arch/x86/include/asm/apic.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81050ee6)
Location: arch/x86/include/asm/apic.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81032a5a)
Location: arch/x86/include/asm/apic.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff8105379a)
Location: arch/x86/include/asm/apic.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff8190e21a)
Location: arch/x86/include/asm/apic.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff8190e7da)
Location: arch/x86/include/asm/apic.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81a0276a)
Location: arch/x86/include/asm/apic.h:533
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81a02c4a)
Location: arch/x86/include/asm/apic.h:533
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81a01de5)
Location: arch/x86/include/asm/apic.h:527
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81a02375)
Location: arch/x86/include/asm/apic.h:527
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81c01e05)
Location: arch/x86/include/asm/apic.h:527
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81c02415)
Location: arch/x86/include/asm/apic.h:527
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81c01fe5)
Location: arch/x86/include/asm/apic.h:528
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81c02665)
Location: arch/x86/include/asm/apic.h:528
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81c02015)
Location: arch/x86/include/asm/apic.h:537
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81c02695)
Location: arch/x86/include/asm/apic.h:537
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81c01ff5)
Location: arch/x86/include/asm/apic.h:537
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81c02675)
Location: arch/x86/include/asm/apic.h:537
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81c01ea5)
Location: arch/x86/include/asm/apic.h:537
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81c02525)
Location: arch/x86/include/asm/apic.h:537
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81c01fd5)
Location: arch/x86/include/asm/apic.h:537
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81c025e5)
Location: arch/x86/include/asm/apic.h:537
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
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
In arch/x86/kernel/irq_work.c (ffffffff81c02065)
Location: arch/x86/include/asm/apic.h:537
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81c02805)
Location: arch/x86/include/asm/apic.h:537
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
</details>
</li>
</ul>

## Differences
