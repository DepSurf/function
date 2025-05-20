# Function: <code>huge_ptep_get</code>

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
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:78
Inline: True
```
```
In mm/hugetlb.c (ffffffff811dd8c3)
Location: arch/x86/include/asm/hugetlb.h:78
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/mempolicy.c (ffffffff811dfe42)
Location: arch/x86/include/asm/hugetlb.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In fs/proc/task_mmu.c (ffffffff81276a85)
Location: arch/x86/include/asm/hugetlb.h:78
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fc49e)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff811fec0f)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In fs/proc/task_mmu.c (ffffffff812a47c5)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120cf8e)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8121044f)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In fs/proc/task_mmu.c (ffffffff812ba145)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
```
```
In mm/hugetlb.c (ffffffff8121a30f)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8121a97f)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812c7895)
Location: arch/x86/include/asm/hugetlb.h:79
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:80
Inline: True
```
```
In mm/hugetlb.c (ffffffff8123543e)
Location: arch/x86/include/asm/hugetlb.h:80
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81235bc3)
Location: arch/x86/include/asm/hugetlb.h:80
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/hugetlb.h:80
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812eb4af)
Location: arch/x86/include/asm/hugetlb.h:80
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:80
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/hugetlb.h:80
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/hugetlb.h:80
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/hugetlb.h:80
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/hugetlb.h:80
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/hugetlb.h:80
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/hugetlb.h:123
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/hugetlb.h:123
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/hugetlb.h:123
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
In mm/mincore.c (ffffffff81295d94)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff812cb100)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812ce948)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/userfaultfd.c (ffffffff813089a2)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8130b68a)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff8137458b)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff813b6f65)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (ffffffff812a0c84)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff812d6d10)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812da288)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/userfaultfd.c (ffffffff8131477f)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8131754e)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff813824e3)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff813c8605)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (ffffffff812a6564)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff812ddf40)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812e1ae8)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/userfaultfd.c (ffffffff8131a92c)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8131d24e)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff81389569)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff813cf645)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (ffffffff812e7a34)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81325150)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81328bc3)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/memory-failure.c (ffffffff8135ec30)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/userfaultfd.c (ffffffff81367828)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8136a5e9)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff813d6863)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81420a25)
Location: include/asm-generic/hugetlb.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (ffffffff81348c94)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81393a9c)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81397e03)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff813b4b5a)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
```
```
In mm/memory-failure.c (ffffffff813d90c0)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/userfaultfd.c (ffffffff813e4efc)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff813e81ac)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff8145d9ed)
Location: include/asm-generic/hugetlb.h:147
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81499905)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (ffffffff813c1044)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff8141245e)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81417a8a)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81433cea)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
```
```
In mm/memory-failure.c (ffffffff8145f0e0)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/userfaultfd.c (ffffffff8146c9df)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff814700ba)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff814ed41d)
Location: include/asm-generic/hugetlb.h:147
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152db15)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6606)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In mm/mincore.c (ffffffff813f62ba)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81445a26)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8144b00d)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff814696b4)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/memory-failure.c (ffffffff81495090)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/userfaultfd.c (ffffffff814a15f2)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/hmm.c (ffffffff814a4890)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff8152412b)
Location: include/asm-generic/hugetlb.h:147
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81565f45)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e6cc)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In mm/mincore.c (ffffffff81421f6a)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff8147f445)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81484a0d)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff814985e4)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/memory-failure.c (ffffffff814c4990)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/userfaultfd.c (ffffffff814d2372)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/hmm.c (ffffffff814d58c0)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff8155876c)
Location: include/asm-generic/hugetlb.h:147
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159df15)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff81667b9c)
Location: include/asm-generic/hugetlb.h:147
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1398)
Location: arch/arm64/include/asm/hugetlb.h:21
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_get_and_clear
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In mm/mincore.c (ffff8000102fcc3c)
Location: arch/arm64/include/asm/hugetlb.h:21
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffff800010335dcc)
Location: arch/arm64/include/asm/hugetlb.h:21
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffff800010338304)
Location: arch/arm64/include/asm/hugetlb.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/userfaultfd.c (ffff800010378824)
Location: arch/arm64/include/asm/hugetlb.h:21
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffff80001037b290)
Location: arch/arm64/include/asm/hugetlb.h:21
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffff8000103f95f8)
Location: arch/arm64/include/asm/hugetlb.h:21
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffff800010438e8c)
Location: arch/arm64/include/asm/hugetlb.h:21
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/hugetlb.h:123
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/hugetlb.h:123
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/hugetlb.h:123
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/hugetlb.h:123
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/hugetlb.h:123
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/hugetlb.h:123
Inline: True
```
</details>
</li>
</ul>

## Differences
