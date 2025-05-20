# Function: <code>load_mm_ldt</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff810412f9)
Location: arch/x86/include/asm/mmu_context.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/sched/core.c (ffffffff8182019d)
Location: arch/x86/include/asm/mmu_context.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
```
```
In mm/mmu_context.c (ffffffff811afe57)
Location: arch/x86/include/asm/mmu_context.h:66
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffff81213a82)
Location: arch/x86/include/asm/mmu_context.h:66
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff816fb257)
Location: arch/x86/include/asm/mmu_context.h:66
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/common.c (ffffffff8104121c)
Location: arch/x86/include/asm/mmu_context.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff810725dc)
Location: arch/x86/include/asm/mmu_context.h:66
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff817604be)
Location: arch/x86/include/asm/mmu_context.h:66
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/common.c (ffffffff81040c69)
Location: arch/x86/include/asm/mmu_context.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff8107617a)
Location: arch/x86/include/asm/mmu_context.h:67
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8178d4be)
Location: arch/x86/include/asm/mmu_context.h:67
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/common.c (ffffffff8103ec14)
Location: arch/x86/include/asm/mmu_context.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81074818)
Location: arch/x86/include/asm/mmu_context.h:67
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff817ab634)
Location: arch/x86/include/asm/mmu_context.h:67
Inline: True
Inline callers:
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
In arch/x86/kernel/ldt.c (ffffffff81032288)
Location: arch/x86/include/asm/mmu_context.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104189b)
Location: arch/x86/include/asm/mmu_context.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff8107a72c)
Location: arch/x86/include/asm/mmu_context.h:103
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff81822ae9)
Location: arch/x86/include/asm/mmu_context.h:103
Inline: True
Inline callers:
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
In arch/x86/kernel/ldt.c (ffffffff81033778)
Location: arch/x86/include/asm/mmu_context.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104316e)
Location: arch/x86/include/asm/mmu_context.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff8107d4dc)
Location: arch/x86/include/asm/mmu_context.h:104
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8186cd11)
Location: arch/x86/include/asm/mmu_context.h:104
Inline: True
Inline callers:
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
In arch/x86/kernel/ldt.c (ffffffff81034a48)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810447d6)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff8108401f)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8188cd21)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
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
In arch/x86/kernel/ldt.c (ffffffff810368f3)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046daa)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81087ca7)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818d75dc)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
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
In arch/x86/kernel/ldt.c (ffffffff81037123)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104752a)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81088967)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8190985f)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void load_mm_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81039010)
Location: arch/x86/kernel/ldt.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81039010-ffffffff81039081: load_mm_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void load_mm_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81039940)
Location: arch/x86/kernel/ldt.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81039940-ffffffff810399b1: load_mm_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void load_mm_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103b410)
Location: arch/x86/kernel/ldt.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8103b410-ffffffff8103b481: load_mm_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void load_mm_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81c98e2c-ffffffff81c98e4c: load_mm_ldt.cold (STB_LOCAL)
ffffffff81040e60-ffffffff81040eee: load_mm_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void load_mm_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81e483d7-ffffffff81e483f7: load_mm_ldt.cold (STB_LOCAL)
ffffffff810488f0-ffffffff81048994: load_mm_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void load_mm_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff820522bf-ffffffff820522df: load_mm_ldt.cold (STB_LOCAL)
ffffffff81053620-ffffffff810536c4: load_mm_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void load_mm_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff820d07d9-ffffffff820d07f9: load_mm_ldt.cold (STB_LOCAL)
ffffffff81054600-ffffffff810546a4: load_mm_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void load_mm_ldt(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:switch_ldt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff821ab2ee-ffffffff821ab30e: load_mm_ldt.cold (STB_LOCAL)
ffffffff8105b840-ffffffff8105b8e4: load_mm_ldt (STB_GLOBAL)
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
In arch/x86/kernel/ldt.c (ffffffff81037283)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810476aa)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81087967)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818a8c1f)
Location: arch/x86/include/asm/mmu_context.h:100
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
In arch/x86/kernel/ldt.c (ffffffff81026c14)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036849)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff810765e3)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818638cc)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/ldt.c (ffffffff810370e3)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810474ea)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81087917)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818fa27f)
Location: arch/x86/include/asm/mmu_context.h:100
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
In arch/x86/kernel/ldt.c (ffffffff810380e3)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810488ea)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81089ac8)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8191b3df)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
