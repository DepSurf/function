# Function: <code>pmd_none_or_clear_bad</code>

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
In mm/memory.c (ffffffff811bcdf1)
Location: include/asm-generic/pgtable.h:382
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811c8afc)
Location: include/asm-generic/pgtable.h:382
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811ce45c)
Location: include/asm-generic/pgtable.h:382
Inline: True
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
In mm/memory.c (ffffffff811dcac5)
Location: include/asm-generic/pgtable.h:387
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811e4dad)
Location: include/asm-generic/pgtable.h:387
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811eae06)
Location: include/asm-generic/pgtable.h:387
Inline: True
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
In mm/memory.c (ffffffff811ec5d5)
Location: include/asm-generic/pgtable.h:411
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811f4de1)
Location: include/asm-generic/pgtable.h:411
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811fc066)
Location: include/asm-generic/pgtable.h:411
Inline: True
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
In mm/memory.c (ffffffff811f7551)
Location: include/asm-generic/pgtable.h:516
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811ffb0f)
Location: include/asm-generic/pgtable.h:516
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff81206ec3)
Location: include/asm-generic/pgtable.h:516
Inline: True
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
In mm/memory.c (ffffffff8120fa38)
Location: include/asm-generic/pgtable.h:517
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81218349)
Location: include/asm-generic/pgtable.h:517
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff8121fff1)
Location: include/asm-generic/pgtable.h:517
Inline: True
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
In mm/memory.c (ffffffff812307ba)
Location: include/asm-generic/pgtable.h:560
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239e50)
Location: include/asm-generic/pgtable.h:560
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/vmalloc.c (ffffffff8124123f)
Location: include/asm-generic/pgtable.h:560
Inline: True
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
In mm/memory.c (ffffffff81243b39)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124dc9b)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff81255920)
Location: include/asm-generic/pgtable.h:598
Inline: True
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
In mm/memory.c (ffffffff81255996)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8125fe55)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff81267c85)
Location: include/asm-generic/pgtable.h:598
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
In mm/memory.c (ffffffff81263f06)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff812765d5)
Location: include/asm-generic/pgtable.h:598
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
In mm/memory.c (ffffffff8129343e)
Location: include/linux/pgtable.h:772
Inline: True
Inline callers:
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff812a7b60)
Location: include/linux/pgtable.h:772
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
In mm/memory.c (ffffffff8129ddb3)
Location: include/linux/pgtable.h:821
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff812b2c30)
Location: include/linux/pgtable.h:821
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
In mm/memory.c (ffffffff812a4a38)
Location: include/linux/pgtable.h:821
Inline: True
Inline callers:
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff812b8803)
Location: include/linux/pgtable.h:821
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
In mm/memory.c (ffffffff812e3c3b)
Location: include/linux/pgtable.h:840
Inline: True
Inline callers:
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff812fec0c)
Location: include/linux/pgtable.h:840
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_range_noflush
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
In mm/memory.c (ffffffff81346f9d)
Location: include/linux/pgtable.h:873
Inline: True
Inline callers:
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff8136141d)
Location: include/linux/pgtable.h:873
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
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
In mm/memory.c (ffffffff813bf397)
Location: include/linux/pgtable.h:909
Inline: True
Inline callers:
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff813dcdb5)
Location: include/linux/pgtable.h:909
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
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
In mm/memory.c (ffffffff813f4017)
Location: include/linux/pgtable.h:921
Inline: True
Inline callers:
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff81411625)
Location: include/linux/pgtable.h:921
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
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
In mm/memory.c (ffffffff8141eca7)
Location: include/linux/pgtable.h:1052
Inline: True
Inline callers:
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff8143de15)
Location: include/linux/pgtable.h:1052
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
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
In mm/memory.c (ffff8000102fa704)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/vmalloc.c (ffff80001030c75c)
Location: include/asm-generic/pgtable.h:598
Inline: True
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
In arch/arm/mm/pgd.c (c031f94c)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - arch/arm/mm/pgd.c:pgd_free
```
```
In mm/memory.c (c0518b9c)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/vmalloc.c (c05282b4)
Location: include/asm-generic/pgtable.h:598
Inline: True
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
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5d10)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In mm/memory.c (c0000000003c4a4c)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/vmalloc.c (c0000000003dcce8)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_page_range
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
In mm/memory.c (ffffffe000209d48)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/vmalloc.c (ffffffe000215670)
Location: include/asm-generic/pgtable.h:598
Inline: True
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
In mm/memory.c (ffffffff8125c556)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff8126ec25)
Location: include/asm-generic/pgtable.h:598
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
In mm/memory.c (ffffffff8124eb71)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/vmalloc.c (ffffffff8126056e)
Location: include/asm-generic/pgtable.h:598
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
In mm/memory.c (ffffffff8125a2f6)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff8126c9c5)
Location: include/asm-generic/pgtable.h:598
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
In mm/memory.c (ffffffff81269cf6)
Location: include/asm-generic/pgtable.h:598
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/vmalloc.c (ffffffff8127c505)
Location: include/asm-generic/pgtable.h:598
Inline: True
```
</details>
</li>
</ul>

## Differences
