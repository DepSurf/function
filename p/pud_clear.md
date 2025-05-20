# Function: <code>pud_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d4c0)
Location: arch/x86/include/asm/paravirt.h:610
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c5de)
Location: arch/x86/include/asm/paravirt.h:610
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pgd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107137b)
Location: arch/x86/include/asm/paravirt.h:610
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811bcf0f)
Location: arch/x86/include/asm/paravirt.h:610
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811d03d5)
Location: arch/x86/include/asm/paravirt.h:610
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff811dd5ea)
Location: arch/x86/include/asm/paravirt.h:610
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff8107d4c0-ffffffff8107d4df: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107ef9d)
Location: arch/x86/include/asm/paravirt.h:583
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c5cc)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107126c)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811d7d28)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811ed585)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff811fb89a)
Location: arch/x86/include/asm/paravirt.h:583
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff8107ef9d-ffffffff8107efbc: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8108364d)
Location: arch/x86/include/asm/paravirt.h:574
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107026c)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81074dec)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811e7a11)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811f7975)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8120c392)
Location: arch/x86/include/asm/paravirt.h:574
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff8108364d-ffffffff8108366c: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ce3e)
Location: arch/x86/include/asm/paravirt.h:576
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f98c)
Location: arch/x86/include/asm/paravirt.h:576
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107439c)
Location: arch/x86/include/asm/paravirt.h:576
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811f2c3a)
Location: arch/x86/include/asm/paravirt.h:576
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81202b05)
Location: arch/x86/include/asm/paravirt.h:576
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81217d32)
Location: arch/x86/include/asm/paravirt.h:576
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff8106ce3e-ffffffff8106ce5d: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81071b5d)
Location: arch/x86/include/asm/paravirt.h:540
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pageattr.c (ffffffff81074dcb)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079f52)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff81209cdc)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8121b875)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81232a99)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff81071b5d-ffffffff81071b7c: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81074825)
Location: arch/x86/include/asm/paravirt.h:540
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107787a)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cbf1)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff8122ab13)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8123d655)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81255b09)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff81074825-ffffffff81074844: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107a715)
Location: arch/x86/include/asm/paravirt.h:524
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107e02a)
Location: arch/x86/include/asm/paravirt.h:524
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108361f)
Location: arch/x86/include/asm/paravirt.h:524
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff8123decd)
Location: arch/x86/include/asm/paravirt.h:524
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81251ba5)
Location: arch/x86/include/asm/paravirt.h:524
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81269f59)
Location: arch/x86/include/asm/paravirt.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff8107a715-ffffffff8107a734: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e46c)
Location: arch/x86/include/asm/paravirt.h:525
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810818f7)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108728f)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff8124e4f1)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81263e76)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8128508c)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff8107e46c-ffffffff8107e48b: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f4fc)
Location: arch/x86/include/asm/paravirt.h:513
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810829b7)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087f7f)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff8125ca61)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812726e6)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81294c2c)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff8107f4fc-ffffffff8107f51b: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085eab)
Location: arch/x86/include/asm/paravirt.h:527
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a41f)
Location: arch/x86/include/asm/paravirt.h:527
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cb18)
Location: arch/x86/include/asm/paravirt.h:527
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff8128c353)
Location: arch/x86/include/asm/paravirt.h:527
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812a3486)
Location: arch/x86/include/asm/paravirt.h:527
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff812c8222)
Location: arch/x86/include/asm/paravirt.h:527
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff81085eab-ffffffff81085eca: pud_clear (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81c3d0b6)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a686)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ccd3)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff812972c6)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812ab08f)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812aed86)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff812d3df9)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
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
In arch/x86/mm/init_64.c (ffffffff81c2f4b7)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b2d6)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d8c5)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff8129d10a)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812b058f)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812b42b6)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff812dad05)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
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
In arch/x86/mm/init_64.c (ffffffff81d4dbb6)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a876)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d150)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff812de555)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812f28b6)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff812f5e96)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81321d26)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
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
In arch/x86/mm/init_64.c (ffffffff81f1d91a)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810adb44)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b09da)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff8133e5f5)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff8135665a)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81359e04)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8138ee72)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
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
In arch/x86/mm/init_64.c (ffffffff820c5d0f)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7d57)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb0a8)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff813b565f)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff813d0c7b)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff813d4814)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8140d95a)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
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
In arch/x86/mm/init_64.c (ffffffff82149d79)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb497)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce6d2)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff813ead1f)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff814056ad)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff814091e4)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81440d0d)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
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
In arch/x86/mm/init_64.c (ffffffff8222c829)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810d39e7)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6db2)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff8141751f)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff81431bd5)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff814359d4)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8147ae3d)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
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
In arch/arm64/mm/mmu.c (ffff8000100af540)
Location: arch/arm64/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:pud_free_pmd_page
  - arch/arm64/mm/mmu.c:pud_clear_huge
```
```
In virt/kvm/arm/mmu.c (ffff8000100cb394)
Location: arch/arm64/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In mm/memory.c (ffff8000102f56f0)
Location: arch/arm64/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffff800010307f5c)
Location: arch/arm64/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffff80001033399c)
Location: arch/arm64/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
</details>
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c00000000009596c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:911
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_free_pmd_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_clear_huge
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5dd8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:911
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In mm/memory.c (c0000000003bc87c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:911
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (c0000000003d74fc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:911
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
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
In mm/memory.c (ffffffe000206bb2)
Location: arch/riscv/include/asm/pgtable-64.h:51
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffe000212e24)
Location: arch/riscv/include/asm/pgtable-64.h:51
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffe00022fb0a)
Location: arch/riscv/include/asm/pgtable-64.h:51
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e4fc)
Location: arch/x86/include/asm/paravirt.h:513
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810819b7)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81086f7f)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff812550b1)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff8126ad36)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8128d20c)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff8107e4fc-ffffffff8107e51b: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e4ac)
Location: arch/x86/include/asm/paravirt.h:513
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81081967)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81086f2f)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff81252e51)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81268ad6)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8128b01c)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff8107e4ac-ffffffff8107e4cb: pud_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pud_clear(pud_t *pudp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8108059c)
Location: arch/x86/include/asm/paravirt.h:513
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81083a87)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108905f)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff812627b1)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81278466)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8129ae3c)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
```
**Symbols:**

```
ffffffff8108059c-ffffffff810805bb: pud_clear (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
