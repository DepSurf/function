# Function: <code>load_mm_cr4_irqsoff</code>

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
In arch/x86/events/core.c (ffffffff81006561)
Location: arch/x86/include/asm/mmu_context.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/mm/tlb.c (ffffffff810886a6)
Location: arch/x86/include/asm/mmu_context.h:31
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff81006561)
Location: arch/x86/include/asm/mmu_context.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/mm/tlb.c (ffffffff810876a6)
Location: arch/x86/include/asm/mmu_context.h:31
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
In arch/x86/events/core.c (ffffffff81004481)
Location: arch/x86/include/asm/mmu_context.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/mm/tlb.c (ffffffff81076317)
Location: arch/x86/include/asm/mmu_context.h:31
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
In arch/x86/events/core.c (ffffffff81006521)
Location: arch/x86/include/asm/mmu_context.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/mm/tlb.c (ffffffff81087656)
Location: arch/x86/include/asm/mmu_context.h:31
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
In arch/x86/events/core.c (ffffffff81006681)
Location: arch/x86/include/asm/mmu_context.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/mm/tlb.c (ffffffff81089786)
Location: arch/x86/include/asm/mmu_context.h:31
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
</details>
</li>
</ul>

## Differences
