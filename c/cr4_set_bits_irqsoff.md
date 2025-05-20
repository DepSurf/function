# Function: <code>cr4_set_bits_irqsoff</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006598)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d2bd)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e0db)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810403a4)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046f8b)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dcde)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8107de17)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810886b5)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810402fd)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810411cb)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810436fa)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104adc3)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810533be)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81084517)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8108adfe)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/kernel/process.c (ffffffff8104024d)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8104109b)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043706)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a2c1)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810524de)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81bd8790)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8108af83)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/kernel/process.c (ffffffff81041c1d)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81042a8b)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81044f56)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104adb6)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053d93)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81bca634)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8108bae5)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/kernel/process.c (ffffffff81047eed)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81048dfb)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b524)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81051e46)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c5f2)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81c9fab3)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8109b0de)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/kernel/process.c (ffffffff81050bc4)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810521b4)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055674)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105d1d4)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067a54)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81e4f313)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810ae60f)
Location: arch/x86/include/asm/tlbflush.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/kernel/process.c (ffffffff8105e0d4)
Location: arch/x86/include/asm/tlbflush.h:25
Inline: True
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8105f9a4)
Location: arch/x86/include/asm/tlbflush.h:25
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810631e4)
Location: arch/x86/include/asm/tlbflush.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106b607)
Location: arch/x86/include/asm/tlbflush.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076fb4)
Location: arch/x86/include/asm/tlbflush.h:25
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff810c0c67)
Location: arch/x86/include/asm/tlbflush.h:25
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810c8904)
Location: arch/x86/include/asm/tlbflush.h:25
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/kernel/process.c (ffffffff8105f784)
Location: arch/x86/include/asm/tlbflush.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810610f4)
Location: arch/x86/include/asm/tlbflush.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064b34)
Location: arch/x86/include/asm/tlbflush.h:28
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106cfb7)
Location: arch/x86/include/asm/tlbflush.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810791c4)
Location: arch/x86/include/asm/tlbflush.h:28
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff810c4347)
Location: arch/x86/include/asm/tlbflush.h:28
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810cbefe)
Location: arch/x86/include/asm/tlbflush.h:28
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/kernel/process.c (ffffffff81066834)
Location: arch/x86/include/asm/tlbflush.h:29
Inline: True
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81068204)
Location: arch/x86/include/asm/tlbflush.h:29
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106bfc4)
Location: arch/x86/include/asm/tlbflush.h:29
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81074627)
Location: arch/x86/include/asm/tlbflush.h:29
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080774)
Location: arch/x86/include/asm/tlbflush.h:29
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff810cc797)
Location: arch/x86/include/asm/tlbflush.h:29
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810d458e)
Location: arch/x86/include/asm/tlbflush.h:29
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/events/core.c (ffffffff81006598)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d43d)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e25b)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040524)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104710b)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104de3e)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8107ce17)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810876b5)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff810044b6)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8102cadf)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8102da6d)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102fd16)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810361c3)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103d2e0)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8106c579)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81076326)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff81006558)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d27d)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e09b)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040364)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046f4b)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dc8e)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8107cdc7)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81087665)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff810066b8)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103e34f)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103f21b)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041734)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104834b)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f0ce)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8107eec7)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81089795)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
</details>
</li>
</ul>

## Differences
