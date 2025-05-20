# Function: <code>pte_mkdirty</code>

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
In mm/gup.c (ffffffff811ba71e)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bc668)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/hugetlb.c (ffffffff811deddb)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/huge_memory.c (ffffffff811f7682)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:218
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
In mm/gup.c (ffffffff811d4d9a)
Location: arch/x86/include/asm/pgtable.h:232
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811daf32)
Location: arch/x86/include/asm/pgtable.h:232
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff811fd26c)
Location: arch/x86/include/asm/pgtable.h:232
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/huge_memory.c (ffffffff812175b6)
Location: arch/x86/include/asm/pgtable.h:232
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:232
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
In mm/gup.c (ffffffff811e4dd9)
Location: arch/x86/include/asm/pgtable.h:232
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eab37)
Location: arch/x86/include/asm/pgtable.h:232
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff8120dd31)
Location: arch/x86/include/asm/pgtable.h:232
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/huge_memory.c (ffffffff81229b4e)
Location: arch/x86/include/asm/pgtable.h:232
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:232
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
```
```
In mm/gup.c (ffffffff811ef3ac)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f5b88)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff8121781c)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/huge_memory.c (ffffffff81235726)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:289
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
```
```
In mm/gup.c (ffffffff81206507)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120d673)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff81232582)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
```
```
In mm/huge_memory.c (ffffffff81254129)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:304
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
```
```
In mm/gup.c (ffffffff812267c9)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122e375)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff81255582)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
```
```
In mm/huge_memory.c (ffffffff81273b57)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:314
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
```
```
In mm/gup.c (ffffffff8123ab11)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124216b)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff8126995d)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128811c)
Location: arch/x86/include/asm/pgtable.h:316
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:316
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/gup.c (ffffffff8124be4c)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812549b7)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff81284a97)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/huge_memory.c (ffffffff812a2d2e)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:333
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/gup.c (ffffffff8125a33c)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81262f17)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff81294637)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b422a)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:333
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
```
```
In mm/gup.c (ffffffff8128882c)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129238c)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff812c7a29)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813080c4)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
```
```
In mm/gup.c (ffffffff81292506)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129cc3c)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff812d3596)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81313e62)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
```
```
In mm/gup.c (ffffffff81297fb1)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a232b)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_reuse
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff812da3b9)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8131a01f)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In mm/gup.c (ffffffff812d89f1)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e369b)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/hugetlb.c (ffffffff813246ff)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81366f3a)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In mm/gup.c (ffffffff81338a1d)
Location: arch/x86/include/asm/pgtable.h:328
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81344a72)
Location: arch/x86/include/asm/pgtable.h:328
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/hugetlb.c (ffffffff81392cf1)
Location: arch/x86/include/asm/pgtable.h:328
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate_device.c (0)
Location: arch/x86/include/asm/pgtable.h:328
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813e419f)
Location: arch/x86/include/asm/pgtable.h:328
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813bcc73)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/hugetlb.c (ffffffff81411639)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff81432876)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (0)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143dc02)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff8146bc2f)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:346
Inline: True
```
```
In mm/memory.c (ffffffff813efcf2)
Location: arch/x86/include/asm/pgtable.h:346
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:346
Inline: True
```
```
In mm/migrate.c (ffffffff81467f88)
Location: arch/x86/include/asm/pgtable.h:346
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (0)
Location: arch/x86/include/asm/pgtable.h:346
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:346
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0a79)
Location: arch/x86/include/asm/pgtable.h:346
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In mm/gup.c (ffffffff8140f03a)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81420b13)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/hugetlb.c (ffffffff8147a0aa)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/ksm.c (ffffffff8148e66a)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81497c9d)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d56e)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a1878)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff814d01bc)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b16e0)
Location: arch/arm64/include/asm/pgtable.h:160
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In mm/shmem.c (ffff8000102d311c)
Location: arch/arm64/include/asm/pgtable.h:160
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffff8000102f1da0)
Location: arch/arm64/include/asm/pgtable.h:160
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fa070)
Location: arch/arm64/include/asm/pgtable.h:160
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffff800010305278)
Location: arch/arm64/include/asm/pgtable.h:160
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffff80001033596c)
Location: arch/arm64/include/asm/pgtable.h:160
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffff800010352f5c)
Location: arch/arm64/include/asm/pgtable.h:160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffff800010358304)
Location: arch/arm64/include/asm/pgtable.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035e694)
Location: arch/arm64/include/asm/pgtable.h:160
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffff80001037805c)
Location: arch/arm64/include/asm/pgtable.h:160
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In mm/shmem.c (0)
Location: arch/arm/include/asm/pgtable.h:296
Inline: True
```
```
In mm/gup.c (c05144a4)
Location: arch/arm/include/asm/pgtable.h:296
Inline: True
```
```
In mm/memory.c (c051be20)
Location: arch/arm/include/asm/pgtable.h:296
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/userfaultfd.c (0)
Location: arch/arm/include/asm/pgtable.h:296
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
In arch/powerpc/mm/ioremap.c (c000000000089508)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:663
Inline: True
Inline callers:
  - arch/powerpc/mm/ioremap.c:ioremap_prot
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011cad0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:663
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
```
```
In mm/shmem.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:663
Inline: True
```
```
In mm/gup.c (c0000000003b6610)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:663
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c4220)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:663
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (c00000000040ee6c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:663
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (c000000000439b10)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:663
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (c00000000044126c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:663
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c000000000447a5c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:663
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:663
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
In mm/shmem.c (0)
Location: arch/riscv/include/asm/pgtable.h:261
Inline: True
```
```
In mm/gup.c (ffffffe00020490c)
Location: arch/riscv/include/asm/pgtable.h:261
Inline: True
```
```
In mm/memory.c (ffffffe000209968)
Location: arch/riscv/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffe00022f5d6)
Location: arch/riscv/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/userfaultfd.c (0)
Location: arch/riscv/include/asm/pgtable.h:261
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/gup.c (ffffffff8125298c)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125b567)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff8128cc17)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ac80a)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:333
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/gup.c (ffffffff81245639)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124d84e)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff8127ea43)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/huge_memory.c (ffffffff8129e878)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:333
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/gup.c (ffffffff8125072c)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81259307)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff8128aa27)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aa61a)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:333
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
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/gup.c (ffffffff812600aa)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81268d07)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff8129a81c)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
```
In mm/huge_memory.c (ffffffff812baac0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
```
</details>
</li>
</ul>

## Differences
