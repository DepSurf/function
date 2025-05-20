# Function: <code>ldt_slot_va</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810322bf)
Location: arch/x86/include/asm/mmu_context.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810419c1)
Location: arch/x86/include/asm/mmu_context.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff8107a772)
Location: arch/x86/include/asm/mmu_context.h:71
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff81822bfb)
Location: arch/x86/include/asm/mmu_context.h:71
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
In arch/x86/kernel/ldt.c (ffffffff810337af)
Location: arch/x86/include/asm/mmu_context.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104329d)
Location: arch/x86/include/asm/mmu_context.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff8107d51b)
Location: arch/x86/include/asm/mmu_context.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8186ce3b)
Location: arch/x86/include/asm/mmu_context.h:72
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
In arch/x86/kernel/ldt.c (ffffffff8103480c)
Location: arch/x86/include/asm/mmu_context.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81044935)
Location: arch/x86/include/asm/mmu_context.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81084055)
Location: arch/x86/include/asm/mmu_context.h:72
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8188ce4b)
Location: arch/x86/include/asm/mmu_context.h:72
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
In arch/x86/kernel/ldt.c (ffffffff810366b5)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046ea8)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81087ce0)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818d7623)
Location: arch/x86/include/asm/mmu_context.h:73
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
In arch/x86/kernel/ldt.c (ffffffff81036ee5)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047625)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff810889a0)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8190998c)
Location: arch/x86/include/asm/mmu_context.h:73
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
In arch/x86/kernel/ldt.c (ffffffff81038ad9)
Location: arch/x86/kernel/ldt.c:37
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:unmap_ldt_struct
  - arch/x86/kernel/ldt.c:unmap_ldt_struct
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
In arch/x86/kernel/ldt.c (ffffffff81039703)
Location: arch/x86/kernel/ldt.c:37
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff8103b1d0)
Location: arch/x86/kernel/ldt.c:37
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81040c15)
Location: arch/x86/kernel/ldt.c:37
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
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
In arch/x86/kernel/ldt.c (ffffffff8104856c)
Location: arch/x86/kernel/ldt.c:37
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
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
In arch/x86/kernel/ldt.c (ffffffff810532cc)
Location: arch/x86/kernel/ldt.c:37
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
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
In arch/x86/kernel/ldt.c (ffffffff810542a6)
Location: arch/x86/kernel/ldt.c:37
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
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
In arch/x86/kernel/ldt.c (ffffffff8105b4da)
Location: arch/x86/kernel/ldt.c:37
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
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
In arch/x86/kernel/ldt.c (ffffffff81037045)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047795)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff810879a0)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818a8d4c)
Location: arch/x86/include/asm/mmu_context.h:73
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
In arch/x86/kernel/ldt.c (ffffffff81026932)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036a05)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81076617)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff81863a8b)
Location: arch/x86/include/asm/mmu_context.h:73
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
In arch/x86/kernel/ldt.c (ffffffff81036ea5)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810475d5)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81087950)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818fa3ac)
Location: arch/x86/include/asm/mmu_context.h:73
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
In arch/x86/kernel/ldt.c (ffffffff81037ea5)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810489e5)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/mm/tlb.c (ffffffff81089b01)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8191b50c)
Location: arch/x86/include/asm/mmu_context.h:73
Inline: True
```
</details>
</li>
</ul>

## Differences
