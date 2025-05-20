# Function: <code>tlb_remove_page_size</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070bf1)
Location: include/asm-generic/tlb.h:150
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/hugetlb.c (ffffffff811fbca0)
Location: include/asm-generic/tlb.h:150
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff8121582a)
Location: include/asm-generic/tlb.h:150
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/mm/pgtable.c (ffffffff810747d4)
Location: include/asm-generic/tlb.h:140
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/hugetlb.c (ffffffff8120c796)
Location: include/asm-generic/tlb.h:140
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff81227e99)
Location: include/asm-generic/tlb.h:140
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/mm/pgtable.c (ffffffff81073d27)
Location: include/asm-generic/tlb.h:141
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/hugetlb.c (ffffffff8121811a)
Location: include/asm-generic/tlb.h:141
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff81234001)
Location: include/asm-generic/tlb.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/hugetlb.c (ffffffff81232f84)
Location: include/asm-generic/tlb.h:141
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff81251b65)
Location: include/asm-generic/tlb.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/hugetlb.c (ffffffff81255f28)
Location: include/asm-generic/tlb.h:141
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812760da)
Location: include/asm-generic/tlb.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81073f60)
Location: include/asm-generic/tlb.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff8126a3b2)
Location: include/asm-generic/tlb.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff8128af81)
Location: include/asm-generic/tlb.h:178
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81077ae0)
Location: include/asm-generic/tlb.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff812854d7)
Location: include/asm-generic/tlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812a5b24)
Location: include/asm-generic/tlb.h:405
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81078b50)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff8129507c)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812b6fe4)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff8107fe50)
Location: include/asm-generic/tlb.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff812c8670)
Location: include/asm-generic/tlb.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812ec1db)
Location: include/asm-generic/tlb.h:430
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff8107fa7e)
Location: include/asm-generic/tlb.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff812d41f6)
Location: include/asm-generic/tlb.h:429
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812f726d)
Location: include/asm-generic/tlb.h:429
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81080b9e)
Location: include/asm-generic/tlb.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff812db0d4)
Location: include/asm-generic/tlb.h:431
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812fd704)
Location: include/asm-generic/tlb.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff8108fade)
Location: include/asm-generic/tlb.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff81322171)
Location: include/asm-generic/tlb.h:431
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff81347339)
Location: include/asm-generic/tlb.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff810a08dd)
Location: include/asm-generic/tlb.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff8138f45d)
Location: include/asm-generic/tlb.h:431
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff813bd5e8)
Location: include/asm-generic/tlb.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff810b858d)
Location: include/asm-generic/tlb.h:463
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff8140fbee)
Location: include/asm-generic/tlb.h:463
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff8143fd84)
Location: include/asm-generic/tlb.h:463
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff810bb78d)
Location: include/asm-generic/tlb.h:463
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff81442fb5)
Location: include/asm-generic/tlb.h:463
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff814755af)
Location: include/asm-generic/tlb.h:463
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff810c2ba2)
Location: include/asm-generic/tlb.h:462
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_tlb_remove_table
```
```
In mm/hugetlb.c (ffffffff8147d1cc)
Location: include/asm-generic/tlb.h:462
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff814a4fa7)
Location: include/asm-generic/tlb.h:462
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
```
</details>
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
In mm/hugetlb.c (ffff800010333d20)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffff800010357d44)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c05175fc)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040c894)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (c0000000004400cc)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000206b12)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/hugetlb.c (ffffffe00022fe3c)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
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
In arch/x86/kernel/paravirt.c (ffffffff81077b50)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff8128d65c)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812af5c4)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81067770)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff8127f3ff)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812a0bb5)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81077b00)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff8128b46c)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812ad3d4)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81079ba0)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
```
```
In mm/hugetlb.c (ffffffff8129b285)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812bd754)
Location: include/asm-generic/tlb.h:413
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
</details>
</li>
</ul>

## Differences
