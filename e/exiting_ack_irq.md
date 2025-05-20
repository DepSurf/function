# Function: <code>exiting_ack_irq</code>

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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81048f00)
Location: arch/x86/include/asm/apic.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81049030)
Location: arch/x86/include/asm/apic.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049850)
Location: arch/x86/include/asm/apic.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104911b)
Location: arch/x86/include/asm/apic.h:662
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8104923b)
Location: arch/x86/include/asm/apic.h:662
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049a5b)
Location: arch/x86/include/asm/apic.h:662
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104b1e6)
Location: arch/x86/include/asm/apic.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8104b696)
Location: arch/x86/include/asm/apic.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104be56)
Location: arch/x86/include/asm/apic.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8190e336)
Location: arch/x86/include/asm/apic.h:641
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8190e436)
Location: arch/x86/include/asm/apic.h:641
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8190e536)
Location: arch/x86/include/asm/apic.h:641
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a0285c)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a0292c)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a029fc)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a01ee4)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a01fc4)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a020a4)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c01f04)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c01fe4)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c020c4)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020e4)
Location: arch/x86/include/asm/apic.h:540
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021c4)
Location: arch/x86/include/asm/apic.h:540
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c022a4)
Location: arch/x86/include/asm/apic.h:540
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c02114)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021f4)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c022d4)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020f4)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021d4)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c022b4)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c01fa4)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c02084)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c02164)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020d4)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021b4)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c02294)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c02194)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c022a4)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c023b4)
Location: arch/x86/include/asm/apic.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
</details>
</li>
</ul>

## Differences
