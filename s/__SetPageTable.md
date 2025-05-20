# Function: <code>__SetPageTable</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c1d5)
Location: include/linux/page-flags.h:700
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff81082b65)
Location: include/linux/page-flags.h:723
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff81086786)
Location: include/linux/page-flags.h:760
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff81087476)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff81089926)
Location: include/linux/page-flags.h:802
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff81089b08)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/memory.c (ffffffff8129cf15)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff8108a7d6)
Location: include/linux/page-flags.h:766
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/memory.c (ffffffff812a25f5)
Location: include/linux/page-flags.h:766
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff81099d56)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/memory.c (ffffffff812e3965)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff810acd85)
Location: include/linux/page-flags.h:1008
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/memory.c (ffffffff81344d1d)
Location: include/linux/page-flags.h:1008
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff810c6e15)
Location: include/linux/page-flags.h:987
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/memory.c (ffffffff813bcf4d)
Location: include/linux/page-flags.h:987
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff810ca565)
Location: include/linux/page-flags.h:976
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/memory.c (ffffffff813f1c8d)
Location: include/linux/page-flags.h:976
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100ae410)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:pgd_pgtable_alloc
```
```
In mm/memory.c (ffff8000102f97a8)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffff800010356dac)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/mmu.c (c1508ca0)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:late_alloc
```
```
In mm/memory.c (c051bb98)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/pgtable-frag.c (c0000000000892e8)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002096d6)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
```
</details>
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
In arch/x86/mm/pgtable.c (ffffffff81086476)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff810751f6)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff81086426)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
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
In arch/x86/mm/pgtable.c (ffffffff81088566)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
</details>
</li>
</ul>

## Differences
