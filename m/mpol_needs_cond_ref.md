# Function: <code>mpol_needs_cond_ref</code>

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
In mm/shmem.c (ffffffff811a67f4)
Location: include/linux/mempolicy.h:74
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff811dadb6)
Location: include/linux/mempolicy.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff811e1009)
Location: include/linux/mempolicy.h:74
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:mpol_misplaced
```
```
In fs/proc/task_mmu.c (ffffffff81277be5)
Location: include/linux/mempolicy.h:74
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff812f4c54)
Location: include/linux/mempolicy.h:74
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff811bf1c4)
Location: include/linux/mempolicy.h:74
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff811fad19)
Location: include/linux/mempolicy.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff812016f4)
Location: include/linux/mempolicy.h:74
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff812a3f45)
Location: include/linux/mempolicy.h:74
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff813286e5)
Location: include/linux/mempolicy.h:74
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff811cf7f4)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff8120b819)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff812131e4)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:SYSC_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff812b9a00)
Location: include/linux/mempolicy.h:75
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e432)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff811d6634)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff81216f03)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff8121e502)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:SYSC_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff812c6c66)
Location: include/linux/mempolicy.h:75
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813530fc)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff811ebb54)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff81231bb3)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff81239730)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:SYSC_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff812ea7e6)
Location: include/linux/mempolicy.h:76
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81377c6e)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff8120d30f)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff81254aec)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff8125cd12)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff81317cc7)
Location: include/linux/mempolicy.h:76
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6584)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff8122103f)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff81268ecc)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff812715f2)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8132eaa7)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf364)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff8123080f)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff81283f8c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff8128cc03)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/huge_memory.c (ffffffff812a6c6a)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/proc/task_mmu.c (ffffffff81356517)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9cbc)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff8123ea32)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff81293b2c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff8129c833)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8136e74b)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff81403d5c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff8126c0e8)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff812c71c0)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff812d048c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff813b637c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff81451bb0)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff81276b38)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff812d2d4c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff812dbfac)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff813c78fc)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e06b)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff8127bd6b)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff812d9690)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff812e381a)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff813cec5e)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff814734ac)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff812b9edb)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff81320180)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff8132aa50)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8142000c)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca0a1)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff81316555)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff8138d08e)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff8139884e)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff81497f7a)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff81555db7)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff8138aa60)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff8140ba14)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff814186b6)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8152bcea)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff815f74af)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff813bcf9f)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff8143f086)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio_vma
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
```
In mm/mempolicy.c (ffffffff8144bc09)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8156405b)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f67e)
Location: include/linux/mempolicy.h:73
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff813e9bfe)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_alloc_folio
```
```
In mm/swap_state.c (ffffffff8146685f)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8147a2c9)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
```
In mm/mempolicy.c (ffffffff814875bc)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8159aec4)
Location: include/linux/mempolicy.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
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
In mm/shmem.c (ffff8000102d0818)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffff800010331e04)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffff80001033b798)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffff800010438330)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffff8000104e250c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (c00000000038e2dc)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (c00000000040af08)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (c000000000416554)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/proc/task_mmu.c (c00000000054a9e0)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (c00000000061f58c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/shmem.c (ffffffff81237082)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff8128c10c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff81294e13)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff81366d2b)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc33c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff8122a0e2)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff8127df3c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff81286a23)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff813579cb)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecdbc)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff81234e22)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff81289f1c)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff81292c23)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff813647fb)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff813f96bc)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffff81245222)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/hugetlb.c (ffffffff81299d23)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff812a2a13)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/proc/task_mmu.c (ffffffff8137821b)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f317)
Location: include/linux/mempolicy.h:76
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
</details>
</li>
</ul>

## Differences
