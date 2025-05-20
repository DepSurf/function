# Function: <code>pgtable_page_dtor</code>

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
In arch/x86/mm/pgtable.c (ffffffff81070c32)
Location: include/linux/mm.h:1607
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff811bd307)
Location: include/linux/mm.h:1607
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff811f4021)
Location: include/linux/mm.h:1607
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In arch/x86/mm/pgtable.c (ffffffff81070a32)
Location: include/linux/mm.h:1723
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff811db738)
Location: include/linux/mm.h:1723
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81215987)
Location: include/linux/mm.h:1723
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121b62d)
Location: include/linux/mm.h:1723
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In arch/x86/mm/pgtable.c (ffffffff810746c2)
Location: include/linux/mm.h:1697
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff811ead6f)
Location: include/linux/mm.h:1697
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81227f38)
Location: include/linux/mm.h:1697
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122ccad)
Location: include/linux/mm.h:1697
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In arch/x86/mm/pgtable.c (ffffffff81073c12)
Location: include/linux/mm.h:1750
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff811f5cf0)
Location: include/linux/mm.h:1750
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812340c3)
Location: include/linux/mm.h:1750
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81239290)
Location: include/linux/mm.h:1750
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In arch/x86/mm/pgtable.c (ffffffff81079632)
Location: include/linux/mm.h:1852
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff8120d764)
Location: include/linux/mm.h:1852
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81251cf4)
Location: include/linux/mm.h:1852
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812579a3)
Location: include/linux/mm.h:1852
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In arch/x86/mm/pgtable.c (ffffffff8107c1e5)
Location: include/linux/mm.h:1940
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff8122e288)
Location: include/linux/mm.h:1940
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81276261)
Location: include/linux/mm.h:1940
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127bbfd)
Location: include/linux/mm.h:1940
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In arch/x86/mm/pgtable.c (ffffffff81082b75)
Location: include/linux/mm.h:2011
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff81242065)
Location: include/linux/mm.h:2011
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8128af41)
Location: include/linux/mm.h:2011
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8128ff35)
Location: include/linux/mm.h:2011
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In arch/x86/mm/pgtable.c (ffffffff810867a5)
Location: include/linux/mm.h:2006
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff81253b21)
Location: include/linux/mm.h:2006
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812a5ae4)
Location: include/linux/mm.h:2006
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ab129)
Location: include/linux/mm.h:2006
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2006
Inline: True
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
