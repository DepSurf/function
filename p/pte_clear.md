# Function: <code>pte_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d5c5)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77fe9)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In mm/memory.c (ffffffff811bd8d8)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/hugetlb.c (ffffffff811ddac2)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff811f558a)
Location: arch/x86/include/asm/paravirt.h:644
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
**Symbols:**

```
ffffffff8107d5c5-ffffffff8107d5f0: pte_clear.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f0aa)
Location: arch/x86/include/asm/paravirt.h:617
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa0741)
Location: arch/x86/include/asm/paravirt.h:617
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In mm/memory.c (ffffffff811d8fd2)
Location: arch/x86/include/asm/paravirt.h:617
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffff811eef3b)
Location: arch/x86/include/asm/paravirt.h:617
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff811fbd3b)
Location: arch/x86/include/asm/paravirt.h:617
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff8121a4fc)
Location: arch/x86/include/asm/paravirt.h:617
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8107f0aa-ffffffff8107f0d5: pte_clear.constprop.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81083760)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbcb2)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In mm/memory.c (ffffffff811e8466)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffff811ff89d)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8120c7f2)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff8122e8fe)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81083760-ffffffff8108378b: pte_clear.constprop.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ceca)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcc82)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In mm/memory.c (ffffffff811f367a)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
```
```
In mm/madvise.c (ffffffff8120a52a)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff81218184)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff812385ad)
Location: arch/x86/include/asm/paravirt.h:655
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8106ceca-ffffffff8106cef5: pte_clear.constprop.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81071be9)
Location: arch/x86/include/asm/paravirt.h:619
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/ioremap.c (ffffffff826c385e)
Location: arch/x86/include/asm/paravirt.h:619
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In mm/memory.c (ffffffff8120b299)
Location: arch/x86/include/asm/paravirt.h:619
Inline: True
```
```
In mm/madvise.c (ffffffff81223781)
Location: arch/x86/include/asm/paravirt.h:619
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff81232ff9)
Location: arch/x86/include/asm/paravirt.h:619
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff81259a98)
Location: arch/x86/include/asm/paravirt.h:619
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81071be9-ffffffff81071c14: pte_clear.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810748df)
Location: arch/x86/include/asm/paravirt.h:624
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff826edae3)
Location: arch/x86/include/asm/paravirt.h:624
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fe8f)
Location: arch/x86/include/asm/paravirt.h:624
Inline: True
```
```
In mm/memory.c (ffffffff8122c07a)
Location: arch/x86/include/asm/paravirt.h:624
Inline: True
```
```
In mm/madvise.c (ffffffff8124658c)
Location: arch/x86/include/asm/paravirt.h:624
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8125603a)
Location: arch/x86/include/asm/paravirt.h:624
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff8127c419)
Location: arch/x86/include/asm/paravirt.h:624
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff810748df-ffffffff8107490a: pte_clear.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81034844)
Location: arch/x86/include/asm/paravirt.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/mm/init_64.c (ffffffff8107a7f2)
Location: arch/x86/include/asm/paravirt.h:602
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4675)
Location: arch/x86/include/asm/paravirt.h:602
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff810869cf)
Location: arch/x86/include/asm/paravirt.h:602
Inline: True
```
```
In mm/memory.c (ffffffff8123f489)
Location: arch/x86/include/asm/paravirt.h:602
Inline: True
```
```
In mm/madvise.c (ffffffff8125a9af)
Location: arch/x86/include/asm/paravirt.h:602
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8126a4d6)
Location: arch/x86/include/asm/paravirt.h:602
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff81290abc)
Location: arch/x86/include/asm/paravirt.h:602
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8107a7f2-ffffffff8107a81d: pte_clear.constprop.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810366ec)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff810398dd)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff8107e561)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff828bcb45)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a5e7)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
```
```
In mm/memory.c (ffffffff81250dca)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
```
```
In mm/madvise.c (ffffffff81275af9)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff812855ef)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff812a9df1)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
```
**Symbols:**

