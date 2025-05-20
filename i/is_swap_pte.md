# Function: <code>is_swap_pte</code>

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
In mm/mremap.c (0)
Location: include/linux/swapops.h:55
Inline: True
```
```
In mm/hugetlb.c (ffffffff811df4a3)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff811f0c63)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (ffffffff811fa8aa)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812780eb)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mremap.c (0)
Location: include/linux/swapops.h:55
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fdad5)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff812117c0)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8121bc4d)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8121e7c0)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812a4f89)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/mremap.c (0)
Location: include/linux/swapops.h:55
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff811f6feb)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hugetlb.c (ffffffff8120e5c5)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff81223980)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8122d675)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81230df0)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812ba8ee)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/mremap.c (0)
Location: include/linux/swapops.h:55
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81201ee3)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hugetlb.c (ffffffff8121a009)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff8122f2e0)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff8123972c)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8123c650)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812c865d)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/mremap.c (0)
Location: include/linux/swapops.h:56
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8121aa7c)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hugetlb.c (ffffffff812350bf)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff8124cb5e)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff8125855d)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8125c2d7)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812ec837)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mremap.c (ffffffff8123ae03)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c784)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hugetlb.c (ffffffff81258086)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff8127066e)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff8127ceb5)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8127fbe7)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff8131a04d)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mremap.c (ffffffff8124eff1)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250b92)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hugetlb.c (ffffffff8126c765)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff81284d1e)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff81291a1f)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81294557)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff81331120)
Location: include/linux/swapops.h:55
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mremap.c (ffffffff81261353)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262e72)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (ffffffff8127b0ce)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81287af0)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff8129f3ad)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812abdc8)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812b0819)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff81358f28)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mremap.c (ffffffff8126faf6)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81271622)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (ffffffff8128abae)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812976ff)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff812b074d)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812bd5d8)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812c2279)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff81371178)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mprotect.c (ffffffff8129e743)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a0122)
Location: include/linux/swapops.h:56
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812a18d9)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/swapfile.c (ffffffff812bd8dd)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812cac75)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff812e687d)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812f2d09)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812f912a)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff813b7d01)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/mprotect.c (ffffffff812a9b03)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab57f)
Location: include/linux/swapops.h:56
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812ad192)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/swapfile.c (ffffffff812c93fd)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812d6895)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff812f1bcd)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812fd340)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81304fbb)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff813c9791)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/mprotect.c (ffffffff812aef8e)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0982)
Location: include/linux/swapops.h:66
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b28fe)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (ffffffff812cff7f)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812dda49)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff812f7eed)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff813040ac)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8130a44b)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff813d0892)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/mprotect.c (ffffffff812f077e)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f2312)
Location: include/linux/swapops.h:66
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f4523)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (ffffffff81315490)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81324c1d)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff8134254d)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff8134dddc)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81355bab)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff81421ec8)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff81343203)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff813494b2)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81353e22)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81356073)
Location: include/linux/swapops.h:68
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813584f2)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8135d84d)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swap_state.c (ffffffff8137c15e)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81380a07)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81390c11)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff813b49be)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff813c703d)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff813cea47)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff813e4454)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e843b)
Location: include/linux/swapops.h:68
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8145da39)
Location: include/linux/swapops.h:68
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff814994a5)
Location: include/linux/swapops.h:68
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff813bb156)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff813c18a1)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813ce2cc)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d06b6)
Location: include/linux/swapops.h:124
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d2b2f)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff813d86ad)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f3de1)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f98fe)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff813ff30e)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8141271f)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81433b0e)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff8144aec7)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81453462)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8146bf2c)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff8147036a)
Location: include/linux/swapops.h:124
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ed46a)
Location: include/linux/swapops.h:124
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152e73c)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff813efe90)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff813f673a)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff81402ba9)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81404b90)
Location: include/linux/swapops.h:124
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8140736e)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8140ce9a)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81427281)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c78d)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff814321f2)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81445d24)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81469589)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff8147ebe9)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8148919b)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814a0c87)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a4b41)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81524160)
Location: include/linux/swapops.h:124
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81566a4c)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff8141b42b)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff814223ea)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff8142f1bc)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81431163)
Location: include/linux/swapops.h:124
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff814339de)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8143958d)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81460df1)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465edd)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146b5e2)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8147f75c)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8149849b)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff814af8d1)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff814b9054)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814d2417)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d5b78)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff815586ab)
Location: include/linux/swapops.h:124
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159d29f)
Location: include/linux/swapops.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:make_uffd_wp_pte
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/page_vma_mapped.c (ffff8000103072e8)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (ffff800010325dd4)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffff8000103354f4)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffff800010350d0c)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffff80001035eafc)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffff800010363d6c)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffff8000104396e4)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/page_vma_mapped.c (c0524d78)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/swapfile.c (c053d868)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/migrate.c (c05523f8)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (c055608c)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (c0601378)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/page_vma_mapped.c (c0000000003d5bd4)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (c0000000003fc214)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c00000000040f560)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (c000000000436b8c)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (c000000000447e9c)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (c000000000450e48)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (c00000000054d1a0)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/page_vma_mapped.c (ffffffe000212734)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (ffffffe0002261e0)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffe000231bde)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffe00023f6d6)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (ffffffe000241c3e)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffe0002d35e0)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mremap.c (ffffffff81268146)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269c72)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (ffffffff8128318e)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128fcdf)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff812a8d2d)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812b5bb8)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812ba859)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff81369758)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mremap.c (ffffffff8125a371)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125bed5)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (ffffffff81274c73)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128199f)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff8129a6ed)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812a6d65)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812aba17)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff813595ea)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mremap.c (ffffffff81265ee6)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81267a12)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (ffffffff81280f9e)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128daef)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff812a6b3d)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812b39c8)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812b8669)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff81367228)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mremap.c (ffffffff81275888)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812773a8)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/swapfile.c (ffffffff81290cae)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129d8a6)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff812b6e6f)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812c3e08)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812c8ca9)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff8137a877)
Location: include/linux/swapops.h:56
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
</ul>

## Differences
