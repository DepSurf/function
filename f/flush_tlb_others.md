# Function: <code>flush_tlb_others</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81072867)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_page
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
In arch/x86/mm/tlb.c (ffffffff81072a45)
Location: arch/x86/include/asm/paravirt.h:323
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_page
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
```
```
In mm/rmap.c (ffffffff811e7073)
Location: arch/x86/include/asm/paravirt.h:323
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
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
In arch/x86/mm/tlb.c (ffffffff810765f0)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_page
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
```
```
In mm/rmap.c (ffffffff811f8407)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81074d70)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107af08)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107dcc8)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81084840)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810884aa)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108915a)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108bab9)
Location: arch/x86/mm/tlb.c:890
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff8108b670-ffffffff8108b682: flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108bb09)
Location: arch/x86/mm/tlb.c:826
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff8108b6c0-ffffffff8108b6d2: flush_tlb_others (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108811a)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076d7a)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810880ca)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108a351)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
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
</ul>