```
ffffffff8107e561-ffffffff8107e58c: pte_clear.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036f1c)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a0ae)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff8107f5f1)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2fe0)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b257)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
```
In mm/memory.c (ffffffff8125f3e6)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
```
In mm/madvise.c (ffffffff81284ac9)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8129519a)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff812bb361)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
**Symbols:**

```
ffffffff8107f5f1-ffffffff8107f61c: pte_clear.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038b1a)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:unmap_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff8103cd1c)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81086039)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:remove_pte_table
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce63d0)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8109258d)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/memory.c (ffffffff8128f92e)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812b6cb8)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff812c879c)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff812f05c5)
Location: arch/x86/include/asm/paravirt.h:605
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_copy
```
**Symbols:**

```
ffffffff81086039-ffffffff81086069: pte_clear.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/ldt.c (ffffffff8103973b)
Location: arch/x86/include/asm/paravirt.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d1cf)
Location: arch/x86/include/asm/paravirt.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81c3cabb)
Location: arch/x86/include/asm/paravirt.h:504
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:remove_pte_table
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3d56)
Location: arch/x86/include/asm/paravirt.h:504
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff81091c2b)
Location: arch/x86/include/asm/paravirt.h:504
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/memory.c (ffffffff8129a37d)
Location: arch/x86/include/asm/paravirt.h:504
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c2e72)
Location: arch/x86/include/asm/paravirt.h:504
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff812d434a)
Location: arch/x86/include/asm/paravirt.h:504
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff812fbd6f)
Location: arch/x86/include/asm/paravirt.h:504
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
In arch/x86/kernel/ldt.c (ffffffff8103b208)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ea0c)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81c2f0b8)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff831de897)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8109251e)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In mm/memory.c (ffffffff8129f5a0)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c9cef)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff812db22a)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff81302cb8)
Location: arch/x86/include/asm/paravirt.h:535
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
In arch/x86/kernel/ldt.c (ffffffff81040c44)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8104477c)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81d4d7b9)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff832c1c0d)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff810a230e)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In mm/memory.c (ffffffff812e071e)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8130ed0f)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff81322331)
Location: arch/x86/include/asm/paravirt.h:535
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff8134c778)
Location: arch/x86/include/asm/paravirt.h:535
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
In arch/x86/kernel/ldt.c (ffffffff8104859b)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8104cd78)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81f1d4db)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff8347431a)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff810b68ad)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In mm/memory.c (ffffffff81343bce)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff81354066)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff81376a02)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff81390ece)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
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
In arch/x86/kernel/ldt.c (ffffffff810532fb)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff81059189)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff820c57c5)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9c05c)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1af6)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In mm/memory.c (ffffffff813bbc46)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff813ce4ec)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff813f42f6)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff814127a5)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
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
In arch/x86/kernel/ldt.c (ffffffff810542dc)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a737)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff82149835)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff836bfafc)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff810d4fa6)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In mm/memory.c (ffffffff813f065a)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff81402d98)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff81427b0b)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff81445daa)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
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
In arch/x86/kernel/ldt.c (ffffffff8105b510)
Location: arch/x86/include/asm/paravirt.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff81061a0f)
Location: arch/x86/include/asm/paravirt.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff8222c2f5)
Location: arch/x86/include/asm/paravirt.h:534
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff838f061c)
Location: arch/x86/include/asm/paravirt.h:534
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd746)
Location: arch/x86/include/asm/paravirt.h:534
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In mm/memory.c (ffffffff8141ffa4)
Location: arch/x86/include/asm/paravirt.h:534
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff8142f408)
Location: arch/x86/include/asm/paravirt.h:534
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff8146131b)
Location: arch/x86/include/asm/paravirt.h:534
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8147f7e2)
Location: arch/x86/include/asm/paravirt.h:534
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebee0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:474
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
  - arch/powerpc/mm/book3s64/radix_pgtable.c:split_kernel_mapping
  - arch/powerpc/mm/book3s64/radix_pgtable.c:stop_machine_change_mapping
```
```
In mm/memory.c (c0000000003bed58)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:474
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (c0000000003f32c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:474
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (c00000000040c9d0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:474
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (c000000000446178)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:474
Inline: True
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
In arch/riscv/mm/init.c (ffffffe000003d9a)
Location: arch/riscv/include/asm/pgtable.h:342
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:paging_init
  - arch/riscv/mm/init.c:paging_init
  - arch/riscv/mm/init.c:get_pmd_virt
  - arch/riscv/mm/init.c:get_pte_virt
```
```
In mm/memory.c (ffffffe00020766e)
Location: arch/riscv/include/asm/pgtable.h:342
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffe00022071e)
Location: arch/riscv/include/asm/pgtable.h:342
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffe00022ff32)
Location: arch/riscv/include/asm/pgtable.h:342
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
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103707c)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a20e)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff8107e5f1)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff828adfb6)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a217)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
```
In mm/memory.c (ffffffff81257a36)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
```
In mm/madvise.c (ffffffff8127d119)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8128d77a)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff812b3941)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
**Symbols:**

```
ffffffff8107e5f1-ffffffff8107e61c: pte_clear.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036edc)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a06e)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff8107e5a1)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0eb5)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a1c7)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
```
In mm/memory.c (ffffffff812557d6)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
```
In mm/madvise.c (ffffffff8127aeb9)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8128b58a)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff812b1751)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
**Symbols:**

```
ffffffff8107e5a1-ffffffff8107e5cc: pte_clear.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037edc)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103b06e)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81080691)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff828c4000)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c467)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
```
In mm/memory.c (ffffffff8126528d)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
```
In mm/madvise.c (ffffffff8128aa85)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8129b398)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff812c1abb)
Location: arch/x86/include/asm/paravirt.h:591
Inline: True
```
**Symbols:**

```
ffffffff81080691-ffffffff810806bc: pte_clear.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
