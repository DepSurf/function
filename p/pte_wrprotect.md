# Function: <code>pte_wrprotect</code>

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
In arch/x86/xen/mmu.c (ffffffff8102294f)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
```
```
In mm/memory.c (ffffffff811c13c8)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
```
```
In mm/hugetlb.c (ffffffff811dafa2)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
```
```
In mm/huge_memory.c (ffffffff811f76aa)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:208
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
In arch/x86/xen/mmu.c (ffffffff81021c7f)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
```
```
In mm/memory.c (ffffffff811dce5b)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
```
```
In mm/hugetlb.c (ffffffff811f910e)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
```
```
In mm/huge_memory.c (ffffffff812163af)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:222
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
In arch/x86/xen/mmu.c (ffffffff810223cf)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
```
```
In mm/memory.c (ffffffff811ec953)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
```
```
In mm/hugetlb.c (ffffffff81209cfb)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
```
```
In mm/huge_memory.c (ffffffff81228963)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:222
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:222
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
In arch/x86/xen/mmu_pv.c (ffffffff8102439f)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
```
```
In mm/memory.c (ffffffff811f77e1)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
```
```
In mm/hugetlb.c (ffffffff8121529b)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
```
```
In mm/huge_memory.c (ffffffff81231fdb)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:279
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
In arch/x86/xen/mmu_pv.c (ffffffff81024f3f)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
```
```
In mm/memory.c (ffffffff8120a510)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
```
```
In mm/hugetlb.c (ffffffff8122ff1b)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
```
```
In mm/huge_memory.c (ffffffff81252d5c)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:294
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
In arch/x86/xen/mmu_pv.c (ffffffff81025c5f)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
```
```
In mm/memory.c (ffffffff8122b375)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
```
```
In mm/hugetlb.c (ffffffff812523eb)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:304
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:304
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
In arch/x86/xen/mmu_pv.c (ffffffff8102580f)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
```
```
In mm/memory.c (ffffffff8123e7e9)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126664b)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
```
```
In mm/huge_memory.c (ffffffff81288a13)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:306
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:306
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
In arch/x86/xen/mmu_pv.c (ffffffff81027540)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/memory.c (ffffffff8125063e)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/hugetlb.c (ffffffff81281909)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a3659)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:323
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
In arch/x86/xen/mmu_pv.c (ffffffff81027b20)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/memory.c (ffffffff8125ebee)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/hugetlb.c (ffffffff81291319)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b4b59)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:323
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
In arch/x86/xen/mmu_pv.c (ffffffff81029a60)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
```
```
In mm/memory.c (ffffffff81291733)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_one_pte
```
```
In mm/mprotect.c (ffffffff8129e6bc)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c425c)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ea0ff)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c7c5)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:345
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:345
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
In arch/x86/xen/mmu_pv.c (ffffffff8102a440)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In mm/memory.c (ffffffff8129bfec)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812a9a7c)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cfa4c)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f52d5)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318705)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:344
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
In arch/x86/xen/mmu_pv.c (ffffffff8102b0e0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In mm/memory.c (ffffffff812a12d5)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812aef07)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In mm/hugetlb.c (ffffffff812dd042)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fb81f)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e8f5)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:344
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
In arch/x86/xen/mmu_pv.c (ffffffff8102f9f0)
Location: arch/x86/include/asm/pgtable.h:315
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly
```
```
In mm/memory.c (ffffffff812e221c)
Location: arch/x86/include/asm/pgtable.h:315
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812f06f7)
Location: arch/x86/include/asm/pgtable.h:315
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:315
Inline: True
```
```
In mm/hugetlb.c (ffffffff81324229)
Location: arch/x86/include/asm/pgtable.h:315
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:315
Inline: True
```
```
In mm/huge_memory.c (ffffffff8134565b)
Location: arch/x86/include/asm/pgtable.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bcd5)
Location: arch/x86/include/asm/pgtable.h:315
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:315
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:315
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
In arch/x86/xen/mmu_pv.c (ffffffff81034d86)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly
```
```
In mm/memory.c (ffffffff813432e2)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff81353d07)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/hugetlb.c (ffffffff81390699)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bb641)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff813e41c4)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9ecc)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:318
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
In arch/x86/xen/mmu_pv.c (ffffffff83e6f604)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init
```
```
In mm/memory.c (ffffffff813bb29c)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff813ce1db)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
```
```
In mm/hugetlb.c (ffffffff81410ee8)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143dc13)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff8146bc5b)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471f5c)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:335
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
In arch/x86/xen/mmu_pv.c (ffffffff83690504)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init
```
```
In mm/memory.c (ffffffff813ec942)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff81402a8f)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
```
```
In mm/swapfile.c (ffffffff81430721)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445b97)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81467c5b)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a688c)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff81042c86)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly
```
```
In mm/memory.c (ffffffff8141b525)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff8142f0d2)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81437ab8)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
```
```
In mm/swapfile.c (ffffffff814690db)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147f59d)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8148fd3d)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8149792b)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814a18ba)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814d0205)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d76cb)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159cdd1)
Location: arch/x86/include/asm/pgtable.h:376
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:make_uffd_wp_pte
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b16f4)
Location: arch/arm64/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect
```
```
In mm/memory.c (ffff8000102f6674)
Location: arch/arm64/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (0)
Location: arch/arm64/include/asm/pgtable.h:138
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/arm64/include/asm/pgtable.h:138
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/arm64/include/asm/pgtable.h:138
Inline: True
```
```
In mm/huge_memory.c (ffff800010355f10)
Location: arch/arm64/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/dax.c (0)
Location: arch/arm64/include/asm/pgtable.h:138
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
In mm/memory.c (c0518768)
Location: arch/arm/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (0)
Location: arch/arm/include/asm/pgtable.h:281
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/arm/include/asm/pgtable.h:281
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
In mm/memory.c (c0000000003be150)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:623
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (c0000000003d79d0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:623
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/hugetlb.c (c000000000406b00)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:623
Inline: True
```
```
In mm/ksm.c (c000000000419f2c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:623
Inline: True
```
```
In mm/huge_memory.c (c00000000043c3b0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:623
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/dax.c (c0000000005126a4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:623
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
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
In mm/memory.c (ffffffe00020a006)
Location: arch/riscv/include/asm/pgtable.h:247
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (0)
Location: arch/riscv/include/asm/pgtable.h:247
Inline: True
```
```
In mm/hugetlb.c (ffffffe00022f5cc)
Location: arch/riscv/include/asm/pgtable.h:247
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (0)
Location: arch/riscv/include/asm/pgtable.h:247
Inline: True
```
```
In fs/dax.c (0)
Location: arch/riscv/include/asm/pgtable.h:247
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
In arch/x86/xen/mmu_pv.c (ffffffff81027c80)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/memory.c (ffffffff8125723e)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/hugetlb.c (ffffffff812898f9)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ad139)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:323
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
In mm/memory.c (ffffffff81249b17)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/hugetlb.c (ffffffff8127b788)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/huge_memory.c (ffffffff8129e145)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:323
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
In arch/x86/xen/mmu_pv.c (ffffffff81027ae0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/memory.c (ffffffff81254fde)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/hugetlb.c (ffffffff81287709)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aaf49)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:323
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
In arch/x86/xen/mmu_pv.c (ffffffff81028720)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/memory.c (ffffffff81264a9a)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/hugetlb.c (ffffffff81298239)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bb299)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
</details>
</li>
</ul>

## Differences
