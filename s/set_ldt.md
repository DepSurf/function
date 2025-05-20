# Function: <code>set_ldt</code>

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
In arch/x86/kernel/ldt.c (ffffffff81032bb4)
Location: arch/x86/include/asm/paravirt.h:237
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041309)
Location: arch/x86/include/asm/paravirt.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/sched/core.c (ffffffff818201ae)
Location: arch/x86/include/asm/paravirt.h:237
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:idle_task_exit
```
```
In mm/mmu_context.c (ffffffff811afe64)
Location: arch/x86/include/asm/paravirt.h:237
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffff81213a92)
Location: arch/x86/include/asm/paravirt.h:237
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff816fb263)
Location: arch/x86/include/asm/paravirt.h:237
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/ldt.c (ffffffff81031d53)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104122c)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff810725e8)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff817604ca)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/ldt.c (ffffffff810319d3)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040c79)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81076186)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8178d4ca)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/ldt.c (ffffffff8102fbef)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ec24)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81074824)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff817ab644)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/ldt.c (ffffffff81032294)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810418ab)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff8107a738)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff81822af9)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/ldt.c (ffffffff81033784)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810432ed)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff8107d4e8)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8186cd21)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/ldt.c (ffffffff81034a54)
Location: arch/x86/include/asm/paravirt.h:271
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810447e6)
Location: arch/x86/include/asm/paravirt.h:271
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff8108402b)
Location: arch/x86/include/asm/paravirt.h:271
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8188cd31)
Location: arch/x86/include/asm/paravirt.h:271
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/ldt.c (ffffffff81036903)
Location: arch/x86/include/asm/paravirt.h:271
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046dba)
Location: arch/x86/include/asm/paravirt.h:271
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81087cb3)
Location: arch/x86/include/asm/paravirt.h:271
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818d75e8)
Location: arch/x86/include/asm/paravirt.h:271
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/ldt.c (ffffffff81037133)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104753a)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81088973)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8190986f)
Location: arch/x86/include/asm/paravirt.h:259
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
In arch/x86/kernel/ldt.c (ffffffff8103903e)
Location: arch/x86/include/asm/paravirt.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
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
In arch/x86/kernel/ldt.c (ffffffff8103996e)
Location: arch/x86/include/asm/paravirt.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103b43e)
Location: arch/x86/include/asm/paravirt.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81040eb0)
Location: arch/x86/include/asm/paravirt.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81048959)
Location: arch/x86/include/asm/paravirt.h:286
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81053689)
Location: arch/x86/include/asm/paravirt.h:286
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81054669)
Location: arch/x86/include/asm/paravirt.h:288
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8105b8a9)
Location: arch/x86/include/asm/paravirt.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
  - arch/x86/kernel/ldt.c:load_mm_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81037293)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810476ba)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81087973)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818a8c2f)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810370f3)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810474fa)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81087923)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818fa28f)
Location: arch/x86/include/asm/paravirt.h:259
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
In arch/x86/kernel/ldt.c (ffffffff810380f3)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810488fa)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81089ad4)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8191b3ef)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
```
</details>
</li>
</ul>

## Differences
