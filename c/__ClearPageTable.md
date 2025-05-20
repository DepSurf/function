# Function: <code>__ClearPageTable</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c204)
Location: include/linux/page-flags.h:700
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff8122e2a0)
Location: include/linux/page-flags.h:700
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8127626c)
Location: include/linux/page-flags.h:700
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
In mm/khugepaged.c (ffffffff8127bc08)
Location: include/linux/page-flags.h:700
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
Location: include/linux/page-flags.h:723
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff81242065)
Location: include/linux/page-flags.h:723
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8128af41)
Location: include/linux/page-flags.h:723
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
Location: include/linux/page-flags.h:723
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
Location: include/linux/page-flags.h:760
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff81253b21)
Location: include/linux/page-flags.h:760
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812a5ae4)
Location: include/linux/page-flags.h:760
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
Location: include/linux/page-flags.h:760
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:760
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff81087495)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff81262084)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812b6fa4)
Location: include/linux/page-flags.h:776
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
In mm/khugepaged.c (ffffffff812bcac2)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:776
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff81089945)
Location: include/linux/page-flags.h:802
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff81292047)
Location: include/linux/page-flags.h:802
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812ec186)
Location: include/linux/page-flags.h:802
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f125e)
Location: include/linux/page-flags.h:802
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:802
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff8108a738)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff8129d06a)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812f71ea)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fc954)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:772
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff8108b38a)
Location: include/linux/page-flags.h:766
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff812a2750)
Location: include/linux/page-flags.h:766
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812fd67c)
Location: include/linux/page-flags.h:766
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813036c3)
Location: include/linux/page-flags.h:766
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:766
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff8109a92a)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff812e3ac0)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff813472b1)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134d42d)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:785
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff810adbfd)
Location: include/linux/page-flags.h:1008
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff81344e5f)
Location: include/linux/page-flags.h:1008
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff813bd594)
Location: include/linux/page-flags.h:1008
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c3bb3)
Location: include/linux/page-flags.h:1008
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:1008
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff810c7e14)
Location: include/linux/page-flags.h:987
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff813bd08f)
Location: include/linux/page-flags.h:987
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8143fd2c)
Location: include/linux/page-flags.h:987
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81447392)
Location: include/linux/page-flags.h:987
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:987
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff810cb554)
Location: include/linux/page-flags.h:976
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff813f1dd5)
Location: include/linux/page-flags.h:976
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81475554)
Location: include/linux/page-flags.h:976
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147ca6c)
Location: include/linux/page-flags.h:976
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:976
Inline: True
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
In mm/memory.c (ffff8000102f9338)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/huge_memory.c (ffff800010357cf0)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035dcd4)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In arch/arm/mm/pgd.c (c031f9a0)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/arm/mm/pgd.c:pgd_free
```
```
In mm/memory.c (c051b80c)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
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
In arch/powerpc/mm/pgtable-frag.c (c0000000000893d0)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_free
  - arch/powerpc/mm/pgtable-frag.c:pte_frag_destroy
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
In mm/memory.c (ffffffe000209322)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
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
In arch/x86/mm/pgtable.c (ffffffff81086495)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff8125a6d4)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812af584)
Location: include/linux/page-flags.h:776
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
In mm/khugepaged.c (ffffffff812b50a2)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:776
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
In arch/x86/mm/pgtable.c (ffffffff81075215)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff8124caf4)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812a0b75)
Location: include/linux/page-flags.h:776
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
In mm/khugepaged.c (ffffffff812a60c2)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:776
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff81086445)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff81258474)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812ad394)
Location: include/linux/page-flags.h:776
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
In mm/khugepaged.c (ffffffff812b2eb2)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:776
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
In arch/x86/mm/pgtable.c (ffffffff81088585)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff81267e54)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812bd715)
Location: include/linux/page-flags.h:776
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
In mm/khugepaged.c (ffffffff812c32e6)
Location: include/linux/page-flags.h:776
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:776
Inline: True
```
</details>
</li>
</ul>

## Differences
